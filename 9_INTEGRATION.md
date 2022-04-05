# Overview

- **SQS:**
  - Queue services
  - Multiple produces, mesages kept for 2 weeks
  - Multiple Consumers -> Read and delete message when done
  - Use case -> Decouple apps
- **SNS:**
  - Notification service
  - Subscribers: Email, lambda, SQS, HTTP, Mobile
  - Multiple subscribers, message sent to all
  - No message retention
- **Kinesis:** Real time data streaming, persistence and analysis
- **Amazon MQ:** managed Apache MQ in cloud.