# Architecture

## Overview

BuildGuard follows a microservices architecture with the following components:

- **Platform API** — Central API gateway
- **User Service** — Authentication and user management
- **Payment Service** — Billing and payment processing
- **Order Service** — Order lifecycle management
- **Notification Service** — Multi-channel notifications

## Infrastructure

- AWS EKS for container orchestration
- PostgreSQL for primary data storage
- Redis for caching and sessions
- Apache Kafka for event streaming
