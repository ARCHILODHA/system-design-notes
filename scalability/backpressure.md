# Backpressure

## Definition

Backpressure controls the rate of data flow between producers and consumers.

## Why Needed?

If producers generate data faster than consumers can process it, systems become overloaded.

## Solutions

- Buffering
- Rate limiting
- Queue management
- Dropping excess requests

## Benefits

- Prevents crashes
- Improves stability
- Better resource utilization

## Used In

- Apache Kafka
- Reactive Streams
- RabbitMQ
- Akka
