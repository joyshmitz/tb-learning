---
layout: docwithnav
title: MQTT Broker Performance Test - 100M Connections
description: ThingsBoard MQTT Broker Performance Test with 100M Connections
---

# MQTT Broker Performance Test - 100M Connections

This document describes the performance test setup and results for ThingsBoard MQTT Broker with 100 million concurrent connections.

## Test Setup

- **Hardware**: AWS EC2 instances
- **Network**: AWS VPC
- **Client Simulator**: Custom MQTT client simulator
- **Monitoring**: Prometheus + Grafana

## Test Results

- Successfully established 100M concurrent MQTT connections
- Average connection time: < 100ms
- Memory usage per connection: ~20KB
- CPU usage: 60-70% under load

## Conclusion

ThingsBoard MQTT Broker successfully demonstrated its ability to handle 100 million concurrent connections while maintaining stable performance and resource usage.
