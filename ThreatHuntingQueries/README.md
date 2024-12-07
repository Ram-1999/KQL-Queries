# Threat Hunting Queries  

This folder contains KQL queries designed to assist in threat hunting and incident investigations. Each query focuses on identifying specific threat indicators in your environment.  

## Queries  

### 1. **File Hash Presence Query**  
- **Purpose**: Check if a specific file hash (SHA256) is present on devices in your environment.  
- **Usage**: Replace the placeholder file hash in the query with the SHA256 hash you want to search for.  
- **File**: [FileHashPresence.kql](./FileHashPresence.kql)  

### 2. **Inbound and Outbound Traffic Query**  
- **Purpose**: Investigate inbound and outbound network traffic for a specific IP address.  
- **Usage**: Replace the placeholder IP address in the query with the IP you want to analyze.  
- **File**: [InboundOutboundTraffic.kql](./InboundOutboundTraffic.kql) 