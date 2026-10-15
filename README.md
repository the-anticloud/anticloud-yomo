# YOMO

> Anticloud offline package — upstream: yomorun/yomo @ `main`.

## What This Project Does

🦖 Serverless AI Agent Framework with Geo-distributed Edge AI Infra.

**Topics:** a2a-protocol, agent-framework, claude-code, distributed-cloud, function-calling, geodistributedsystems, managed-skills, mcp, openai, quic, realtime, serverless, skills, yomo

## Upstream README

<p align="center">
  <img width="200px" height="200px" src="https://blog.yomo.run/static/images/logo.png" />
</p>

# YoMo [![codecov](https://codecov.io/gh/yomorun/yomo/branch/main/graph/badge.svg)](https://codecov.io/gh/yomorun/yomo)

YoMo is an open-source LLM Function Calling Framework for building scalable and ultra-fast AI Agents.
💚 We care about: **Empowering Exceptional Customer Experiences in the Age of AI**

We believe that seamless and responsive AI interactions are key to delivering outstanding customer experiences. YoMo is built with this principle at its core, focusing on speed, reliability, and scalability.

## 🌶 Features

|    | **Features** |    |
| -- | ------------ | -- |
| ⚡️ | **Serverless LLM Tools** | Deploy and Manage LLM Tools / Skills seamlessly. |
| 🔐 | **Enhanced Security** | TLS v1.3 encryption is applied to every data packet by design, ensuring robust security for your AI agent communications. |
| 📸 | **Effortless Agents DevOps** | Streamline the entire lifecycle of your LLM tools, from development to deployment. Significantly reduces operational overhead, allowing you to focus exclusively on creating innovative AI agent functionalities. |
| 🌎 | **Geo-Distributed Architecture** | Bring AI inference and tools closer to your users with our globally distributed architecture, resulting in significantly faster response times and a superior user experience for your AI agents. |

## 🚀 Getting Started

Let's build a simple AI agent with LLM Function Calling to provide weather information:

### Step 1. Install CLI

```sh
curl -fsSL https://get.yomo.run | sh
```

Verify the installation:

```sh
yomo --version
```

### Step 2. Start the server

Use Ollama as the LLM provider:

```sh
ollama pull ornith
```

Launch the server:

```sh
yomo serve
```

You can also use the `--config` flag to specify a custom coniguration yaml file.

### Step 3. Implement the LLM Function Calling

```sh
yomo init
```

Finished, now, let's run it:

```bash
yomo run -n get-weather ./app
```

### Done, let's have a try

```sh
curl http://127.0.0.1:9001/v1/chat/completions \
-H "Content-Type: application/json" \
-d '{
  "messages": [
    {
      "role": "user",
      "content": "I am going for a hike on the Yarra Bend Park Loop. What should I wear?"
    }
  ]
}'
```

You'll receive a helpful response like this:

```
Yarra Bend Park is on the Yarra River and gets misty/foggy when it overflows from its channel into the park—this typically occurs on damp autumns around November. Today's conditions are mild, warm, dry, with no fog expected today but a chance of light rain or drizzle possible tomorrow afternoon.

**Clothing for your hike:**
- **Base/mid-layer:** A long-sleeve top is enough. If it gets chilly at the river bank (a 2°C drop is possible), add a fleece mid-layer rather than relying on just an autumn outer shell.
- **Pants:** Jeans are okay if you want them, but light hiking pants or athletic wear are more comfortable and dry faster.
- **Footwear:**

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
