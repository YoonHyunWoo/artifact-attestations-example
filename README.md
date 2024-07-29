This repository provides an example of generating build artifact attestations for Go applications.

## Attestation Generation and Verification
1. When code is pushed, GitHub Actions are triggered to build and generate attestations.
2. To verify the created `build-attestation.json` file, use the following command:
   ```sh
   cat build-attestation.json
   ```
3. You can check if the attestation file was successfully generated.

For more information, refer to [GitHub Docs](https://docs.github.com/en/actions/security-guides/using-artifact-attestations-to-establish-provenance-for-builds#generating-artifact-attestations-for-your-builds).