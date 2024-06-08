# Kafka Cab Booking System

## Overview
This project demonstrates a cab booking system using Apache Kafka. The system simulates the location of cab drivers and includes a producer for user booking requests and a consumer for processing these requests.

## Prerequisites
- Java 11 or higher
- Apache Kafka 2.8.0 or higher
- Apache Zookeeper 3.6.3 or higher

## Setup

### Step 1: Install Kafka and Zookeeper
1. Download Kafka from [Apache Kafka Downloads](https://kafka.apache.org/downloads).
2. Extract the downloaded files to your desired location.
3. Configure `server.properties` and `zookeeper.properties` files as needed.

### Step 2: Start Zookeeper and Kafka
```bash
# Start Zookeeper
bin/zookeeper-server-start.sh config/zookeeper.properties

# Start Kafka
bin/kafka-server-start.sh config/server.properties
