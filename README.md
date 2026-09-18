<div align="center">

# Michael Mayaguari

**Full-stack engineer building AI systems that have to work with real data and real stakes.**

[![Gmail](https://img.shields.io/badge/-gmail-ec493c?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:mayaguarimichael@gmail.com)&nbsp;
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michaelmayaguari/)&nbsp;
[![Portfolio](https://img.shields.io/badge/portfolio-%23000000.svg?&style=for-the-badge&logo=globe&logoColor=white)](https://mgmayaguari.github.io/)&nbsp;

</div>

<br>

## Who I am

I like being the person who sits with a messy, real-world system - a brokerage account with no public API, a knowledge base that has to keep an AI agent honest, a client who needs something live by Friday - and gets it working. My strongest projects aren't tutorials; they involve real accounts, real users, and real constraints I didn't get to design away.

I care about finance, travel, and design specifically, which is why my two current flagship projects are a multi-account portfolio intelligence platform built on my own family's brokerage accounts, and an AI travel planner grounded in a real guidance corpus rather than a model's guesses. Both are built the same way: deterministic code owns the numbers, the model owns judgment calls, and every output is checked before a person sees it.

## What I'm building now

- **[portfolio-copilot](#)** - Brokerage OAuth integration (SnapTrade), a transaction-ledger schema with lot-level cost basis, and an LLM agent that answers questions by calling typed tools instead of doing arithmetic. Eval suite with a dedicated refusal set for anything that would constitute investment advice, running in CI. *(in progress)*
- **[applied-ai-system-project](https://github.com/mgmayaguari/applied-ai-system-project)** - A retrieval-grounded planning agent: BM25 search over a knowledge base, a bounded plan → act → check → repair loop, and a guardrails layer with named validators for citation grounding, category coverage, and time conflicts. Being ported from its pet-care original into an AI travel planner. *(in progress)*

## Skills

**Languages** - Python, TypeScript/JavaScript, Swift, SQL

**AI & agentic systems** - Tool-calling agents, retrieval-augmented generation (BM25-based), guardrail/validation design, eval harness construction (golden sets, CI-integrated scoring), prompt iteration against measured results. Built through hands-on coursework in CodePath's AI Engineering track and applied independently in production-shaped side projects.

**Backend & data** - FastAPI, SQLAlchemy/Pydantic, Postgres, transaction-ledger and lot-based financial data modeling, Selenium-based integration with systems that have no public API

**Frontend & mobile** - React, Next.js, SwiftUI/UIKit (iOS)

**Cloud & infrastructure** - AWS (RDS, ECS/Fargate, S3, CloudFront, Route 53, IAM) - currently studying for the **AWS Certified Solutions Architect – Associate**, applying each service to the platform above as I learn it rather than studying in the abstract

**Other** - Solidity/smart contracts (deployed and tested a coin-flip Dapp end to end), Git/GitHub Actions CI, Figma

## Currently learning

Working toward the AWS Solutions Architect Associate certification, with the portfolio-copilot deployment as the applied half of that study - each service above got used on a real system, not just a practice exam.
