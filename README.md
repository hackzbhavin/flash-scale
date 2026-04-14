# flash-scale
A system that can handle thousands of simultaneous users trying to buy a limited stock of items (e.g., concert tickets or sneaker drops) without overselling.

### High-Concurrency "Flash Sale" Inventory System
**The Goal:** Build a system that can handle thousands of simultaneous users trying to buy a limited stock of items (e.g., concert tickets or sneaker drops) without overselling.
**Why it skills you up:** It forces you to deal with race conditions, distributed locking, and caching strategies—highly sought-after skills for senior roles. [cite_start]It builds directly on your experience with performance optimization and databases[cite: 14, 22].
* **Frontend:** Next.js (React) for a fast, responsive UI[cite: 19].
* **Backend:** NestJS Microservices[cite: 20, 23].
* **Database/Cache:** MySQL for ACID compliance and Redis for distributed locking to prevent double-booking[cite: 22].
* **The Challenge:** Implement a queuing mechanism using Redis or AWS SQS [cite: 21] so that when 10,000 requests hit the server for 100 tickets, the system processes them reliably without crashing or selling 101 tickets.
