# System_Design
# System Design — [System Name]

## Overview
One or two lines describing the purpose of the system.

---

## Requirements
- **Functional:** [e.g., create short URL, redirect to original]
- **Non-functional:** [e.g., low latency, high availability]

---

## Estimations
- Expected users: [...]
- Requests per second: [...]
- Storage needs: [...]

---

## Data Model
ER diagram / schema: `./diagrams/data-model.png`

---

## API Design (Examples)
- `POST /shorten` — body: `{ "long_url": "..." }` → response: `{ "short_url": "..." }`
- `GET /:shortId` — redirect to original URL

---

## High-level Architecture
Diagram: `./diagrams/high-level-arch.png`

---

## Deep Dives
- [Short URL Generation](./deep-dives/short-url-generation.md)
- [Scalability & Caching](./deep-dives/scalability.md)

---

## Implementation Notes
- Tech choices: [language, DB, cache]
- Trade-offs or limitations: [list briefly]

---
