# Cost Analysis (₹)

Cost estimates for **Global Edge CDN Platform** in **Indian Rupees (₹)**.

## Production Environment

| Service | Monthly Cost (₹) | Notes |
|---------|------------------|-------|
| **CloudFront** | ₹80,000–200,000 | Data transfer + requests |
| **Lambda@Edge** | ₹15,000–40,000 | Edge compute |
| **S3 Origin** | ₹10,000–25,000 | Origin storage |
| **WAF** | ₹20,000–40,000 | Security rules |
| **Shield Advanced** | ₹250,000 | DDoS protection (optional) |
| **Total** | **₹125,000–305,000** | ~$1,560–3,810/month |

## Data Transfer Pricing

| Region | Cost per GB (₹) |
|--------|-----------------|
| India | ₹7 |
| US/Europe | ₹6.5 |
| Asia Pacific | ₹10 |
| South America | ₹12 |

## Cost Optimization

- **Cache optimization** – Maximize cache hit ratio
- **Compression** – Enable Gzip/Brotli
- **Price class** – Limit to needed regions
- **Origin Shield** – Reduce origin requests
- **Reserved capacity** – For predictable traffic
