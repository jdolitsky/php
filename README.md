# php

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/jdolitsky/php/actions/workflows/release.yaml/badge.svg)](https://github.com/jdolitsky/php/actions/workflows/release.yaml)

This is a minimal PHP image based on Alpine, using PHP apks available on the Alpine Community repositories (not built from source as of now).<br/><br/>While this image is being developed, we will stick to the latest stable PHP version which at this moment is `8.1`. Supported versions in the long term are TBD.

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/php:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `dev-8.2` `dev-8.2.1` `dev-8.2.1-r0` | `sha256:a5a8f94b4935393395633d02e402d832d5cc67566ade70d0a2930a7895385862`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a5a8f94b4935393395633d02e402d832d5cc67566ade70d0a2930a7895385862) | `amd64` `arm64` |
| `8` `8.2` `8.2.1` `8.2.1-r0` `latest` | `sha256:7a0fb2080ca93d57250c6829c6dbd0d4f2c6c888935093846ea0e5d0fef6a39d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7a0fb2080ca93d57250c6829c6dbd0d4f2c6c888935093846ea0e5d0fef6a39d) | `amd64` `arm64` |
| `8-bullseye` `8-cli` `8-cli-bullseye` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.12` `8.1.12-bullseye` `8.1.12-cli` `8.1.12-cli-bullseye` `8.1.12-r1` `bullseye` `cli` `cli-bullseye` | `sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` | `sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.12-r0` | `sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-dev-8` `glibc-dev-8.1` `glibc-dev-8.1.13` `glibc-dev-8.1.13-r0` | `sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b) | `amd64` `arm64` |
| `dev-8` `dev-8.1` `dev-8.1.13` `dev-8.1.13-r0` | `sha256:d665f8f9cce5c481f946d1664e1905aab90a9759034ff035a109f766a3a00ce4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d665f8f9cce5c481f946d1664e1905aab90a9759034ff035a109f766a3a00ce4) | `amd64` `arm64` |
| `8.1` `8.1.13` `8.1.13-r0` | `sha256:36755fdf20a89aa71407d82881653b761a27fa17601b8333eb9aafb2c054779c`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:36755fdf20a89aa71407d82881653b761a27fa17601b8333eb9aafb2c054779c) | `amd64` `arm64` |
| `8.1.10` `8.1.10-bullseye` `8.1.10-cli` `8.1.10-cli-bullseye` `8.1.10-r0` | `sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-r0` | `sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11` `8.1.11-r2` | `sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-8` `glibc-8.1` `glibc-8.1.13` `glibc-8.1.13-r0` | `sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51) | `amd64` `arm64` |


## Usage

To try out the image, run:

```shell
docker run --rm cgr.dev/chainguard/php --version
```

```
PHP 8.1.10 (cli) (built: Sep  1 2022 16:13:09) (NTS)
Copyright (c) The PHP Group
Zend Engine v4.1.10, Copyright (c) Zend Technologies
```

## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/php:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/php:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/php"
      },
      "image": {
        "docker-manifest-digest": "sha256:7a0fb2080ca93d57250c6829c6dbd0d4f2c6c888935093846ea0e5d0fef6a39d"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "22b44286e8fe879c712ef8aefe9b359cf396b28a",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCICqdPG3UI1yZ65kdEmp0IbrVwIXXEPzxvKWMohB8r3SOAiEA15ScgrQ4+s4eQNMEThIutdbbm80TZoc0wgVTeZEh95w=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJlODU0NjU0NDdlZDRhNjg1NDNmMDRiYTRkZGY0Y2JhNGRlOGM2ZmYyODJlNWM4YzExOWUxYTc1ZjI4ZTE0YzcxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJR01aYS9iMTlvWmVGM2VPeWowSlhINlljcnExclZxTEc0Vi9haUZQaVFDYUFpQWRiM1NWVTdydHNEQWF1ZVZOaEJ3V3RxbFBiU3c3aHN0azlLV3NLUXMrYVE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjBla05EUVhvMlowRjNTVUpCWjBsVlYzUnNiRVZSU0ZGRVZIZG5PSFpNZVRrdlNuWjVOekpMUW1aQmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFVUlRSTlJFVXdUbnBOZVZkb1kwNU5hazEzVFZSRk5FMUVSVEZPZWsxNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYzV1hCemJubG1NRWhwVjNKVk4xTXZNWE5oYWtodGRHaEhWRkZ0SzB3MWVUUkplRWdLVlV4U2FVSXhhMlJITjBGSmJFdzJaVE50V21FclJHdFhWVEUyTWxadk4yaDFiWGx3YlVwbU9GVkdRa3gzYmxCWWJtRlBRMEZzTUhkblowcGFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZDVkVGSENrYzFOakJWYkRocFlWcG1jSEUzYlVaRGJqbG5iMWx2ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJkNVRXMUpNRTVFU1RST2JWVTBXbTFWTkU1NmJHcE9la1Y1V2xkWk5GbFhWbTFhVkd4cFRYcFZOVmt5V1hwUFZGcHBDazFxYUdoTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjB4Q1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtnd1JXVjNRalZCU0dOQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSbmR2T1dGdFowRkJRa0ZOUVZORVFrY0tRV2xGUVRjMGJsRTFlVWhYZWtacFdHeFFiRkZYZVc1TVVFRkljWEVyUVZwc1VtNUROM0F6VVhRNFZURXJaVmxEU1ZGRGIyVlhPRWswYmpCTmJWZFBZZ280VTFweWMyUXpNVEZLU0VwbGEyNTJjbUU1THk5bU5YZFhRMkpQYzBSQlMwSm5aM0ZvYTJwUFVGRlJSRUYzVG01QlJFSnJRV3BDZEc5dGNUTkpWUzlqQ2xoRGFtOURMMmhvT0haRGFFSkhlV3R2Y1ZoRlJWWXhSVEkwWWtGcE9FSlhURlppU0RKRlkzVnhlbVp1YTJkVFFqWTRSRTVDYTNkRFRVTmxSbEU0WjA0S04wRjVWVWhUUkU1YVJ6UkVTMWxNYWpKM1pFdDRPVVJsYkdRNFNGVm5NMlJVVTNaTWQyVjFaRmxoUVhoMGNHTndVVzVtWlZNMVdreHdaejA5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1674006462,
          "logIndex": 11402646,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "22b44286e8fe879c712ef8aefe9b359cf396b28a",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3944925610",
      "sha": "22b44286e8fe879c712ef8aefe9b359cf396b28a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

