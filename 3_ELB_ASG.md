# Summary

- **High av vs. Scalability:** Vertical (cpu + ram), horizontal (# of instances)
- **ELB:** 
  - Distribute traffic across backend instances, can be multi AZ
  - Supports health checks
  - Types:
    - ALB (HTTP - L7)
    - NLB (TCP - L4)
    - Classic (HTTP - L4 & L7)
- **ASG:**
    - Add elasticity to solution. Can be multi AZ
    - Scale # of instances to meet demand and replace unhealthy ones
    - Integrated with ELB
