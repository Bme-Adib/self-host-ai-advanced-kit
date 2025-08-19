# Self-hosted AI starter kit

**Self-hosted AI Starter Kit** is an open-source Docker Compose template designed to swiftly initialize a comprehensive local AI and low-code development environment.

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/self-hosted-ai-starter-kit/main/assets/n8n-demo.gif)

Curated by <https://github.com/n8n-io>, it combines the self-hosted n8n
platform with a curated list of compatible AI products and components to
quickly get started with building self-hosted AI workflows.

> [!TIP]
> [Read the announcement](https://blog.n8n.io/self-hosted-ai/)

### What’s included

✅ [**Self-hosted n8n**](https://n8n.io/) - Low-code platform with over 400
integrations and advanced AI components

✅ [**Ollama**](https://ollama.com/) - Cross-platform LLM platform to install
and run the latest local LLMs

✅ [**Open WebUi**](https://openwebui.com/) - Open WebUI is an extensible, 
self-hosted AI interface that adapts to your workflow, all while operating entirely offline.

✅ [**Qdrant**](https://qdrant.tech/) - Open-source, high performance vector
store with an comprehensive API

✅ [**PostgreSQL**](https://www.postgresql.org/) -  Workhorse of the Data
Engineering world, handles large amounts of data safely.

### What you can build

⭐️ **AI Agents** for scheduling appointments

⭐️ **Summarize Company PDFs** securely without data leaks

⭐️ **Smarter Slack Bots** for enhanced company communications and IT operations

⭐️ **Private Financial Document Analysis** at minimal cost

### What's different in this fork?

🎶 **Connect with your own domain** to connect to google services

🎶 **youtube video** to help you go step by step

🎶 **have your open webui** accessable from any Pc on the internet

## Installation

### Cloning the Repository

```bash
git clone https://github.com/Bme-Adib/self-host-ai-advanced-kit.git
cd self-host-ai-advanced-kit
```

### Running n8n using Docker Compose

#### For Nvidia GPU users
in te same folder where to cloned the files
run the command

```bash
docker compose --profile gpu-nvidia up -d
```

> [!NOTE]
> If you have not used your Nvidia GPU with Docker before, please follow the
> [Ollama Docker instructions](https://github.com/ollama/ollama/blob/main/docs/docker.md).

### For AMD GPU users on Linux
in te same folder where to cloned the files
run the command

```bash
docker compose --profile gpu-amd up -d
```

### To run using CPU only
in te same folder where to cloned the files
run the command

```bash
docker compose up -d
```

## Upgrading

Open powershell and navigate to the folde where you have the docker-compose.yml and 

```bash
docker compose down
docker compose pull
docker compose --profile gpu-nvidia up -d
```


## 👓 Recommended reading

n8n is full of useful content for getting started quickly with its AI concepts
and nodes. If you run into an issue, go to [support](#support).

- [AI agents for developers: from theory to practice with n8n](https://blog.n8n.io/ai-agents/)
- [Tutorial: Build an AI workflow in n8n](https://docs.n8n.io/advanced-ai/intro-tutorial/)
- [Langchain Concepts in n8n](https://docs.n8n.io/advanced-ai/langchain/langchain-n8n/)
- [Demonstration of key differences between agents and chains](https://docs.n8n.io/advanced-ai/examples/agent-chain-comparison/)
- [What are vector databases?](https://docs.n8n.io/advanced-ai/examples/understand-vector-databases/)

## 🎥 Video walkthrough

- 

## 💬 Support

Join the conversation in the [n8n Forum](https://community.n8n.io/), where you
can:

f you need any help feel free to reach out — I’m always open for questions and collaborations. You can DM me anytime and follow me to stay updated
with the latest tutorials, projects, and tips I share. Connect with me on 
- [The Biomed Nest Youtube Channel](https://www.youtube.com/@thebiomednest)
- [The Biomed Nest instagram](https://www.instagram.com/thebiomednest)

to learn more and never miss new content.
