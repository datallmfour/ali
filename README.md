# Open WebUI 👋

![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub language count](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub top language](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

**Open WebUI is an [extensible](https://docs.openwebui.com/features/plugin/), feature-rich, and user-friendly self-hosted AI platform designed to operate entirely offline.** It supports various LLM runners like **Ollama** and **OpenAI-compatible APIs**, with **built-in inference engine** for RAG, making it a **powerful AI deployment solution**.

Passionate about open-source AI? [Join our team →](https://careers.openwebui.com/)

![Open WebUI Demo](./demo.gif)

> [!TIP]  
> **Looking for an [Enterprise Plan](https://docs.openwebui.com/enterprise)?** – **[Speak with Our Sales Team Today!](https://docs.openwebui.com/enterprise)**
>
> Get **enhanced capabilities**, including **custom theming and branding**, **Service Level Agreement (SLA) support**, **Long-Term Support (LTS) versions**, and **more!**

For more information, be sure to check out our [Open WebUI Documentation](https://docs.openwebui.com/).

## Key Features of Open WebUI ⭐

- 🚀 **Effortless Setup**: Install seamlessly using Docker or Kubernetes (kubectl, kustomize or helm) for a hassle-free experience with support for both `:ollama` and `:cuda` tagged images.

- 🤝 **Ollama/OpenAI API Integration**: Effortlessly integrate OpenAI-compatible APIs for versatile conversations alongside Ollama models. Customize the OpenAI API URL to link with **LMStudio, GroqCloud, Mistral, OpenRouter, and more**.

- 🛡️ **Granular Permissions and User Groups**: By allowing administrators to create detailed user roles and permissions, we ensure a secure user environment. This granularity not only enhances security but also allows for customized user experiences, fostering a sense of ownership and responsibility amongst users.

- 📱 **Responsive Design**: Enjoy a seamless experience across Desktop PC, Laptop, and Mobile devices.

- 📱 **Progressive Web App (PWA) for Mobile**: Enjoy a native app-like experience on your mobile device with our PWA, providing offline access on localhost and a seamless user interface.

- ✒️🔢 **Full Markdown and LaTeX Support**: Elevate your LLM experience with comprehensive Markdown and LaTeX capabilities for enriched interaction.

- 🎤📹 **Hands-Free Voice/Video Call**: Experience seamless communication with integrated hands-free voice and video call features using multiple Speech-to-Text providers (Local Whisper, OpenAI, Deepgram, Azure) and Text-to-Speech engines (Azure, ElevenLabs, OpenAI, Transformers, WebAPI), allowing for dynamic and interactive chat environments.

- 🛠️ **Model Builder**: Easily create Ollama models via the Web UI. Create and add custom characters/agents, customize chat elements, and import models effortlessly through [Open WebUI Community](https://openwebui.com/) integration.

- 🐍 **Native Python Function Calling Tool**: Enhance your LLMs with built-in code editor support in the tools workspace. Bring Your Own Function (BYOF) by simply adding your pure Python functions, enabling seamless integration with LLMs.

- 💾 **Persistent Artifact Storage**: Built-in key-value storage API for artifacts, enabling features like journals, trackers, leaderboards, and collaborative tools with both personal and shared data scopes across sessions.

- 📚 **Local RAG Integration**: Dive into the future of chat interactions with groundbreaking Retrieval Augmented Generation (RAG) support using your choice of 9 vector databases and multiple content extraction engines (Tika, Docling, Document Intelligence, Mistral OCR, External loaders). Load documents directly into chat or add files to your document library, effortlessly accessing them using the `#` command before a query.

- 🔍 **Web Search for RAG**: Perform web searches using 15+ providers including `SearXNG`, `Google PSE`, `Brave Search`, `Kagi`, `Mojeek`, `Tavily`, `Perplexity`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `SearchApi`, `SerpApi`, `Bing`, `Jina`, `Exa`, `Sougou`, `Azure AI Search`, and `Ollama Cloud`, injecting results directly into your chat experience.

- 🌐 **Web Browsing Capability**: Seamlessly integrate websites into your chat experience using the `#` command followed by a URL. This feature allows you to incorporate web content directly into your conversations, enhancing the richness and depth of your interactions.

- 🎨 **Image Generation & Editing Integration**: Create and edit images using multiple engines including OpenAI's DALL-E, Gemini, ComfyUI (local), and AUTOMATIC1111 (local), with support for both generation and prompt-based editing workflows.

- ⚙️ **Many Models Conversations**: Effortlessly engage with various models simultaneously, harnessing their unique strengths for optimal responses. Enhance your experience by leveraging a diverse set of models in parallel.

- 🔐 **Role-Based Access Control (RBAC)**: Ensure secure access with restricted permissions; only authorized individuals can access your Ollama, and exclusive model creation/pulling rights are reserved for administrators.

- 🗄️ **Flexible Database & Storage Options**: Choose from SQLite (with optional encryption), PostgreSQL, or configure cloud storage backends (S3, Google Cloud Storage, Azure Blob Storage) for scalable deployments.

- 🔍 **Advanced Vector Database Support**: Select from 9 vector database options including ChromaDB, PGVector, Qdrant, Milvus, Elasticsearch, OpenSearch, Pinecone, S3Vector, and Oracle 23ai for optimal RAG performance.

- 🔐 **Enterprise Authentication**: Full support for LDAP/Active Directory integration, SCIM 2.0 automated provisioning, and SSO via trusted headers alongside OAuth providers. Enterprise-grade user and group provisioning through SCIM 2.0 protocol, enabling seamless integration with identity providers like Okta, Azure AD, and Google Workspace for automated user lifecycle management.

- ☁️ **Cloud-Native Integration**: Native support for Google Drive and OneDrive/SharePoint file picking, enabling seamless document import from enterprise cloud storage.

- 📊 **Production Observability**: Built-in OpenTelemetry support for traces, metrics, and logs, enabling comprehensive monitoring with your existing observability stack.

- ⚖️ **Horizontal Scalability**: Redis-backed session management and WebSocket support for multi-worker and multi-node deployments behind load balancers.

- 🌐🌍 **Multilingual Support**: Experience Open WebUI in your preferred language with our internationalization (i18n) support. Join us in expanding our supported languages! We're actively seeking contributors!

- 🧩 **Pipelines, Open WebUI Plugin Support**: Seamlessly integrate custom logic and Python libraries into Open WebUI using [Pipelines Plugin Framework](https://github.com/open-webui/pipelines). Launch your Pipelines instance, set the OpenAI URL to the Pipelines URL, and explore endless possibilities. [Examples](https://github.com/open-webui/pipelines/tree/main/examples) include **Function Calling**, User **Rate Limiting** to control access, **Usage Monitoring** with tools like Langfuse, **Live Translation with LibreTranslate** for multilingual support, **Toxic Message Filtering** and much more.

- 🌟 **Continuous Updates**: We are committed to improving Open WebUI with regular updates, fixes, and new features.

Want to learn more about Open WebUI's features? Check out our [Open WebUI documentation](https://docs.openwebui.com/features) for a comprehensive overview!

---

We are incredibly grateful for the generous support of our sponsors. Their contributions help us to maintain and improve our project, ensuring we can continue to deliver quality work to our community. Thank you!

## How to Install 🚀

### Installation via Python pip 🐍

Open WebUI can be installed using pip, the Python package installer. Before proceeding, ensure you're using **Python 3.11** to avoid compatibility issues.

1. **Install Open WebUI**:
   Open your terminal and run the following command to install Open WebUI:

   ```bash
   pip install open-webui
   ```

2. **Running Open WebUI**:
   After installation, you can start Open WebUI by executing:

   ```bash
   open-webui serve
   ```

This will start the Open WebUI server, which you can access at [http://localhost:8080](http://localhost:8080)

### Quick Start with Docker 🐳

> [!NOTE]  
> Please note that for certain Docker environments, additional configurations might be needed. If you encounter any connection issues, our detailed guide on [Open WebUI Documentation](https://docs.openwebui.com/) is ready to assist you.

> [!WARNING]
> When using Docker to install Open WebUI, make sure to include the `-v open-webui:/app/backend/data` in your Docker command. This step is crucial as it ensures your database is properly mounted and prevents any loss of data.

> [!TIP]  
> If you wish to utilize Open WebUI with Ollama included or CUDA acceleration, we recommend utilizing our official images tagged with either `:cuda` or `:ollama`. To enable CUDA, you must install the [Nvidia CUDA container toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) on your Linux/WSL system.

### Installation with Default Configuration

- **If Ollama is on your computer**, use this command:

  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **If Ollama is on a Different Server**, use this command:

  To connect to Ollama on another server, change the `OLLAMA_BASE_URL` to the server's URL:

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **To run Open WebUI with Nvidia GPU support**, use this command:

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```

### Installation for OpenAI API Usage Only

- **If you're only using OpenAI API**, use this command:

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

### Installing Open WebUI with Bundled Ollama Support

This installation method uses a single container image that bundles Open WebUI with Ollama, allowing for a streamlined setup via a single command. Choose the appropriate command based on your hardware setup:

- **With GPU Support**:
  Utilize GPU resources by running the following command:

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

- **For CPU Only**:
  If you're not using a GPU, use this command instead:

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

Both commands facilitate a built-in, hassle-free installation of both Open WebUI and Ollama, ensuring that you can get everything up and running swiftly.

After installation, you can access Open WebUI at [http://localhost:3000](http://localhost:3000). Enjoy! 😄

### Other Installation Methods

We offer various installation alternatives, including non-Docker native installation methods, Docker Compose, Kustomize, and Helm. Visit our [Open WebUI Documentation](https://docs.openwebui.com/getting-started/) or join our [Discord community](https://discord.gg/5rJgQTnV4s) for comprehensive guidance.

Look at the [Local Development Guide](https://docs.openwebui.com/getting-started/advanced-topics/development) for instructions on setting up a local development environment.

### Troubleshooting

Encountering connection issues? Our [Open WebUI Documentation](https://docs.openwebui.com/troubleshooting/) has got you covered. For further assistance and to join our vibrant community, visit the [Open WebUI Discord](https://discord.gg/5rJgQTnV4s).

#### Open WebUI: Server Connection Error

If you're experiencing connection issues, it’s often due to the WebUI docker container not being able to reach the Ollama server at 127.0.0.1:11434 (host.docker.internal:11434) inside the container . Use the `--network=host` flag in your docker command to resolve this. Note that the port changes from 3000 to 8080, resulting in the link: `http://localhost:8080`.

**Example Docker Command**:

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### Keeping Your Docker Installation Up-to-Date

In case you want to update your local Docker installation to the latest version, you can do it with [Watchtower](https://containrrr.dev/watchtower/):

```bash
docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui
```

In the last part of the command, replace `open-webui` with your container name if it is different.

Check our Updating Guide available in our [Open WebUI Documentation](https://docs.openwebui.com/getting-started/updating).

### Using the Dev Branch 🌙

> [!WARNING]
> The `:dev` branch contains the latest unstable features and changes. Use it at your own risk as it may have bugs or incomplete features.

If you want to try out the latest bleeding-edge features and are okay with occasional instability, you can use the `:dev` tag like this:

```bash
docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart always ghcr.io/open-webui/open-webui:dev
```

### Offline Mode

If you are running Open WebUI in an offline environment, you can set the `HF_HUB_OFFLINE` environment variable to `1` to prevent attempts to download models from the internet.

```bash
export HF_HUB_OFFLINE=1
```

## What's Next? 🌟

Discover upcoming features on our roadmap in the [Open WebUI Documentation](https://docs.openwebui.com/roadmap/).

## License 📜

This project contains code under multiple licenses. The current codebase includes components licensed under the Open WebUI License with an additional requirement to preserve the "Open WebUI" branding, as well as prior contributions under their respective original licenses. For a detailed record of license changes and the applicable terms for each section of the code, please refer to [LICENSE_HISTORY](./LICENSE_HISTORY). For complete and updated licensing details, please see the [LICENSE](./LICENSE) and [LICENSE_HISTORY](./LICENSE_HISTORY) files.

## Support 💬

If you have any questions, suggestions, or need assistance, please open an issue or join our
[Open WebUI Discord community](https://discord.gg/5rJgQTnV4s) to connect with us! 🤝

## Star History

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---

Created by [Timothy Jaeryang Baek](https://github.com/tjbck) - Let's make Open WebUI even more amazing together! 💪


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-06 13:53:36`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-07 09:41:09`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-08 09:25:27`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-09 09:25:03`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-10 09:26:44`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-11 09:27:39`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-12 09:27:11`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-13 09:22:38`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-14 09:41:36`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-15 09:39:52`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-16 09:28:09`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-17 09:23:22`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-18 09:24:02`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-19 09:27:07`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-20 09:23:08`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-21 09:41:47`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-22 09:40:51`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-23 09:27:25`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-24 09:26:27`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-25 09:27:35`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-26 09:27:29`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-27 09:25:44`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-28 09:46:02`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-29 09:44:45`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-30 09:28:01`*


---
*由 GitHub Actions 自动同步于北京时间：`2025-12-31 09:28:50`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-01 09:47:25`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-02 09:39:23`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-03 09:25:00`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-04 09:47:28`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-05 09:47:25`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-06 09:39:23`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-07 09:39:17`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-08 09:39:24`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-09 09:39:43`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-10 09:27:26`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-11 09:47:31`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-12 09:44:07`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-13 09:26:46`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-14 09:47:19`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-15 09:28:27`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-16 09:40:08`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-17 09:26:42`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-18 09:46:08`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-19 09:44:40`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-20 09:39:49`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-21 09:43:05`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-22 09:42:49`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-23 09:39:43`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-24 09:28:13`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-25 09:49:16`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-26 09:48:45`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-27 09:45:53`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-28 09:42:26`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-29 09:54:13`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-30 09:54:52`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-01-31 09:50:49`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-01 10:10:24`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-02 10:02:22`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-03 10:01:00`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-04 09:55:39`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-05 09:57:30`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-06 09:56:28`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-07 09:53:12`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-08 10:26:30`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-09 10:04:22`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-10 10:13:52`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-11 10:10:04`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-12 10:03:34`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-13 10:06:37`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-14 09:55:21`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-15 10:05:46`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-16 10:01:28`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-17 09:59:21`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-18 10:03:06`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-19 10:01:44`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-20 09:57:27`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-21 09:52:47`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-22 10:01:13`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-23 10:02:24`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-24 09:58:50`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-25 10:01:11`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-26 09:56:55`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-27 09:55:48`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-02-28 09:46:30`*


---
*由 GitHub Actions 自动同步于北京时间：`2026-03-01 10:08:16`*

