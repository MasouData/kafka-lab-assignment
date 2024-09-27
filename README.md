<<<<<<< HEAD
# kafka-lab-assignment
to show show how distributed systems communicate with one another through publish/subscribe communication protocols, specifically use Kafka, which is a common message broker
=======
# Kafka Lab Assignment

## Overview

This project demonstrates how distributed systems communicate using Kafka's publish/subscribe model. It includes:

- Multiple Kafka producers running concurrently.
- A consumer that deserializes and processes messages in Avro format.

## Directory Structure

- `schemas/` - Avro schema files.
- `Dockerfile` - Docker configuration for the deserializer.
- `deserializer.py` - Consumer script.
- `run-deserializer.sh` - Script to run the consumer.
- `start-producers.sh` - Script to start multiple producers.
- `start-producer.sh` - Original producer script.
- `auth/` - Authentication credentials (excluded from repository).

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/kafka-lab-assignment.git
   cd kafka-lab-assignment
>>>>>>> bc851df (Add README.md file)
