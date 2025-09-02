# System Design Notes

Curated notes, diagrams, and code snippets to learn and revise System Design concepts. Where useful, small reference implementations and examples are included in Java and C++.

> This repository is evolving. If you spot gaps or want to add a topic/example, contributions are welcome—see “Contributing”.

## Why this repo

- Concise summaries for foundational system design topics
- Practical trade-offs and design checklists
- Small runnable examples (Java/C++) to reinforce concepts
- Interview-oriented references and mental models

## Topics you can expect
- Scalability, availability, and reliability fundamentals
- Caching, load balancing, partitioning/sharding, replication
- Consistency models, CAP theorem, consensus basics
- Storage systems: SQL vs NoSQL, indexing, queues, streams
- Rate limiting, pagination, id generation, search
- Observability: logging, metrics, tracing, SLOs/SLIs
- Security and privacy considerations, multi-tenancy
- API design (REST/gRPC), versioning, backward compatibility
- Back-of-the-envelope estimations and capacity planning

Note: The exact set of topics depends on what’s already in the repository. If something is missing, feel free to open an issue or PR.

## Repository structure (typical layout)
The structure may differ; use this as a guide when browsing:
- notes/ — Concept write-ups and diagrams
- java/ — Java examples or reference implementations
- cpp/ — C++ examples or reference implementations
- diagrams/ — Architecture diagrams and illustrations
- resources/ — External links, papers, and cheat sheets

If a folder is missing, it’s likely planned—PRs to add it are appreciated.

## Running examples

If the repository includes Java or C++ samples, you can usually run them like this:

### Java
```bash
# From the example directory containing .java files
javac Main.java
java Main
```

If there is a build tool (Maven/Gradle), follow the project’s README within that example directory.

### C++
```bash
# From the example directory containing .cpp files
g++ -std=c++17 -O2 -o app main.cpp
./app
```

## How to study with this repo

1. Start with fundamentals (scalability, availability, consistency).
2. Work through one topic at a time: read the note, then run the example.
3. Capture trade-offs and decision criteria in your own words.
4. Practice estimation problems; compare your approach to the checklists.
5. Revisit periodically and refine your mental models.

## Contributing

Contributions of any size are welcome!

- Fix typos/clarify explanations
- Add small runnable examples (prefer Java/C++)
- Add diagrams illustrating flows and failure modes
- Propose new topics or extend existing ones

Guidelines:
- Keep notes concise; link out for deep dives.
- Prefer self-contained examples with a short README inside the example folder.
- Include a brief “Why”/“Trade-offs” section for design write-ups.
- For code:
  - Java: Prefer Java 11+; include simple build/run instructions.
  - C++: Prefer C++17; compile with -O2 and document any dependencies.
- Add or update a table of contents if you create new sections.

Workflow:
1. Open an issue describing the change (optional but recommended).
2. Create a feature branch.
3. Submit a PR with a clear title and description.
4. Be open to feedback and iteration.

## Roadmap (suggested)
- [ ] Add core checklists (scalability, caching, data modeling)
- [ ] Include diagram set for common patterns (LB, shard, CQRS, event-driven)
- [ ] Add failure testing scenarios and mitigations
- [ ] Extend examples to include observability instrumentation
- [ ] Collect “Design a …” case studies with step-by-step reasoning

## Resources

- Designing Data-Intensive Applications (Kleppmann)
- The Architecture of Open Source Applications
- Google SRE Book(s) – SLI/SLO, error budgets
- Papers We Love and system design interview blogs

Consider adding links in resources/ to specific papers, talks, or blog posts as you go.

## Feedback

If something is confusing or missing, please open an issue with:
- What you were trying to learn/build
- Where the documentation/example fell short
- Any suggestions you have

---

⭐ If this repo helps you, please give it a star!
