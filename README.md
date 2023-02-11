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
| `8.1.12-r0` | `sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b4c7b000c519369152c1ce80ec5b8a8177fde27a12d416b94af6d73a05e90b52) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-8` `glibc-8.1` `glibc-8.1.13` `glibc-8.1.13-r0` | `sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a8354eb8c3b5aa5f4948297147771e1bf51d648a78dbdc5092f7c2ddc549fd51) | `amd64` `arm64` |
| `8.2.1` `8.2.1-r1` | `sha256:3bd27e14f7d8625fcc4666584dc67fde6b20c101463ca53bc8f394882e099a7e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3bd27e14f7d8625fcc4666584dc67fde6b20c101463ca53bc8f394882e099a7e) | `amd64` `arm64` |
| `8.2.1-r0` | `sha256:5f14fdaa62cb227a74fbedac5a42c76dc71ade05cae73bcdb3e5e2936ff6a961`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5f14fdaa62cb227a74fbedac5a42c76dc71ade05cae73bcdb3e5e2936ff6a961) | `amd64` `arm64` |
| `fpm-8.2.1` `fpm-8.2.1-r1` | `sha256:7d22f12b226908c6ed7c15a59f0dfaf395298bdabe64d235f5b075d4153f5bd4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7d22f12b226908c6ed7c15a59f0dfaf395298bdabe64d235f5b075d4153f5bd4) | `amd64` `arm64` |
| `8.1` `8.1.13` `8.1.13-r0` | `sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4c008e154e82f3e551e185f77947e57035986ad809b82cb0b9b6d897224a87d0) | `amd64` `arm64` |
| `8.1.10` `8.1.10-bullseye` `8.1.10-cli` `8.1.10-cli-bullseye` `8.1.10-r0` | `sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5e144068a1ef73b8323543fc3ca0d3d01b752637c690993ff16172f370af4bbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-r0` | `sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d46b713a1b507d70e7e471510e4f94013b4a8adcaa3d26f3ee5044d9aef5c9b5) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `glibc-dev-8` `glibc-dev-8.1` `glibc-dev-8.1.13` `glibc-dev-8.1.13-r0` | `sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0e10340c93f91ced308891ef7e8695f64f20398c0af7a2731d54118c8818ba5b) | `amd64` `arm64` |
| `fpm-8` `fpm-8.2` `fpm-8.2.2` `fpm-8.2.2-r0` | `sha256:64a3846b7c3eaf97e343ad7dc1b15a6e7071db4e7f8982f045b1a138984b603f`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64a3846b7c3eaf97e343ad7dc1b15a6e7071db4e7f8982f045b1a138984b603f) | `amd64` `arm64` |
| `8.1.11` `8.1.11-r2` | `sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:68f08d147fcac5c3b5c92020201d2ba8a50f11f55d6ba3c6e4c0e085960f96a3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` | `sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:16cbf167b6bf23ad27985c8d85faf2a2db395a2e61c6267041fec1346fa42c6a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8.2.1` `dev-8.2.1-r1` | `sha256:cc64e34710093b85afe131c39ffa1f7cc68e5e79133a9fa04c8afa7441ef949a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:cc64e34710093b85afe131c39ffa1f7cc68e5e79133a9fa04c8afa7441ef949a) | `amd64` `arm64` |
| `dev-8.2.1-r0` | `sha256:5991122b462c37011cd2f9e621bca7cfe2ccdf8e2a3f4802de236e7033f175dc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5991122b462c37011cd2f9e621bca7cfe2ccdf8e2a3f4802de236e7033f175dc) | `amd64` `arm64` |
| `8` `8.2` `8.2.2` `8.2.2-r0` `latest` | `sha256:8db25771d4a10e191a3c372db7e1acf22257f34d031ab0ca44a5d17781fdc8b9`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:8db25771d4a10e191a3c372db7e1acf22257f34d031ab0ca44a5d17781fdc8b9) | `amd64` `arm64` |
| `8-bullseye` `8-cli` `8-cli-bullseye` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.12` `8.1.12-bullseye` `8.1.12-cli` `8.1.12-cli-bullseye` `8.1.12-r1` `bullseye` `cli` `cli-bullseye` | `sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:64654489c4d9350afc093213b0809f71df778fb1927657bfb4ef4293e8b1d226) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `dev-8` `dev-8.2` `dev-8.2.2` `dev-8.2.2-r0` | `sha256:87ec0ce9fe8993a21d353d0b2dd80a354ad4cceee94f5c8c12761608226d84ac`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:87ec0ce9fe8993a21d353d0b2dd80a354ad4cceee94f5c8c12761608226d84ac) | `amd64` `arm64` |
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
        "docker-manifest-digest": "sha256:8db25771d4a10e191a3c372db7e1acf22257f34d031ab0ca44a5d17781fdc8b9"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "72f15ab347b1d859b970ca4b1810b55826658d85",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIC34Ic7uTmyASmI2nkyVsNhTD+n0wZZURfSZ8htotrVlAiBSXr6gy2ns1ieRZK2mCTAT6y5pZ0W5BMf+0AvCTcD3zw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyOWJiNDZmMTEzNTIyMjc4ODk3YjY1ODllNmY4MGVmZjYxNjRkNTAwYzI4OTc1MzI1OWQ0ZWJkM2NlYWJhYjMyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRENaQ09QbHZWOXo0R25GVjdDTUQwZEdVM1R2c0hRejBvdGNqTlovTE42Q0FpQi83R1Y1R2tJSVhuNnZWY1dVaXFlUkhpcFZ6dldQT21pQWY0U1A0dzBuWHc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjJSRU5EUVRCSFowRjNTVUpCWjBsVlZEbG9XVkpSYVVaeU55dEVNVlZSWWtSRlpYQnJRMlZhTVdwM2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFxUlhkTlJFRjRUVlJCZDFkb1kwNU5hazEzVFdwRmQwMUVRWGxOVkVGM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZJYVU1eVNIaDJSbU5sUkVzNUszUnZhRmN6ZEV4d00xUlRiM2Q2U1VGRVJtVnpiWEVLWkRObE1FMTJLMlJqYUVVdmVqRXJXaTlFWmtkM1oySmlVbXc0Ums0MWVrZFFSVWhVUkRCSUsydG5USGxJV2pSQ1MwdFBRMEZ0UVhkblowcGpUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZSVEZwa0NuaElaVVpXSzFCUmQwWnVNbU4zZVhOdVVsVlplSEJaZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMDU2U20xTlZGWm9XV3BOTUU0eVNYaGFSR2N4VDFkSk5VNTZRbXBaVkZKcFRWUm5lRTFIU1RGT1ZHZDVDazVxV1RGUFIxRTBUbFJCYzBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUWpSMVdqSnNNR0ZJVm1sTU0yUjJZMjEwYldKSE9UTmplVGw1V2xkNGJGbFlUbXdLVEc1c2FHSlhkM2RLWjFsTFMzZFpRa0pCUjBSMmVrRkNRbEZSV1ZreWFHaGhWelZ1WkZkR2VWcERNWEJpVjBadVdsaE5kbUZYTVdoYU1sWjZUVUl3UndwRGFYTkhRVkZSUW1jM09IZEJVVmxGUkROS2JGcHVUWFpoUjFab1draE5kbUpYUm5CaWFrTkNhV2RaUzB0M1dVSkNRVWhYWlZGSlJVRm5VamhDU0c5QkNtVkJRakpCVGpBNVRVZHlSM2g0UlhsWmVHdGxTRXBzYms1M1MybFRiRFkwTTJwNWRDODBaVXRqYjBGMlMyVTJUMEZCUVVKb2FtbHdUelIzUVVGQlVVUUtRVVZqZDFKUlNXaEJUbEZoWldKV09VcHJORGw1YjNGYVQyeE1hMEZ3WkhOeVRrMVhhRVJZVFVSSFFYWkxOa1I0U1d0MlRFRnBRVnBvTjI1UU9FVTJRZ3A2Tmsxa1dYRXlaMWxSTXk5bFZqUmlibWxwVlVsVVFXZFJjVFF5YzIxUFZWcFVRVXRDWjJkeGFHdHFUMUJSVVVSQmQwNXdRVVJDYlVGcVJVRTFNWGN2Q200eE5rWlJVazgzWVN0SVZsTTRNSGRXYUc5dVpEUnZZM014VjBKbmJrdzBjVkowVGs5UlNqVTBlRVZXTVU5VFpVVmhVVVJqVUc4cmJIaFdkVUZxUlVFS2JHVTBWMDVWUlRocVQzcG5XbTFOT0dvdlRXdG1ValJOZDI5QmRpOXNTek5xVjIxRlVHY3dhMmh5TDBOS1RtVXhSa2R5YW1OUWIxVjBRVmd3VVRaTmNnb3RMUzB0TFVWT1JDQkRSVkpVU1VaSlEwRlVSUzB0TFMwdENnPT0ifX19fQ==",
          "integratedTime": 1675987870,
          "logIndex": 13008211,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "72f15ab347b1d859b970ca4b1810b55826658d85",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "4139544178",
      "sha": "72f15ab347b1d859b970ca4b1810b55826658d85"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

