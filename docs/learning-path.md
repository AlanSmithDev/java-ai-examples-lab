# Java AI 应用学习路线（基于本仓库示例）

## 阶段一：跑通第一个 LLM 调用
1. `open-ai-examples` —— 理解 ChatModel / EmbeddingModel 抽象
2. `ollama-examples` —— 改成本地模型，零成本反复实验

## 阶段二：RAG 基础
3. `pgvector-example` —— 向量存储 + 语义检索的最小闭环
4. `rag-examples` —— 进阶：查询改写、文档压缩、重排序

## 阶段三：工具与 Agent
5. `mcp-example` / `mcp-github-example` —— 模型调用外部工具
6. `customer-support-agent-example` —— 记忆 + 工具 + RAG 组合成 Agent

## 阶段四：生产化与框架集成
7. `spring-boot-example` —— 接入 Spring 生态
8. 任选一个向量库示例（milvus / weaviate / redis …）做横向对比

## 建议
- 每个示例先 `./mvnw compile` 确认能编译，再读 `src/main/java` 主类；
- 优先用 Ollama 本地模型，避免烧 API 额度；
- 把每个示例的"输入 → 模型 → 输出"画成一张图，比直接抄代码收获更大。
