# Database Replication

## Definition

Replication means copying data from one database server to another.

## Purpose

- High Availability
- Fault Tolerance
- Read Scalability

## Architecture

        Master
           |
    ----------------
    |              |
 Replica1      Replica2

## Types

### Synchronous
Data is written to replicas immediately.

### Asynchronous
Data reaches replicas after a delay.

## Advantages

- Faster Reads
- Backup Support
- Disaster Recovery
