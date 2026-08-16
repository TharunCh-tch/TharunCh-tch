<div align="center">

# Tharun Chatteti
### Software Engineer — AI/ML Systems & Backend

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tharun-chatteti)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://tharunch-tch.github.io/my-portfolio/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:tharun.chatteti@gmail.com)

</div>

MS in Computer Science (AI/ML) from SUNY Buffalo. I build retrieval and
evaluation systems for LLMs, and backend services that have run in
production at enterprise scale. Currently doing benchmark-task design
and reward-signal ranking for model training data at Handshake AI;
previously shipped 15+ REST APIs on a Java/Spring Boot migration at EY.

**Currently:** open to full-time Software Engineer / AI Engineer / ML
Engineer roles.

---

### Stack

`Python` `Java` `TypeScript` `SQL` `PHP`
`PyTorch` `LangChain` `Hugging Face` `FAISS` `YOLOv8` `MediaPipe` `scikit-learn`
`React` `FastAPI` `Spring Boot` `Kafka` `PostgreSQL` `Docker` `AWS`

### Projects

**[Enterprise Knowledge Assistant](https://github.com/TharunCh-tch/enterprise-knowledge-assistant)**
RAG pipeline over uploaded documents — chunking, FAISS vector search,
HuggingFace sentence-transformer embeddings, FastAPI serving layer.
Tested (pytest, incl. a real end-to-end retrieval test) with CI on
every push.
`Python` `LangChain` `FAISS` `sentence-transformers` `FastAPI`

**[LLM Eval Harness](https://github.com/TharunCh-tch/llm-eval-harness)**
Rubric + LLM-judge scoring, golden-patch/SWE-Bench-style comparison
with a sandboxed test runner, pairwise response ranking via a
from-scratch Bradley-Terry implementation, and inter-rater agreement
metrics (Cohen's kappa, Spearman). 84 tests, results reproduced from a
real run, committed in `results.md`.
`Python` `LLM Evaluation` `Bradley-Terry`

**[Smart Transportation AI](https://github.com/TharunCh-tch/smart-transportation-ai)**
NYC traffic simulation (A* routing, live map) plus a real computer-vision
module: YOLOv8 vehicle detection, OpenCV + EasyOCR plate reading, and a
from-scratch multi-object tracker. Measured precision/recall reported
honestly in `results.md`, including where the heuristics fall short.
`PyTorch` `YOLOv8` `OpenCV` `FastAPI`

**[AI Music Discovery Platform](https://github.com/TharunCh-tch/ai-music-discovery-platform)**
React/TypeScript SPA on a FastAPI backend — JWT auth, PostgreSQL,
mood-based semantic search (sentence-transformers), and both
content-based and collaborative (item-based + matrix factorization)
recommendation engines.
`React` `TypeScript` `FastAPI` `PostgreSQL` `JWT`

**[Order Fulfillment Service](https://github.com/TharunCh-tch/order-fulfillment-service)**
Spring Boot microservice — REST API, Kafka event producer/consumer,
PostgreSQL + Flyway migrations, Dockerized. JUnit 5 + Mockito +
MockMvc test suite.
`Java` `Spring Boot` `Kafka` `PostgreSQL` `Docker`

**[ASL Detection](https://github.com/TharunCh-tch/asl-detection)**
Real-time American Sign Language recognition — MediaPipe hand-landmark
extraction into a lightweight PyTorch MLP classifier. Trained on
10,873 real images; 91.8% test accuracy, measured and reproducible.
Flask API + Streamlit UI.
`PyTorch` `MediaPipe` `OpenCV` `Flask`

**[Community Cafe](https://github.com/TharunCh-tch/community-cafe)**
Neighborhood community platform — marketplace, cart/checkout, Razorpay
payments, visitor & amenity management. A solo modernized rebuild of a
3-person undergrad team project, with the original's SQL-injection and
weak-hashing issues fixed and regression-tested.
`PHP` `MySQL` `Razorpay` `PHPUnit`

### Experience

**AI/ML Software Engineer**, Handshake AI — *2026*
Benchmark task design and golden-patch authoring for SWE-Bench-style
training data; response ranking for reward-model signal.

**Associate Software Engineer**, EY — *2022–2023*
Cloud migration for a Fortune 500 client. 15+ REST APIs in Spring Boot
microservices, AWS CI/CD, Kafka/RabbitMQ, Snowflake/PostgreSQL tuning.

### Certifications
AWS Certified Solutions Architect – Associate · AWS Certified Developer
– Associate · AWS Certified AI Practitioner · AWS Certified Machine
Learning Engineer – Associate
