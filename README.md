# Shaikh Nishan Mondal

**Software Engineer | Distributed Systems, Event-Driven Microservices, Cloud-Native Backends**

I design and build high-throughput, low-latency backend systems using Java, Spring Boot, Kafka, and Redis. My focus is on reliable service-to-service communication, data consistency across microservices, and performance engineering.

<p align="left">
  <a href="https://www.linkedin.com/in/sk-nishan-mondal-b7544425b/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:wizice855@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## Featured Projects

### [Banking Backend Core](https://github.com/Shaikh-NM/banking-backend-core)
An event-driven digital banking platform built from six Spring Boot microservices.

- Orchestrated **Saga pattern** for fund transfers, with compensating refunds so no transaction is left half-complete
- **Real-time fraud detection** (velocity, unusual amount, balance usage) with OTP verification backed by Redis
- Asynchronous messaging over **Kafka**, idempotent event handlers, and Redis-backed rate limiting at the API Gateway
- Razorpay payment integration with webhook handling

`Java 17` `Spring Boot 3` `Spring Cloud Gateway` `Kafka` `Redis` `MySQL` `OpenFeign`

### [Netflix Streaming Core](https://github.com/Shaikh-NM/netflix-streaming-core)
A video streaming backend covering ingestion, encoding, and secure adaptive playback.

- Raw uploads stored in **AWS S3**, then transcoded asynchronously with **FFmpeg** into multi-resolution (240p to 1080p) **HLS** output
- Upload and encoding decoupled through **Kafka** events so each stage scales independently
- Private S3 bucket with time-limited signed URLs; **Redis** caching for faster playback start-up

`Java` `Spring Boot` `Kafka` `Redis` `AWS S3` `FFmpeg` `HLS` `Docker`

### [Stock Trading Platform](https://github.com/Shaikh-NM/stock-trading-platform)
A distributed trading platform with live market data and AI-assisted trade analysis.

- Nine-service architecture with **JWT** validated centrally at the API Gateway
- **WebSocket** price streaming and event-driven order, funds, portfolio, and notification flow over **Kafka**
- AI service that uses the **Claude API** to analyze a trade before the user confirms it

`Java` `Spring Boot` `Spring Security` `JWT` `WebSocket` `Kafka` `Redis` `Claude API`

> These projects are built for learning and portfolio purposes. The trading platform does not execute real trades, and the streaming project is not affiliated with Netflix.

---

## Technical Skills

| Area | Technologies |
| :--- | :--- |
| **Languages** | Java, Go, Python, C++, C#, TypeScript, JavaScript, Scala, Bash |
| **Backend & Frameworks** | Spring Boot, Spring Cloud, FastAPI, NestJS, Node.js, Django, .NET, GraphQL |
| **Messaging & Streaming** | Apache Kafka, RabbitMQ, Apache Spark, Apache Flink, Apache Airflow |
| **Databases & Caching** | PostgreSQL, MySQL, Redis, MongoDB, Cassandra, DynamoDB, Elasticsearch, Neo4j |
| **Cloud & DevOps** | AWS, GCP, Azure, Docker, Kubernetes, Nginx, GitHub Actions, GitLab CI, Jenkins |
| **Observability** | Datadog |
| **AI / ML** | LangChain, LangGraph, Claude API, OpenAI, Hugging Face, Ollama, PyTorch, TensorFlow, MLflow, Pinecone, ChromaDB |

<details>
<summary>Badge view</summary>
<br />

<p align="left">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring-%236DB33F.svg?style=flat&logo=spring&logoColor=white" alt="Spring" />
  <img src="https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=flat&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-%23326CE5.svg?style=flat&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

</details>

---

## Focus Areas

- **Distributed systems:** event-driven design, Saga orchestration, idempotent consumers, eventual consistency
- **Performance:** low-latency APIs, caching strategies, rate limiting, throughput tuning
- **Cloud-native delivery:** containerized services, CI/CD, Kubernetes orchestration
- **Applied AI:** integrating LLMs into backend workflows and agentic systems

## Currently

- Building and refining microservice architectures with Kafka and Redis
- Studying distributed consensus algorithms and multi-agent LLM systems
- Exploring eBPF tracing for fine-grained cloud-native performance profiling

## Open to

- Collaborating on open-source backend infrastructure and low-latency API tooling
- Conversations about backend design, Kafka, Kubernetes, and performance engineering

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=Shaikh-NM&theme=holi&hide_border=false&include_all_commits=true&count_private=true" height="175" alt="GitHub Stats" />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Shaikh-NM&theme=holi&hide_border=false&include_all_commits=true&count_private=true&layout=compact" height="175" alt="Top Languages" />
</p>

---

## Get in Touch

- LinkedIn: [sk-nishan-mondal](https://www.linkedin.com/in/sk-nishan-mondal-b7544425b/)
- Email: [wizice855@gmail.com](mailto:wizice855@gmail.com)
