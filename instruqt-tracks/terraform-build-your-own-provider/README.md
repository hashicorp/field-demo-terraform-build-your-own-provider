# terraform-build-your-own-provider

## Build the Image

Using `instruqt-packer/hashistack-go-development`.

```bash
make \
    PROJECT=instruqt-hashicorp \
    STACK_VERSION=0.9.1 \
    CONSUL_VERSION=1.9.5 \
    NOMAD_VERSION=1.0.4 \
    TERRAFORM_VERSION=0.15.3 \
    VAULT_VERSION=1.7.1 \
    DOCKER_COMPOSE_VERSION=1.29.1 \
    GO_VERSION=1.16.3 \
    build
```

### Challenge Work

- Implement Import
    -[x] Setup
    -[ ] Check
    -[ ] Solve
    -[?] Cleanup
