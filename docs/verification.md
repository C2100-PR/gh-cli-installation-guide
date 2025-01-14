# Binary Verification Guide

## Using gh (if already installed)
```bash
gh at verify -R cli/cli gh_2.62.0_macOS_arm64.zip
```

## Using Sigstore cosign
```bash
cosign verify-blob-attestation --bundle cli-cli-attestation-3120304.sigstore.json \
      --new-bundle-format \
      --certificate-oidc-issuer="https://token.actions.githubusercontent.com" \
      --certificate-identity-regexp="^https://github.com/cli/cli/.github/workflows/deployment.yml@refs/heads/trunk$" \
      gh_2.62.0_macOS_arm64.zip
```