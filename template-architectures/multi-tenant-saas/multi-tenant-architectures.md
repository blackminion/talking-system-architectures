## Multi-Tenant architectures

## Concepts
- A _single-tenant architecture_ is a single architecture per organization where the application has its own infrastructure, hardware, and software ecosystem. More costs, more maintenance, difficulty of updating across environments.

- In _multi-tenant architecture_ a single environment can serve mutiple tenants utilizing a scalable, available, and resilient architecture. The underlying infrastructure is ocmpletely shared, logically isolated, and with fully crentalized services.

## Multi-tenant benefits
- Server cost reduction
- One single source of trust
- Cost reductions of development and time-to-market


## Tips
- If you are projecting a high-traffic for your SaaS application, you'd better architect your database with MongoDB.
- All static content, including images, media and HTML, should be hosted on Amazon S3. In front of Amazon S3, you can integrate AWS CloudFront, in order to cache the entire static content and reduce bandwidth consts.
- 


## References
- [Multi tenant architecture](https://www.clickittech.com/saas/multi-tenant-architecture/)
