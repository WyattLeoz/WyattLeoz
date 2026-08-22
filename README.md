# Loh Kai Zhe

**Backend / full-stack developer** — Information Systems @ Singapore Management University, Singapore.
Looking for a **2027 software engineering internship**.

Most of what I build is server-side: Spring Boot and NestJS APIs, relational schema and migrations,
and the Docker / Kubernetes / Terraform layer that puts them in front of users. I like the parts of a
system that have to keep working when nobody is watching — deploy pipelines, test coverage, and the
database.

Portfolio → **[kzdev-website.web.app](https://kzdev-website.web.app/)**

---

## Featured work

Some of these are team repositories owned by teammates, so they don't show up in the repository grid
on this profile. Commit counts below are mine.

### [The Six Seven](https://github.com/tiongg/csd) · Java · Spring Boot · PostgreSQL
Learning management system with contributor-authored courses, quizzes, and trend visualisation.
**95 commits** — I worked across the Spring Boot service layer and built the backend test suite:
JUnit coverage for the Course, Learner, Contributor, Admin, Tag, Notification, and Preference
services, wired up with JaCoCo reporting and a Dockerised test harness. Also rebuilt the admin
dashboard as a single-page KPI layout.

`Java 21` `Spring Boot` `Spring Security` `PostgreSQL` `Flyway` `Maven` `React 19` `JaCoCo`

### [OneTogether](https://github.com/nnylac/OneTogether) · NestJS · Terraform · Kubernetes
Centralised emergency and disaster response platform for Singapore, with separate public, responder,
and government roles over a shared incident timeline.
**52 commits** — mostly infrastructure and backend. I set up the AWS Terraform definitions (IAM,
security groups, CloudFront), the Kubernetes manifests for the backend, and three GitHub Actions
deploy pipelines. Also fixed production WebSocket transport and database SSL, wrote the prod seeding
workflow, and shipped the maps and AI advisory features.

`NestJS` `Prisma` `PostgreSQL` `Redis` `Socket.IO` `Terraform` `Kubernetes` `AWS` `GitHub Actions`

### [QuickAid](https://github.com/WyattLeoz/ShihTzu) · TypeScript · Express · PostgreSQL — *solo*
Emergency triage command platform: citizens report incidents, responders triage them with AI-ranked
response options, and a government portal broadcasts alerts. **Every commit is mine.**

Built around Postgres doing more of the work than usual — `LISTEN/NOTIFY` pushed straight out over
Server-Sent Events for live updates instead of polling, and `pg_trgm` for fuzzy incident search.
JWT auth with refresh tokens in httpOnly cookies, Zod validation at the boundary, Pino structured logs.

`TypeScript` `Express` `PostgreSQL` `SSE` `JWT` `Zod` `Pino` `React 18`

### [RunTogether](https://github.com/WyattLeoz/runtogether) · Vue 3 · Express · MongoDB
Full-stack group-run planner — create a session, get a route generated from your start point, and
find runs near you. **38 commits.** Consolidated from two separate repos into one monorepo with both
commit histories preserved.

`Vue 3` `Pinia` `Express 5` `MongoDB` `Mongoose` `Tailwind` `Google Routes API`

---

## Also

**Charm Companion** — InnovateFest 2026 (SMU, University Track), built for MINDS Employment &
Learning Pathways. A collectible phone charm with an SOS button, a Telegram companion bot, and a
staff dashboard, answering *"is my client safe at home tonight?"* from ordinary household signals —
the door lock, the kettle — rather than cameras. Solo build, Python. *Repo available on request.*

---

## Tools

**Backend** Java · Spring Boot · NestJS · Node.js · Express · Python
**Data** PostgreSQL · MongoDB · Prisma · JPA / Hibernate · Flyway · Redis
**Infrastructure** Docker · Kubernetes · Terraform · AWS · GitHub Actions
**Frontend** TypeScript · React · Vue 3 · Tailwind CSS
**Testing** JUnit · JaCoCo · Vitest

---

📍 Singapore · 📧 [wyattloh@gmail.com](mailto:wyattloh@gmail.com)
