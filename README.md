# Alexander LaPlante

AI/ML engineer in Sioux Falls, SD. Founder and sole engineer at Nxflo LLC, where I build and run an AI marketing platform for local service businesses end to end: data pipelines, model fine-tuning and serving, the ad-tech protocol services around them, and the AWS infrastructure underneath. M.S. in AI/ML in progress at CU Boulder. NVIDIA Inception member.

## Projects

| Repository | What it is |
| --- | --- |
| [nxflo-dsp](https://github.com/alaplante01/nxflo-dsp) | Real-time bidder for OpenRTB 2.5: Rust (Axum/Tokio) gateway with a C++ pricing engine over FFI, Terraform for ECS Fargate, Aurora PostgreSQL and a Kinesis Firehose event pipeline |
| [nxflo-buyer](https://github.com/alaplante01/nxflo-buyer) | Ad Context Protocol (AdCP 3.2.1) buying agent in Python/FastAPI: seller discovery over MCP, signed requests (RFC 9421), idempotent media buys with circuit breakers and a retry budget |
| [nxflo-seller](https://github.com/alaplante01/nxflo-seller) | AdCP sales agent with an ADFX adapter, built on the Prebid sales agent |
| [kalshi-btc-markets](https://github.com/alaplante01/kalshi-btc-markets) | Collector, backfill, pricing model and terminal client for Kalshi's hourly Bitcoin markets |

The Nxflo platform itself (TypeScript/Bun daemon, MCP server and React SPA on Cloud Run, plus per-client lead-capture stacks on AWS Lambda, DynamoDB and CloudFront) is private.

## Stack

Python, TypeScript, Rust, SQL · PyTorch, llama.cpp, LoRA fine-tuning, Claude and OpenAI APIs, MCP · PostgreSQL, DynamoDB · AWS (ECS Fargate, Lambda, Aurora, Route 53, CloudFront), GCP Cloud Run, Terraform, GitHub Actions

## Contact

alexlaplante04@gmail.com · [LinkedIn](https://www.linkedin.com/in/alaplante01/)
