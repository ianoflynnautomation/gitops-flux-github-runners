# Contributing

Thanks for your interest in contributing! This repo provisions resources with Terraform.

## Workflow
1. Fork the repo and create a feature branch.
2. Make changes under `kubernetes/`.
3. Update docs if interfaces change (variables/outputs/modules/README).
4. Open a Pull Request using the provided template.

## Style
- Prefer clear, explicit variable names and outputs.
- Pin provider and module versions.
- Keep modules cohesive and small.
- Avoid breaking changes; if unavoidable, call them out in the PR.

## Commit Messages
- Use meaningful messages; Conventional Commits are welcome (e.g., `feat: add log analytics`).

## Security
- Never commit secrets. Use Key Vault and Terraform variables securely.
