# Backend Architecture – PaySaveOnline

| Component | Purpose |
|------------|----------|
| **FastAPI Service** | Exposes endpoints `/rates`, `/rules`, `/feedback`. |
| **DynamoDB** | Stores FX and surcharge rules with timestamps. |
| **Lambda + API Gateway** | Serverless deployment for scalability. |
| **S3** | Hosts static JSON assets for offline fallback. |
| **Monitoring** | CloudWatch + Sentry for error tracking. |