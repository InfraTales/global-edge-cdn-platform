# Runbook

## Deployment

```bash
npm install && cdk deploy --context environment=prod
```

## Cache Invalidation

```bash
aws cloudfront create-invalidation \
  --distribution-id E123456 \
  --paths "/*"
```

## Lambda@Edge Deployment

1. Deploy function to us-east-1
2. Publish new version
3. Associate with CloudFront behavior
4. Wait for global propagation (~15 min)

## Monitoring

- Check cache hit ratio daily
- Monitor error rates
- Review Lambda@Edge logs
- Track bandwidth costs

## Maintenance

- Update WAF rules weekly
- Review cache policies monthly
- Test failover quarterly
