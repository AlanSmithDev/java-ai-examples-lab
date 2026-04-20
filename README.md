# Java AI 应用示例实验室 (java-ai-examples-lab)

> 基于 [LangChain4j](https://github.com/langchain4j/langchain4j) 官方示例集整理的学习型仓库。
> 原始项目以 Apache-2.0 许可证发布，本仓库保留其 LICENSE 与署名（见 NOTICE），仅做中文梳理、模块化拆分与本地化说明，便于系统性学习 Java 大模型 / RAG / Agent 应用开发。

## 这个仓库是什么

一个按"能力维度"重新组织的 Java LLM 应用示例集合，覆盖：模型接入、向量存储、RAG 高级技巧、工具调用 / MCP、Agent，以及主流 Java 框架（Spring Boot / Quarkus / Helidon 等）的集成。每个示例都是可独立运行的 Maven 子模块。

## 目录地图（按能力分组）

### 模型接入
- `open-ai-examples`：OpenAI 聊天 / 嵌入 / 函数调用
- `ollama-examples`：本地 Ollama 模型（离线可用，零成本）
- `anthropic-examples`：Claude 接入
- `bedrock-examples`：AWS Bedrock
- `azure-open-ai-examples` / `azure-open-ai-customer-support-agent-example`：Azure OpenAI 与客服 Agent
- `google-ai-gemini-examples` / `vertex-ai-gemini-examples`：Gemini
- `mistral-ai-examples`：Mistral
- `watsonx-ai-examples` / `ovh-ai-examples`：IBM Watsonx / OVHcloud
- `voyage-ai-examples`：VoyageAI 嵌入

### 向量存储（RAG 底座）
`pgvector-example`、`chroma-example`、`weaviate-example`、`milvus-example`、`neo4j-example`、`redis-example`、`qdrant-example`、`pinecone-example`、`elasticsearch-example`、`opensearch-example`、`couchbase-example`、`infinispan-example`、`vespa-example`、`jvector-example`、`google-alloydb-example`、`oracle-example`、`yugabytedb-example`、`s3-vectors-example`

### RAG / Agent / 工具
- `rag-examples`：高级 RAG 技术（多查询 / 压缩 / 重排等）
- `customer-support-agent-example`：带记忆 / 工具 / RAG 的客服 Agent
- `mcp-example` / `mcp-github-example`：MCP 协议客户端与 GitHub 工具
- `agentic-tutorial`：Agent 入门教程

### 框架集成
`quarkus-example`、`helidon-examples`、`jakartaee-microprofile-example`、`payara-micro-example`、`wildfly-example`、`hibernate-example`、`javafx-example`、`spring-boot-example`、`spring-boot4-example`、`native-java-gemini-function-calling-example`

### 教程 / 其他
`tutorials`、`other-examples`、`jlama-examples`（本地 Jlama 模型）、`gpullama3.java-example`（GPU Llama3）、`dbpedia-example`（知识库问答）

## 如何运行

每个子模块是独立 Maven 工程：

```bash
cd open-ai-examples
./mvnw compile   # 或本机 mvn
```

多数示例需要对应 API Key（OpenAI 等）；使用 `ollama-examples` 可完全本地离线运行。Key 在 `src/main/resources/application.properties` 或环境变量中配置。

## 许可与署名

- 原始项目：LangChain4j Examples，Apache-2.0。
- 本仓库保留原始 LICENSE；修改与整理说明见 NOTICE。
- 本仓库为学习整理用途，不声称原创代码，所有示例源码著作权归 LangChain4j 作者所有。
