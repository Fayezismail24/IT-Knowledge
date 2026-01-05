
```markdown
# Network Measurements

Network measurements refer to the assessment of various parameters related to the performance, health, and efficiency of a network. These measurements are critical for monitoring and optimizing network performance.

## 1. Bandwidth
- **Definition**: The maximum data transfer rate of a network.
- **Measurement**: Typically measured in bits per second (bps).
- **Purpose**: Indicates how much data can be transmitted over a network in a given period.

### Speed Standards
- **10 Mbps** (10 Megabits per second) – This is the speed for **10BASE-T Ethernet**, the slowest standard.
- **100 Mbps** (100 Megabits per second) – This is the speed for **100BASE-T Ethernet**, also known as **Fast Ethernet**.
- **1000 Mbps** (1000 Megabits per second) – This is the speed for **1000BASE-T Ethernet**, also known as **Gigabit Ethernet**. This is the most common speed for modern Ethernet connections.

## 2. Latency
- **Definition**: The delay before a transfer of data begins after an instruction.
- **Measurement**: Measured in milliseconds (ms).
- **Purpose**: Impacts the speed of data transmission and responsiveness.

## 3. Packet Loss
- **Definition**: The percentage of packets that fail to reach their destination.
- **Cause**: Often caused by network congestion, errors, or hardware failure.
- **Purpose**: Indicates the reliability and stability of the network.

## 4. Jitter
- **Definition**: The variation in time delay between packets arriving at their destination.
- **Cause**: Network congestion, routing issues, or interference.
- **Purpose**: High jitter can affect real-time communications (e.g., VoIP, video conferencing).

## 5. Throughput
- **Definition**: The actual rate at which data is successfully transmitted over the network.
- **Measurement**: Measured in bits per second (bps).
- **Purpose**: Can be impacted by network congestion or errors, often lower than bandwidth.

## 6. Network Utilization
- **Definition**: The percentage of available bandwidth being used.
- **Purpose**: High utilization could indicate congestion, while low utilization may suggest underuse.

## 7. Error Rate
- **Definition**: The frequency at which errors occur in the transmission of packets.
- **Cause**: Network noise, interference, or signal degradation.
- **Purpose**: Helps in identifying transmission issues and network health.

## 8. Round-Trip Time (RTT)
- **Definition**: The time it takes for a signal to travel from the source to the destination and back.
- **Measurement**: Measured in milliseconds (ms).
- **Purpose**: Commonly used in protocols like `ping` to measure network performance.

## 9. Connection Establishment Time
- **Definition**: The time taken to establish a connection between two devices on the network.
- **Purpose**: Measures the responsiveness of network connections.

## 10. Goodput
- **Definition**: The amount of useful data transmitted over the network, excluding overhead (like headers and retransmitted packets).
- **Measurement**: Measured in bits per second (bps).
- **Purpose**: Goodput represents the real rate of successful data delivery and is a more accurate reflection of actual network performance than throughput, as it excludes overhead and retransmissions.

## Tools for Network Measurements
- **Wireshark**
- **Ping**
- **Traceroute**
- **NetFlow**

Monitoring and analyzing these measurements help in troubleshooting and maintaining optimal network performance.
```

This update includes the **10/100/1000 Mbps** network speeds and their corresponding **Ethernet standards** under the **Bandwidth** section, as part of the network measurements.
