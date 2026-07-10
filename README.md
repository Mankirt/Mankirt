# Mankirat Singh

Full stack software engineer with a focus on backend systems, cloud infrastructure, and AI-powered applications. I build production-grade software: distributed pipelines, real-time platforms, and developer tools, with an emphasis on architectural clarity and engineering discipline.

Most of what I build starts with a real problem: I got tired of tailoring my resume for every job application, so I built an AI that does it. I wanted to understand multi-agent AI systems deeply, so I built one from scratch on AWS without touching LangChain. That's the pattern.

---

## Projects

**[The Research Desk](https://github.com/Mankirt/ai-research-assistant)** — Distributed Multi-Agent Research Pipeline

Four specialized AI agents (researcher, fact-checker, writer, critic) orchestrated via AWS Step Functions. Built without LangChain or agent frameworks, so every layer of tool calling, state passing, and fault tolerance is explicit and understandable. Cache-aside pattern with DynamoDB cuts repeat query latency from ~35s to ~2s.

Live at [d3q01wfwtbi754.cloudfront.net](https://d3q01wfwtbi754.cloudfront.net)

`AWS Lambda` `Step Functions` `API Gateway` `Bedrock` `DynamoDB` `S3` `CloudFront` `Python` `React`


**[SmartApply](https://github.com/Mankirt/smartapply)** — AI Resume Fit Analyzer

RAG pipeline that scores resume-to-job-description fit, identifies gaps, and generates tailored bullet suggestions. Per-suggestion Accept/Edit/Ignore workflow with PDF export. Built on pgvector for semantic search and Claude API for reasoning.

`FastAPI` `React` `PostgreSQL` `pgvector` `Claude API` `Docker`


**[HireBoard](https://github.com/Mankirt/hireboard)** — Full Stack Job Board Platform

Employer and candidate dashboards with real-time notifications, Elasticsearch fuzzy search, Stripe billing, and JWT auth with refresh token rotation and reuse detection.

`Next.js` `Node.js` `PostgreSQL` `Redis` `Elasticsearch` `Kafka` `Socket.io` `Stripe` `Docker`


**[Miny](https://github.com/Mankirt/miny-url-shortener-redis/tree/main/miny-url-shortener)** — Scalable URL Shortener

Redis cache delivering ~0.1ms redirects. Async Kafka analytics pipeline. 56 billion+ possible short URLs via Base62 encoding.

`React` `Node.js` `PostgreSQL` `Redis` `Kafka` `Docker`

---

## Tech Stack

**Languages:** Python, JavaScript/TypeScript, Java

**Frontend:** React, Next.js, Vite, Tailwind CSS, Socket.io

**Backend:** Node.js, FastAPI, Kafka, PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, pgvector

**Cloud:** AWS (Lambda, Step Functions, API Gateway, Bedrock, DynamoDB, S3, CloudFront, IAM, CloudWatch), Docker

**Other:** Claude API, Tavily API, Playwright, Blue Prism RPA

---

## Experience

**Fortinet** — Intermediate Software Release Automation Engineer *(Jul 2023 – Present)*
Python · Playwright · FortiClient EMS · Enterprise security platform serving 30,000+ organizations · Promoted within 2.5 years

**Natural Resources Canada** — Software Developer Co-op *(May 2022 – Dec 2022)*
Python · Deep Learning · REST APIs · Earthquake monitoring system

**Tata Consultancy Services** — Systems Engineer *(Sep 2020 – Aug 2021)*
Blue Prism · RPA · Financial Workflow Automation · 2× On the Spot Award · Employee of the Month Award

---

## LeetCode

370+ problems solved — [mankirat26](https://leetcode.com/u/mankirat26/)

---

## Contact

[mankirat2601@gmail.com](mailto:mankirat2601@gmail.com) · [LinkedIn](https://linkedin.com/in/mankirat2601) · [LeetCode](https://leetcode.com/u/mankirat26/)
