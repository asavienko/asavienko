# Anton Savienko · Senior full-stack engineer

I build web products end to end: the React/Next.js front end, the Node.js/NestJS API, the PostgreSQL schema, and the AWS and Terraform setup underneath. Ten years of it, fully remote since 2021. Lately most of my work touches LLMs, mainly voice agents and Claude API pipelines that have to survive production.

Before switching to code in 2016 I ran a sales department for five years. It still shows: my current side project is an agent that makes cold calls.

**Open to senior full-stack and AI engineering roles.** Remote, based in the EU. US and Canadian companies via B2B contract.
[LinkedIn](https://www.linkedin.com/in/asavienko) · [asavienko@gmail.com](mailto:asavienko@gmail.com)

## Selected work

**[Loro](https://github.com/asavienko/loro)** is a language-learning app for iOS, Android and the web ([try it](https://main.d8avifn92wmt4.amplifyapp.com/)).
You hear a phrase, say it in the pause, rate yourself, and FSRS spaced repetition (in a shared Rust core) decides when you see it again. Expo/React Native client, offline-first with sync, NestJS + PostgreSQL API on AWS EC2. Phrase sets and audio are generated with the Claude API and ElevenLabs. pnpm + Turborepo monorepo.

**[Outbound voice agent](https://github.com/asavienko/outbound-agent)** calls businesses over Twilio, tells them up front it's an AI, handles objections and books demos. ElevenLabs runs the voice, Claude Haiku the conversation.
A TypeScript/Hono server handles tool calls and HMAC-signed webhooks, with SQLite for state. The dialer respects local calling hours, a do-not-call list and retry backoff. Secrets live in SOPS + age, and the agent config is code with simulation tests.

**Runtime Verification**, full-stack engineer, 2022 to 2026. I reported to the CEO and CTO.
- Designed and built, alone, a SaaS platform that runs formal verification, symbolic execution and fuzzing jobs on five dedicated high-performance machines (Next.js, NestJS, PostgreSQL, AWS). A job can run for days and still resume from where it failed.
- Hooked the Claude API into CI. Triaging a failed test run went from hours to minutes.
- Moved legacy infrastructure to Terraform.

Earlier: technical lead at Rentbetta (New York), and full-stack and front-end roles in Ukraine from 2016.

## Stack

- Languages: TypeScript, JavaScript, Python, SQL
- Front end: React, Next.js, React Native / Expo, Redux, TanStack Query, Tailwind CSS, shadcn/ui, Storybook
- Back end: Node.js, NestJS, Express, Hono, REST, GraphQL, WebSockets
- Data: PostgreSQL, MongoDB, DynamoDB, Redis, pgvector, Prisma, TypeORM
- Cloud and DevOps: AWS (ECS, Lambda, RDS, S3, SQS, CloudFront, Cognito), Terraform, AWS CDK, Docker, Kubernetes, GitHub Actions, GitLab CI
- AI / LLM: Claude API, OpenAI API, LangChain, LangGraph, MCP servers, RAG, ElevenLabs, Twilio
