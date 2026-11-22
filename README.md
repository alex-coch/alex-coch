# Aleksei Kokorev

I’m a Python backend engineer with 8+ years of experience building APIs and event-driven services. My recent work focuses on search, reading activity, and audiobook processing for a digital reading platform.

[Portfolio](https://alex-coch.github.io/) · [Resume](https://alex-coch.github.io/resume/) · [Outbox demo](https://github.com/alex-coch/document-events-outbox#quick-start) · [LinkedIn](https://www.linkedin.com/in/alexcoch/)

- Built FastAPI services for catalog and search, implemented Kafka producers and consumers, and used ClickHouse to analyze reading and listening activity.
- Built a Python pipeline that matches audiobook narration to the written text and deployed the GPU service that runs the model in production.
- Developed asynchronous APIs for a blockchain compliance platform and integrated external analytics providers to support transaction monitoring and case management.
- Built document workflows using event sourcing and CQRS. I implemented a transactional outbox to publish events to RabbitMQ and made consumers idempotent so retries could run safely.

## Selected case studies

- [Matching audiobook narration to text](https://alex-coch.github.io/projects/audiobook-alignment/) — How a Python pipeline turns speech model scores into timestamps for ebook passages. · [View audio example](https://alex-coch.github.io/projects/audiobook-alignment/#alignment-example)
- [Reliable event delivery for document workflows](https://alex-coch.github.io/projects/transactional-outbox/) — How a transactional outbox and idempotent consumers handle broker outages and duplicate deliveries. · [View failure test results](https://alex-coch.github.io/projects/transactional-outbox/#failure-test-results) · [Run the demo](https://github.com/alex-coch/document-events-outbox#quick-start)
  [![Docker Compose](https://github.com/alex-coch/document-events-outbox/actions/workflows/compose-ci.yml/badge.svg?branch=main)](https://github.com/alex-coch/document-events-outbox/actions/workflows/compose-ci.yml) [![Kubernetes (kind)](https://github.com/alex-coch/document-events-outbox/actions/workflows/kind-ci.yml/badge.svg?branch=main)](https://github.com/alex-coch/document-events-outbox/actions/workflows/kind-ci.yml)
- [What’s new in this article?](https://alex-coch.github.io/projects/article-comparison/) — How a Chrome extension retrieves passages from earlier reading to show what a new article adds. · [View example comparison](https://alex-coch.github.io/projects/article-comparison/#example-comparison)
