# go-rate-limiter

A high-performance, adaptive rate-limiting middleware for Go, built entirely from scratch without any external libraries. Supports token bucket and leaky bucket algorithms, real-time adaptive rate limits based on server load, and optional distributed rate-limiting logic. Perfect for microservices, distributed systems, and API traffic management.
Features
- Custom Rate-Limiting Algorithms: Choose between token bucket and leaky bucket algorithms.
- Concurrency-Safe: Built to handle concurrent requests efficiently with Go’s concurrency model.
- Adaptive Rate Limits: Adjusts rate limits in real-time based on server load (e.g., CPU usage, memory utilization).
- Distributed Support (Optional): Distributed rate-limiting across multiple instances without external dependencies.
- Metrics & Logging: Provides metrics for monitoring rate-limiting activity, violations, and load factors.
