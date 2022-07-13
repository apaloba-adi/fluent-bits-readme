# fluent-bits-readme

Theoretical paths to success:
1. Use tail input to keep track of updates to log file, output to Cloudwatch
2. Send logs via HTTP post requests, output to Cloudwatch

Current Red Flags/Hurdles
- Unclear documentation on location of configuration file, especially in Docker
- When using Docker container, cannot post to specified localhost port - 'Connection Refused'
- Cannot access filesystem in Docker in order to modify config file
- Cannot package alongside other software, only used as service
