# CloudDesk SaaS Architecture

## Overview

CloudDesk SaaS is a fictional cloud-based SaaS application used to simulate technical support and application support investigations.

The architecture represents a typical SaaS support environment where customers interact with a web application, authentication services, APIs, and backend services.

## Architecture Flow

```mermaid
flowchart TD
    A[Customer] --> B[Web Browser]
    B --> C[SaaS Web Application]

    C --> D[Authentication Service]
    C --> E[API Gateway]

    E --> F[Application Services]
    F --> G[Database]
    F --> H[Report Service]
    F --> I[Upload Service]

    D --> J[Authentication Logs]
    C --> K[Application Logs]
    E --> L[API Logs]

    H --> K
    I --> K