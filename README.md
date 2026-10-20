<img src="assets/header.svg" alt="Tint Aung Khant: Senior Backend Engineer and AI-First Software Engineer" width="100%">

I design backend systems, build AI-powered products, and turn business problems into software that ships. AI helps me move faster; engineering judgment decides what stays.

8+ years writing software. Founder of Better Solutions.

> **No unnecessary code. No unnecessary complexity. Just systems that work.**

## How I work

- **Business first.** I ask questions and agree on the solution with stakeholders before I write code.
- **Simplicity over abstraction.** YAGNI, until real evidence says otherwise.
- **Code enforces invariants; LLMs interpret intent.** Business rules never live in a prompt.
- **Measure, then decide.** If an approach fails real use cases, I replace it.

## AI-first, human-reviewed

Claude Code is part of my daily workflow. Specs become sequential tickets with one branch and PR each. Work runs test-first, failures get replay scripts, and any model-visible change needs eval results and a cost review. I review and merge every PR myself.

One example: I replayed failed chats against a multi-stage router/specialist/composer pipeline and a single tool-calling agent. The single agent did better, so I dropped the pipeline.

## Stack

**Core** &nbsp; PHP · Laravel · TypeScript · Node.js · PostgreSQL · MySQL · Redis · LLM agents & evals<br>
**Also** &nbsp; Go · Python · Fastify · NestJS · Next.js · Nuxt.js · Docker · AWS

## Selected work

**[Laravel HTTP Beacon](https://github.com/tintaungkhant/laravel-http-beacon)** &nbsp;`public` `Laravel`<br>
HTTP observability for Laravel. I built it after spending too long digging through Telescope for one specific failed request. It logs incoming and outgoing traffic with related queries, model changes and jobs, and you can filter by route, method, status and date. Storage is indexed, with retention pruning and row caps. Used in a few company projects.

**[tasky](https://github.com/tintaungkhant/tasky)** &nbsp;`public` `Go`<br>
Git worktrees organized by ticket, across repositories. It creates task-scoped folders, applies branch-naming templates, generates VS Code multi-root workspaces and cleans up afterwards. Starting a ticket shouldn't come with bookkeeping.

**Zay Thal Gyi Copilot** &nbsp;`private` `in development`<br>
A tool-calling commerce assistant. The model interprets what customers ask for. Deterministic code validates details, calculations, confirmations and state transitions. State lives outside the agent service (Next.js CMS, Fastify, Trigger.dev), and automated multi-turn evaluations guide design choices. It has no live customers yet.

**Zay Thal Gyi POS** &nbsp;`private` `prelaunch`<br>
A Myanmar-language-first retail POS. It covers inventory, purchase orders and multi-store operations, plus split tender with MMK and local payment methods. Cash drawer shifts use a blind close, and stock and money changes go into append-only audit records. Reports, permissions and multitenancy come next.

## Along the way

At 19, about a year into programming, I inherited a Japanese influencer platform when its senior developer left and the promised replacement never arrived. I rebuilt the backend, database, APIs and web app (the mobile apps were handled by others). I learned Vue 2 on the job and got Stripe and Japanese GMO payments working despite the language barrier.

Since then I've worked on crypto payments, car auctions, fleet tracking and school meal systems. I've also owned company products end to end, from engineering and design to customer support.

Outside work: games, learning, and mathematics.

## Let's talk

I'm open to employment, consulting and startup partnerships. GitHub is the best place to find me.

<sub>I like my systems reliable and my abstractions justified.</sub>
