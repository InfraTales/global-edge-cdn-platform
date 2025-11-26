# Troubleshooting

## Common Issues

### Low Cache Hit Ratio
- Review cache key settings
- Check query string handling
- Verify TTL configuration
- Enable Origin Shield

### High Latency
- Check origin response time
- Verify edge location routing
- Review Lambda@Edge duration
- Enable compression

### 5xx Errors
- Check origin health
- Review Lambda@Edge errors
- Verify origin timeout settings
- Check origin capacity

### WAF Blocking Legitimate Traffic
- Review WAF logs
- Adjust rule sensitivity
- Add IP allowlists
- Create custom rules
