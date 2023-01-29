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
| `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` | `sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8` `dev-8.2` `dev-8.2.1` `dev-8.2.1-r0` | `sha256:b88275e9b5c6fd9968c38eace8e48421ac762440545ce6b479dc0d84e0c27129`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b88275e9b5c6fd9968c38eace8e48421ac762440545ce6b479dc0d84e0c27129) | `amd64` `arm64` |
| `dev-8.1` `dev-8.1.13` `dev-8.1.13-r0` | `sha256:19d96fe6db65f3d1e8801586f0b1210e4e0fd22f7683267eca4515ea6e5f3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:19d96fe6db65f3d1e8801586f0b1210e4e0fd22f7683267eca4515ea6e5f3418) | `amd64` `arm64` |
| `8.1` `8.1.13` `8.1.13-r0` | `sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0) | `amd64` `arm64` |
| `8.1.10` `8.1.10-bullseye` `8.1.10-cli` `8.1.10-cli-bullseye` `8.1.10-r0` | `sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11` `8.1.11-r2` | `sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.12-r0` | `sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-8` `glibc-8.1` `glibc-8.1.13` `glibc-8.1.13-r0` | `sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51) | `amd64` `arm64` |
| `glibc-dev-8` `glibc-dev-8.1` `glibc-dev-8.1.13` `glibc-dev-8.1.13-r0` | `sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b) | `amd64` `arm64` |
| `8` `8.2` `8.2.1` `8.2.1-r0` `latest` | `sha256:a83f65a956a17698596104b47c5cd0bb0f55167a35d02d6b9473f3344290a767`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a83f65a956a17698596104b47c5cd0bb0f55167a35d02d6b9473f3344290a767) | `amd64` `arm64` |
| `8-bullseye` `8-cli` `8-cli-bullseye` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.12` `8.1.12-bullseye` `8.1.12-cli` `8.1.12-cli-bullseye` `8.1.12-r1` `bullseye` `cli` `cli-bullseye` | `sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-r0` | `sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:a83f65a956a17698596104b47c5cd0bb0f55167a35d02d6b9473f3344290a767"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "b14103145691bdc5f8e83679d88471b6aa2b4560",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIE30hkjlYMeDkf3l0o1FBgqjijiTbYHMdGUzYZw8n3W/AiEAz9/yV6HE/j0PPW6lFb0QMuJJG5xEODUFYoKELEmgBeg=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI5NTEwZjc5NDdjODMxYjI2OTJhYWExYjI2ZmFkNzA5ZDY1MzY0OTliYjZiNGM4MDI5YzkwZjk4OWE1Yzc0YjM4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQzNwVldKU01KMSthTjVJYXV2QnhES1hFZ2lmMnJiNjhvc0hGYU81bTR4UUFpQS9YMlhlVDVUT2lpNnRFMTJNNXdxai9TT0lBdWdMZk9uR0E1YTUvYlN4M1E9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjFla05EUVRCRFowRjNTVUpCWjBsVlRqVlZkVzQzVm5wc05FZHlTblZtWkN0Uk9XUnNSbnBhUkU0d2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFVU1RSTlJGbDVUWHBOZVZkb1kwNU5hazEzVFZSSk5FMUVXWHBOZWsxNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ5UkdReWMxaFBNMEZ1TjBWS1IxVm5OVkpUY0c4d1ZWRjRia1ZUZFdaeFMzQnhUa2tLWjNKUGNuRlRWamt2VlUxUksyaDNSUzlDTVhaNFNrNDNUM1E0ZG5CMVozcGFObEJ2U0c5VGJGbzNUbU0wYkd0emJrdFBRMEZzT0hkblowcGlUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlVyZDFOUkNtSnlUakozTVZWSlJqUm1ZVXA0UzFsNlVISnlkR0ZCZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMWxxUlRCTlZFRjZUVlJSTVU1cWEzaFpiVkpxVGxkWk5GcFVaM3BPYW1NMVdrUm5ORTVFWTNoWmFscG9DbGxVU21sT1JGVXlUVVJCYzBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUWpSMVdqSnNNR0ZJVm1sTU0yUjJZMjEwYldKSE9UTmplVGw1V2xkNGJGbFlUbXdLVEc1c2FHSlhkM2RLWjFsTFMzZFpRa0pCUjBSMmVrRkNRbEZSV1ZreWFHaGhWelZ1WkZkR2VWcERNWEJpVjBadVdsaE5kbUZYTVdoYU1sWjZUVUl3UndwRGFYTkhRVkZSUW1jM09IZEJVVmxGUkROS2JGcHVUWFpoUjFab1draE5kbUpYUm5CaWFrTkNhVkZaUzB0M1dVSkNRVWhYWlZGSlJVRm5VamRDU0d0QkNtUjNRakZCVGpBNVRVZHlSM2g0UlhsWmVHdGxTRXBzYms1M1MybFRiRFkwTTJwNWRDODBaVXRqYjBGMlMyVTJUMEZCUVVKb1ptTk1ialpGUVVGQlVVUUtRVVZaZDFKQlNXZFRTVzVMVTNCRU1qQkxhRU55ZERFMEsxUkhLMjVGV1VSSlZrMTNWWFJCUmtOSGNFUjZLMjVRUnpaUlEwbElZM0p5ZVc0MlZVMHhlUXBzTm5WVVRuZDBZbTFZVm5GNFdrOXhWR1JyY2xWck16Tm5SMHg1U3l0NVVVMUJiMGREUTNGSFUwMDBPVUpCVFVSQk1tdEJUVWRaUTAxUlEzcFlNR1poQ25WMVkwNVBZM0pUWVVKNFowZ3lhRFpOYWpSTVdYRkNWbmxpTm5ZelVUbEhVMDlzTjJaMFdHOWFTM0ExY1VoYVMxbDZXbE5WZURKSFozWnpRMDFSUTA4S1EyUlVZM0YzVG1VNGIyUlhWMk41WnpsclZXWnpRbms1T1VsVVkzbDBWVnBxWlhWUlNFcG5ka3BsZFVSYVNqSXhRVlpNY1M5bmVrSnNhMVoxV0d0UlBRb3RMUzB0TFVWT1JDQkRSVkpVU1VaSlEwRlVSUzB0TFMwdENnPT0ifX19fQ==",
          "integratedTime": 1674887021,
          "logIndex": 12115683,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "b14103145691bdc5f8e83679d88471b6aa2b4560",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "4",
      "run_id": "4029153351",
      "sha": "b14103145691bdc5f8e83679d88471b6aa2b4560"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

