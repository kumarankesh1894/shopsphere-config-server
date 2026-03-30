# ShopSphere Config Repository Structure

```text
config-repo/
  application.yml
  adminservice-dev.yml
  adminservice-qa.yml
  adminservice-prod.yml
  authservice-dev.yml
  authservice-qa.yml
  authservice-prod.yml
  catalogservice-dev.yml
  catalogservice-qa.yml
  catalogservice-prod.yml
  orderservice-dev.yml
  orderservice-qa.yml
  orderservice-prod.yml
  paymentservice-dev.yml
  paymentservice-qa.yml
  paymentservice-prod.yml
  api-gateway-dev.yml
  api-gateway-qa.yml
  api-gateway-prod.yml
  eurekaserver-dev.yml
  eurekaserver-qa.yml
  eurekaserver-prod.yml
```

Notes:
- Do not use `spring.config.activate.on-profile` in these files.
- Profile is selected by file naming (`<service>-<profile>.yml`).
- Keep secrets in environment variables where possible.

