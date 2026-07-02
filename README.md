# Aaron Joseph George

Backend engineer with 4 years of experience building production REST APIs and real-time systems with Node.js, TypeScript and PostgreSQL. Currently a senior engineer at a venture studio, where I own backend architecture across multiple live products.

**London, UK. Graduate visa with full right to work. No sponsorship required.**

## Selected work

**[booking-concurrency-lab](https://github.com/ajgeorge/booking-concurrency-lab)**
A reservation service that survives concurrent booking attempts on the same slot without a single double-booking. Pessimistic locking with FOR UPDATE, idempotency keys and retry handling in PostgreSQL, verified with a k6 load test firing 500 concurrent requests. Results and design tradeoffs in the README.

**[realtime-tracking-demo](https://github.com/ajgeorge/realtime-tracking-demo)**
Live location tracking across horizontally scaled servers. WebSockets with heartbeat ping/pong, Redis pub/sub for cross-server broadcast, and a docker-compose setup that runs two API instances behind a proxy to prove messages reach clients on any node. One command to run.

**[ai-ops-studio](https://github.com/ajgeorge/ai-ops-studio)**
A production-inspired platform for AI-powered internal operations tools. TypeScript monorepo combining a requirements assistant, an operations recommendation workflow with human-in-the-loop approval, a RAG evaluation lab with cited answers, and an AI governance console with audit trails.

**[AI-gitscorer](https://github.com/ajgeorge/AI-gitscorer)**
A tool that analyses GitHub repositories and scores engineering quality signals. Node.js API with an LLM analysis pipeline and a web interface.

## Production systems I've built

Most of my day-to-day work ships in private client repositories, so here is the short version of each.

- **Sanad RSA**: central REST API for a real-time roadside assistance platform. Service request lifecycles, job assignment and live status updates over WebSockets, with Redis pub/sub broadcasting across servers.
- **CarFlow**: booking and inventory platform on Node.js, PostgreSQL and Azure. Concurrent reservation workflows with strict consistency guarantees, pessimistic locking and idempotency keys to prevent double-booking under load.
- **Q-Auto**: vehicle servicing platform on AWS supporting a digitised 500-point inspection process, live status tracking and automated PDF report generation with embedded media.
- **Agricope**: e-commerce backend taken from concept to production launch in six months. Node.js, TypeScript, MongoDB, Docker and GitHub Actions CI/CD.

Happy to walk through the architecture of any of these in detail.

## How I work

TDD with Jest, structured code review, Docker for everything, and CI/CD through GitHub Actions on every project I touch. I care about data consistency, clear ownership boundaries and systems that stay maintainable after I hand them over.

**Stack**: Node.js, Express, TypeScript, PostgreSQL, Redis, MongoDB, Docker, GitHub Actions, Azure, AWS. React on the frontend when needed.

## Contact

- Email: aaronjosgeorge@gmail.com
- LinkedIn: [linkedin.com/in/ajosgeorge](https://linkedin.com/in/ajosgeorge)
