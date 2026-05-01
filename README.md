# ddos-research

DDoS attack research and traffic analysis tool.

## Features
- Traffic pattern analysis
- Attack vector detection
- Packet flood simulation
- Bandwidth stress testing
- Real-time monitoring

## Usage
```bash
ruby research.rb --mode analyze --target <ip>
```

## Examples
```bash
# Traffic analysis
ruby research.rb --mode analyze --target 192.168.1.1

# Stress test
ruby research.rb --mode stress --target 192.168.1.1 --duration 60
```

## Requirements
- Ruby 2.7+
- pcaprub
- packetfu

## Disclaimer
For authorized research and educational purposes only.
