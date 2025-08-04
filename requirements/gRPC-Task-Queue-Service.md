# gRPC Task Queue Service

## Level 1 – Core
- As a client, I want to add a task to a queue — so workers can process them.
- As a client, I want to check the status of a task — so I know when it's completed.

## Level 2 – Streaming Updates
- As a client, I want to subscribe to task progress — so I get updates in real time.
- As a developer, I want to use protobuf to define types — so communication is strict and typed.

## Level 3 – Scaling: Authentication & Dead-letter Queue
- As a developer, I want to add API token auth to gRPC calls — so only valid clients can use the service.
- As a system, I want failed tasks to move to a dead-letter queue — so they don’t block the pipeline.
