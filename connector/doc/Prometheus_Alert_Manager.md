---
uid: Connector_help_Prometheus_Alert_Manager
---

# Prometheus Alert Manager

This connector can be used to collect all alerts from the Prometheus system.

## About

### Version Info

|Range  |Features  |Based on  |System Impact  |
|---------|---------|---------|---------|
|1.0.0.x [SLC Main]     |      |-         |-         |

### System Info

|Range  |DCF Integration  |Cassandra Compliant  |Linked Components  |Exported Components   |
|---------|---------|---------|---------|---------|
|1.0.0.x    |No       |Yes         |-         |   |

## Configuration

### Connections

#### HTTP Connection

This connector uses an HTTP connection and requires the following input during element creation:

HTTP CONNECTION:

  - **IP address/host**: [The polling IP or URL of the destination.]
  - **IP port**: [The IP port of the destination.]
  - **Device address**: [The bus address of the device. If the proxy server has to be bypassed, specify *BypassProxy*.]

## How to use

The **General** page displays configuration parameters: Username, etc.