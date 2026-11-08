<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/spin-stack/brand/main/logos/mark-dark-256.png">
  <img src="https://raw.githubusercontent.com/spin-stack/brand/main/logos/mark-256.png" width="96" alt="Spinbox">
</picture>

# Spinbox

**Self-hosted sandboxes for AI agents and developers.** Each workspace is its own QEMU/KVM
virtual machine with root, a persistent disk and SSH: snapshots with memory, rollback, a diff of
what changed, and egress that is denied until a policy allows it.

> [!WARNING]
> Spinbox is experimental. APIs will break.

**Documentation:** <https://spin-stack.github.io/website/>

| Repository | What it is |
|---|---|
| [spin-terraform-aws](https://github.com/spin-stack/spin-terraform-aws) | A Spinbox installation on AWS, as one Terraform/OpenTofu module |
| [spin-machine](https://github.com/spin-stack/spin-machine) | The workspace VM: QEMU, guest kernel, base image and its machine definition |
| [vscode-spinbox](https://github.com/spin-stack/vscode-spinbox) | Spinbox for VS Code, VSCodium and Cursor: open your workspaces over Remote-SSH |
| [go-tools](https://github.com/spin-stack/go-tools) | Go CI checks for what a green build doesn't prove: mutation testing, tests that can't fail, and more |
| [devcontainer-cli](https://github.com/spin-stack/devcontainer-cli) | A standalone Go CLI for Dev Containers, with no Node.js |
| [brand](https://github.com/spin-stack/brand) | Spinbox's palette, type and mark as design tokens |
| [website](https://github.com/spin-stack/website) | The documentation site |
