# rust-workflows

This repository is used to run our Rust workflow for all Rust projects

WARNING: Any edits to this repository will affect ALL Rust projects

# Example

Very straight foward use example:

```yaml
name: Rust Syntax Check


on:
  pull_request:
    branches:
      "**"


jobs:
  task:
    uses: Mezzanotte-Labs/rust-workflows/.github/workflows/rust_check.yml@main
```
