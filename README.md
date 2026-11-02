# Jakub Werner

I build internal developer platforms and agentic developer tooling.

In my day job I designed the self-service layer of an internal Kubernetes and AWS platform that more than 2,000 developers use. Product teams onboard themselves through a validated pull request that merges itself, which cut onboarding from over a week to a day. I also built and shipped a RAG documentation chatbot on AWS Bedrock by myself in 11 weeks. That code is not public, and my personal projects are private for now, so this page lists what I work on and my merged upstream contributions.

**Currently:** personal multi-agent systems in Pydantic AI with MCP server integration, an LLM eval that replays the prompt of a real workflow run against up to 9 models and checks every answer against fixed rules, and a homelab k3s cluster with OpenTelemetry tracing, Jaeger and Prometheus.

**Stack:** Python · TypeScript/Node.js · AWS (EKS, Bedrock, Lambda, Step Functions, DynamoDB) · Terraform/Terragrunt · Kubernetes · Helm

## Merged upstream fixes and features

- [langchain-ai/langchain#25658](https://github.com/langchain-ai/langchain/pull/25658): configurable history key for the DynamoDB chat message history (2024)
- [pascalgn/automerge-action#238](https://github.com/pascalgn/automerge-action/pull/238): read the GitHub host from `GITHUB_SERVER_URL` instead of hard-coding github.com (2024)
- [terraform-aws-modules/terraform-aws-appsync#18](https://github.com/terraform-aws-modules/terraform-aws-appsync/pull/18): IAM permission boundary for the roles the module creates (2021)

[LinkedIn](https://www.linkedin.com/in/jakubikan)
