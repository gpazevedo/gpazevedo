### Hi there 👋

- 🔭 I'm currently Building AI/ML Infrastructure & Platforms
- 🌱 I’ve worked to improve Developer Experience in Generative AI, Agentic Systems, and Event-Driven Systems
- 💻 Playing with Strands, LangGraph, MCP, KubeFlow, MLFlow.
- 👯 I’m looking to collaborate on AI Open Source Projects
- 🤔 I’m looking for Disruptive AI/ML Use Cases
- 🚀 I'm learning BedRock AgentCore
- 💬 Ask me about AI, Software Architecture, Observability, DDD, Data Mesh, CDC & Event-Driven Architecture
- 📫 How to reach me: https://www.linkedin.com/in/gpazevedo/
- ⚡ Fun fact: I feel like "I'm Back to School !"

![Procurement Negotiation Agentic System (PNAS)](./PNAS-Architecture-AWS.drawio.svg)
This system was designed and developed through a deep integration of business strategy and high-fidelity engineering.

To ensure the technical solution addressed real-world needs, I began by researching the business domain to propose a commercially sound architecture. The design phase involved defining the **core agent topology, governance models, and security posture**, using **PRDs with EARS requirements** to maintain formal traceability from business goals to technical specs.

For the implementation, I built the end-to-end stack using **Strands agents on Python 3.14**, automating the deployment to **AgentCore** via **Terraform and GitHub Actions**. The system utilizes **AppConfig** for dynamic runtime configuration and includes dedicated strategies for **observability and cost optimization**. 

![Spring AI App deployed at AWS AgentCore](./infrastructure.svg)
*Basic Generative AI app, built with Spring Boot 4, Spring AI 2 with full Observability, deployed at AWS Bedrock AgentCore*

![AI Teleprompter](./architecture.svg)
*Browser-based AI Teleprompter for public speakers*

![Kafka Ingestor](./Kafka_Service.png)
*Contract-based production of Avro events from a JSON payload to a Kafka Topic. Service converts a JSON payload to an Avro payload based on a verified schema and publishes it to a Kafka topic, using the Outbox Pattern*

![Side Kafka](./Side-Kafka-EN.png)

*Sidecar that converts a JSON payload to Avro payload based on a verified schema and publishes it to a Kafka topic*

![Kafka DLQ on Apache Beam](./Beam_Kafka_DLQ.png)
*Kafka Dead Letter Queue on Apache Beam*

![Goals Service](./Goals_Service.jpg)
*Goals Service*

![Event Modelling](./blueprint.jpg)
*Hotel Event Modelling*

![CQRS](https://github.com/gpazevedo/account_api/blob/main/docs/Accounts_API.png)
*Syncronous Bank API*

![ETL Hexagonal](./CoffeeShop_Architecture.png) <br>
*Shop Accounting*
