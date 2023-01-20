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
| `glibc-8` `glibc-8.1` `glibc-8.1.13` `glibc-8.1.13-r0` | `sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51) | `amd64` `arm64` |
| `glibc-dev-8` `glibc-dev-8.1` `glibc-dev-8.1.13` `glibc-dev-8.1.13-r0` | `sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b) | `amd64` `arm64` |
| `dev-8.2` `dev-8.2.1` `dev-8.2.1-r0` | `sha256:ef5a25c1d27d95ac5683263a5b4f68555566c243c996a78b7688d55df92220fc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ef5a25c1d27d95ac5683263a5b4f68555566c243c996a78b7688d55df92220fc) | `amd64` `arm64` |
| `8.2` `8.2.1` `8.2.1-r0` | `sha256:4c206bacb8cbc77b0350bae60ea05a0d0944813bf493f5361784998532ec4363`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4c206bacb8cbc77b0350bae60ea05a0d0944813bf493f5361784998532ec4363) | `amd64` `arm64` |
| `8.1.11-r0` | `sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11` `8.1.11-r2` | `sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.12-r0` | `sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` | `sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8` `dev-8.1` `dev-8.1.13` `dev-8.1.13-r0` | `sha256:d6eec4eb4064ef4c5b0794f31b8174744e6d255743a7e87e34f69269e0e15d77`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d6eec4eb4064ef4c5b0794f31b8174744e6d255743a7e87e34f69269e0e15d77) | `amd64` `arm64` |
| `8` `8.1` `8.1.13` `8.1.13-r0` `latest` | `sha256:be38fad411296b4c6734c5861d1a88cb71e41ed74cd1619e3d3f62e07e4f91d7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:be38fad411296b4c6734c5861d1a88cb71e41ed74cd1619e3d3f62e07e4f91d7) | `amd64` `arm64` |
| `8-bullseye` `8-cli` `8-cli-bullseye` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.12` `8.1.12-bullseye` `8.1.12-cli` `8.1.12-cli-bullseye` `8.1.12-r1` `bullseye` `cli` `cli-bullseye` | `sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.10` `8.1.10-bullseye` `8.1.10-cli` `8.1.10-cli-bullseye` `8.1.10-r0` | `sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:be38fad411296b4c6734c5861d1a88cb71e41ed74cd1619e3d3f62e07e4f91d7"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "4510212e7f5a94bb3fee9b14991d2d1810416a2f",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIHqAr4NqbBHw9GekEUw2gdTm1VpYqfmCmhfTiiL7HQqzAiBdM/9OkfnWw2eCafVVySfSMVsyuJrdfrGceHKtSfYmEg==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJmNGNiZWMxNDdhNDE0ZGM4ZDQxZGUxZDE4ZjIzMWM0ODIyZTJiNGI0Zjg2ZjBiYzFmODQwZjc3ZDg4NGFjM2U2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJSHVxejdibkkycFBUZ2xjRkVGZkNDbU15ZkxITllCOEI1SWdHZm1WTmZUcEFpRUFuNks0bXJ2QytuVlBrN2RTTFlyNmhpUm5GMmxiN2pwWTlKMXd0R3c5eVo0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjFSRU5EUVhvMlowRjNTVUpCWjBsVlVVZFdWVk5tUzIxTU5VWlFaRzVrY2tGM09FUlhPWFZ3VFdwamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFVUlRWTmFrVjRUVlJWTWxkb1kwNU5hazEzVFZSRk5VMXFSWGxOVkZVeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZoUTBFdk5qWTRiVUpDVlVnMWNqVkZZekp2TW1scGFrNVJUa056TlM4eGFrZEVNR0VLWWxrMFlrVnlaamhWZHpsd2VIUTBWSFpXZUROTFZtWldjbnBJTjNVMU1FZG9VekY2ZG5wRmNqZFlUM0J3ZFRCSlNqWlBRMEZzTUhkblowcGFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYzYjI1eUNtZDVkMWhrUkhCa2FrUndjWEpqY1RSV1dXbzNhbkZGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJjd1RsUkZkMDFxUlhsYVZHUnRUbGRGTlU1SFNtbE5NbHBzV2xSc2FVMVVVVFZQVkVaclRXMVJlRTlFUlhkT1JFVXlDbGxVU20xTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjB4Q1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtnd1JXVjNRalZCU0dOQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSbms1S3l0d2QwRkJRa0ZOUVZORVFrY0tRV2xGUVdoRU9WRnJjWG8xWVVsbmMyZFFSRkF4Y21SMmFIcGxSRWt6YUhwTmQxUk5Uemx4Vm5saE1qSnBRWGREU1ZGRE9XcFpiM2xPZWtKQ2VuVkxRUXBwTW1aMmJESkdMM3A1T0d4RE5IUkhWamxzV0RkYWJqTm1VMjV3WjJwQlMwSm5aM0ZvYTJwUFVGRlJSRUYzVG05QlJFSnNRV3BGUVhGSlRVMUlXVFZTQ2pOWmJYVkpaR3c1WjFkdFZVWjNVazlIWVM5RVZEWndjMGRqVlM5c2MzZFBURWxCV21aS1VteFNkakZGVG5aUVFWTkRhVWxMS3pnMFFXcEJhMkVyUW1ZS2FWbzJVVmhyTlRacVJDdEVkbGMxTWtvNGVuZEViMnhDYkdjNGRtZEdjbmROTHpOcVZsZE9WRTQxVlZKa2NERXhNRXBzZG1GNFRYcHpRMEU5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1674162726,
          "logIndex": 11536977,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "4510212e7f5a94bb3fee9b14991d2d1810416a2f",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3962399617",
      "sha": "4510212e7f5a94bb3fee9b14991d2d1810416a2f"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

