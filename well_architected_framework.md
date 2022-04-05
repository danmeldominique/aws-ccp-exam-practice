# Well architected Framework

## Operational Excellence
To run and monitor systems -> Improve processes/ procedures -> Deliver business value.

### Principles
1. **Perform ops as code :** Infra as code (CloudFormation)
2. **Annotate documentation:** Auto docs after every build
3. **Frequent, small, reversible changes:** Easy to roll back
4. **Refine procedures regularly:** Become more efficient
5. **Anticipate failure**
6. **Learn from failure**

## Security
Ability to protect info, systems and assets whilst delivering business value through risk assessment and mitigation strategies

1.  **Strong identity foundation:** Centralize privilege mgmt and reduce reliance on long-term creds. Principle of least privilege.
2.  **Enable traceability:** Integrate logs/mertrics with systems to auto respond and take better action
3.  **Security at all layers:** Edge network, vpc, subnet, LB, Compute, OS, app
4.  **Automate security best practices**
5.  **Protect data:** In transit and at rest
6.  **Keep people away from data:** Reduce/ eliminate need for direct access/manual rpcessing of data
7.  **Prepare for security events:** Run incident response simulation and use tools to speed up detection, investigation and recovery


## Reliability
 System to recover from disruptions, dynamically acquire resources to meet demand and mitigate disruptions.

 1. **Test recovery procedures:** Automation to simulate failures
 2. **Auto recover from failure:** Anticipate and fix issues before they occur
 3. **Scale horizontally to increase aggregate system availability:** Distribute requests across amany resources so no common point of failure
 4. **Stop guessing capacity:** Maintain the optimal level to satisfy demand without over/under provisioning.
 5. **Manage change in automation:** Use automation to make changes to infrastructure
 
 ## Performance efficiency

 Ability to use computing resources efficiently to meet requirements and maintain it when demands change and tech evolves

 1. **Democratize advanced technologies:** Advance tech becomes services so user can focus on product development
 2. **Go global in minutes**: Deployment in minutes
 3. **Use serverless architectures:**Avoid burden of managing servers
 4. **Experiment more often:** Carry out comparative testing
 5. **Mechanical Sympathy:** Aware of all AWS services

## Cost Optimization

Ability to run system to deliver business value at lowest cost possible

1. **Adopt a consumption model:** PAYG
2. **Measure overall efficiency:** Use cloudwatch
3. **Stop spending money on data center operations:** AWS handles infrastructure, customer focus on projects
4. **Analyze expenditure:** Use tags to help identify system usage and costs. Helps measure ROI.
5. **Use managed/applicaiton level services tor educe TCO:**As services operate at cloud scale, they can offer lower cost per transaction/service.