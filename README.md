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
| `dev-8.2.1-r0` | `sha256:5991122b462c37011cd2f9e621bca7cfe2ccdf8e2a3f4802de236e7033f175dc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5991122b462c37011cd2f9e621bca7cfe2ccdf8e2a3f4802de236e7033f175dc) | `amd64` `arm64` |
| `8.2.1` `8.2.1-r1` | `sha256:3bd27e14f7d8625fcc4666584dc67fde6b20c101463ca53bc8f394882e099a7e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3bd27e14f7d8625fcc4666584dc67fde6b20c101463ca53bc8f394882e099a7e) | `amd64` `arm64` |
| `8.2.1-r0` | `sha256:5f14fdaa62cb227a74fbedac5a42c76dc71ade05cae73bcdb3e5e2936ff6a961`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5f14fdaa62cb227a74fbedac5a42c76dc71ade05cae73bcdb3e5e2936ff6a961) | `amd64` `arm64` |
| `8.1` `8.1.13` `8.1.13-r0` | `sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0) | `amd64` `arm64` |
| `8.1.12-r0` | `sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-8` `glibc-8.1` `glibc-8.1.13` `glibc-8.1.13-r0` | `sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51) | `amd64` `arm64` |
| `glibc-dev-8` `glibc-dev-8.1` `glibc-dev-8.1.13` `glibc-dev-8.1.13-r0` | `sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b) | `amd64` `arm64` |
| `8-bullseye` `8-cli` `8-cli-bullseye` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.12` `8.1.12-bullseye` `8.1.12-cli` `8.1.12-cli-bullseye` `8.1.12-r1` `bullseye` `cli` `cli-bullseye` | `sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` | `sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8.2.1` `dev-8.2.1-r1` | `sha256:cc64e34710093b85afe131c39ffa1f7cc68e5e79133a9fa04c8afa7441ef949a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:cc64e34710093b85afe131c39ffa1f7cc68e5e79133a9fa04c8afa7441ef949a) | `amd64` `arm64` |
| `fpm-8` `fpm-8.2` `fpm-8.2.2` `fpm-8.2.2-r0` | `sha256:d41f9f01fb98abe2ae6bf9796b6d5cf4f3722cd941f90e055b7682e56b62a902`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d41f9f01fb98abe2ae6bf9796b6d5cf4f3722cd941f90e055b7682e56b62a902) | `amd64` `arm64` |
| `8` `8.2` `8.2.2` `8.2.2-r0` `latest` | `sha256:42bcd225332d442c9d8ef2ce0758313916d19edbfbc258b366d7b57a483b00d7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:42bcd225332d442c9d8ef2ce0758313916d19edbfbc258b366d7b57a483b00d7) | `amd64` `arm64` |
| `8.1.10` `8.1.10-bullseye` `8.1.10-cli` `8.1.10-cli-bullseye` `8.1.10-r0` | `sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `fpm-8.2.1` `fpm-8.2.1-r1` | `sha256:7d22f12b226908c6ed7c15a59f0dfaf395298bdabe64d235f5b075d4153f5bd4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7d22f12b226908c6ed7c15a59f0dfaf395298bdabe64d235f5b075d4153f5bd4) | `amd64` `arm64` |
| `8.1.11-r0` | `sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11` `8.1.11-r2` | `sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8` `dev-8.2` | `sha256:f8700434d69a959765155b8e0478e019c025973a696a785e6ab2b03011cf4ca7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:f8700434d69a959765155b8e0478e019c025973a696a785e6ab2b03011cf4ca7) | `amd64` `arm64` |
| `dev-8.1` `dev-8.1.13` `dev-8.1.13-r0` | `sha256:19d96fe6db65f3d1e8801586f0b1210e4e0fd22f7683267eca4515ea6e5f3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:19d96fe6db65f3d1e8801586f0b1210e4e0fd22f7683267eca4515ea6e5f3418) | `amd64` `arm64` |


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
        "docker-manifest-digest": "sha256:42bcd225332d442c9d8ef2ce0758313916d19edbfbc258b366d7b57a483b00d7"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "e4a5d39be946c9b2aa029d88bff0cec40d4edda3",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQD1n4UX3COeF/g1nYh89QKj0oD8N4ig+1mNW9ZLlVaW1gIgSa4gsAOhzrlcFYZfv89U4nLhhD2paC2yAf9Z984g8r8=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJjYzFkMDhjYjg1YTg5YmRlMGE5MzBlODM5ZDZiNjhjOTYyZDU3NTliYzdkNmU1Y2MzNGRmYjI4NGM0NGFjYjBhIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURDZ2t6SmFlSzlyUVpjNEh0NnZZL00vT2tKVHFWbGlxMk9NSW5SWkFHazBRSWdDZ2cwVmZnT2lMU1MxMjBXMXl0SUlHVk56Qk9kMmd5Ni9XOFhVVnkzTG1VPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjFha05EUVRCRFowRjNTVUpCWjBsVlkyTllUSEpGZG1WTGFGSjFNRUUyZEhZMFZXbE5iRTFGWWtOQmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFxUVROTlJFRjRUVVJOTWxkb1kwNU5hazEzVFdwQk0wMUVRWGxOUkUweVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZrZVhKYVIwODFjbEJ3WTFSVGRFdFJVRkJNZFRKaEwwdENiR2R0Ums1WmNUVjZZazBLWmk5M1dGUXdLM2RVU1d3NVNtZzJSRFZOTUZab1ozRldOMHBMVTFWRmFuVjFWR1ZDUTB4V1QwWnRTSFpZZGxSSmVtRlBRMEZzT0hkblowcGlUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlU0Tm1vNENrOXNOMjV3VVc4MU0wRTJkV2gzU1ZkNVVsa3ZiMHAzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMXBVVW1oT1YxRjZUMWRLYkU5VVVUSlplbXhwVFcxR2FFMUVTVFZhUkdjMFdXMWFiVTFIVG14WmVsRjNDbHBFVW14YVIxSm9UWHBCYzBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUWpSMVdqSnNNR0ZJVm1sTU0yUjJZMjEwYldKSE9UTmplVGw1V2xkNGJGbFlUbXdLVEc1c2FHSlhkM2RLWjFsTFMzZFpRa0pCUjBSMmVrRkNRbEZSV1ZreWFHaGhWelZ1WkZkR2VWcERNWEJpVjBadVdsaE5kbUZYTVdoYU1sWjZUVUl3UndwRGFYTkhRVkZSUW1jM09IZEJVVmxGUkROS2JGcHVUWFpoUjFab1draE5kbUpYUm5CaWFrTkNhVkZaUzB0M1dVSkNRVWhYWlZGSlJVRm5VamRDU0d0QkNtUjNRakZCVGpBNVRVZHlSM2g0UlhsWmVHdGxTRXBzYms1M1MybFRiRFkwTTJwNWRDODBaVXRqYjBGMlMyVTJUMEZCUVVKb2FXc3hlVkJqUVVGQlVVUUtRVVZaZDFKQlNXZFNOR1JPU0N0U2FIRjZObVJKU2xkbmQyWnNaR0kxYldKRU4zQXdVak0yWVhjNGQyaHVTME1ySzBKdlEwbEZiM1J1TVRoaE5YazBSd3BzT0d4c1pVSTRWa2xzVkRoWVNGQlZSRUU0VjFKb2VHcHNSWGQwYmtkYVprMUJiMGREUTNGSFUwMDBPVUpCVFVSQk1tZEJUVWRWUTAxRFJESktNVGhxQ205blpXOXVkMkUzVnpCbFJURjNVMjVKZEdKaFZrcG5ZV1pYZEhkVWNIWmpibGR5U25GMWNXTnFibkpHZDNBd0wxSkJiakphTVVGcVQxRkplRUZMTW04S1JqWmlOR28yY0ZkS1JYbG1iV0Z1TVRGeWRtbGFhMFpGWjJ4NGFuQTNlRE5oTUVsaE5EazBWRkF5VjI5YVYwTlBaVFF2TWtodE5YVjBWVGhYVmtFOVBRb3RMUzB0TFVWT1JDQkRSVkpVU1VaSlEwRlVSUzB0TFMwdENnPT0ifX19fQ==",
          "integratedTime": 1675728642,
          "logIndex": 12777950,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "e4a5d39be946c9b2aa029d88bff0cec40d4edda3",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "4109115919",
      "sha": "e4a5d39be946c9b2aa029d88bff0cec40d4edda3"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

