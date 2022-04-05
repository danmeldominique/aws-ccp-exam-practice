# Overview

- **Route 53:** Global DNS. Route users to closest deployment with least latency. Good for disaster recovery strat.
- **Cloudfront:** CDN. Replicate parts of app in edge locations - closer to end user. Cache common requests
- **S3 Transfer Acceleration:** increase global dl and ul speeds into S3
- **Global Accelerator:** Improve global app availability and performance using global network.Requests routed through AWS internal network isntead of internet.
- **Outposts:** Deploy AWs racks into own data centers to extend AWS services
- **Wavelength:** AWS services to 5G network. Ultra low latency.
- **Local Zones:** Bring AWS resources closer to users. For latency sensitive apps.