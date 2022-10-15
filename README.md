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
| `8` `8-bullseye` `8-cli` `8-cli-bullseye` `8.1` `8.1-bullseye` `8.1-cli` `8.1-cli-bullseye` `8.1.11` `8.1.11-bullseye` `8.1.11-cli` `8.1.11-cli-bullseye` `8.1.11-r0` `bullseye` `cli` `cli-bullseye` `latest` | `sha256:a002aa8ae729116054224f8ed52e64a58d469d0a11b0c018888fbbfb440a83cf`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a002aa8ae729116054224f8ed52e64a58d469d0a11b0c018888fbbfb440a83cf) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
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
        "docker-manifest-digest": "sha256:a002aa8ae729116054224f8ed52e64a58d469d0a11b0c018888fbbfb440a83cf"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "800614f684e15e5c48860e44ffa4fc4dc779e61a",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/php",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIFoTpNesvBundC3dlydeM/iJBEj+kMKhAd9fvky23KaUAiEAg9ZNptYrJwAn/Yx0VS7ZtJOmhJWxY0fm3dhWbj0cPd4=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkMDY5OGM4MzZjMTU2NDdjNDRmOTQxZDNmYzhlNmIzNTIwMDM0NTllZmM2MGZjMDRlNzAwYTQ1YThlOGE5NTdjIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUN1MGs1Mkx5dkIvL0NjN21EYUFac1pjZTVvc3E1MW5KVlJLU0NkbE9NenVBSWdNRXpnQXZrRHZuZmcrc0dnQkVRS2tVb1BqS3d5RjNERm10b2hzMCtvSVpNPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUndWRU5EUVhsNVowRjNTVUpCWjBsVlF6TXdNeXRrTVZWUGJERmtaRzVaWjNJdlNXMHJabFJPYVZWdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRCTlJFbDRUVlJKTkZkb1kwNU5ha2w0VFVSRk1FMUVTWGxOVkVrMFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ0TmxCM05WSk9jbEp2VEZOcU5IRjBWbGhvTm5aUVRWbE5kaTk0VFRkd1ltbEpVR1VLV1RadGVqWnhVa1pYY0hwUVJISlNWV0poTUdVMVRtUjNjalZ5WkdGR01IUXhjRWxyY25Kb1EzZHdaVEpoY1VSTWVXRlBRMEZyYzNkblowcElUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZwU0hadkNtUjRjRWswVURscmRGQXdhRTV2VFhWeE1VbFJOSFpWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDFwUldVUldVakJTUVZGSUwwSkdjM2RYV1ZwWVlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6UW05alF6aDFXakpzTUdGSVZtbE1NMlIyWTIxMGJXSkhPVE5qZVRsNVdsZDRiRmxZVG14TWJteG9ZbGQ0UVdOdFZtMWplVGx2Q2xwWFJtdGplVGwwV1Zkc2RVMUVhMGREYVhOSFFWRlJRbWMzT0hkQlVVVkZTekpvTUdSSVFucFBhVGgyWkVjNWNscFhOSFZaVjA0d1lWYzVkV041Tlc0S1lWaFNiMlJYU2pGak1sWjVXVEk1ZFdSSFZuVmtRelZxWWpJd2QwWm5XVXRMZDFsQ1FrRkhSSFo2UVVKQloxRkpZekpPYjFwWFVqRmlSMVYzVG1kWlN3cExkMWxDUWtGSFJIWjZRVUpCZDFGdlQwUkJkMDVxUlRCYWFsazBUa2RWZUU1WFZURlplbEUwVDBSWmQxcFVVVEJhYlZwb1RrZGFhazVIVW1wT2VtTTFDbHBVV1hoWlZFRmpRbWR2Y2tKblJVVkJXVTh2VFVGRlJVSkJOVVJqYlZab1pFZFZaMVZ0Vm5OYVYwWjZXbFJCYWtKbmIzSkNaMFZGUVZsUEwwMUJSVVlLUWtKV2FtRkhSbkJpYldReFdWaEthMHhYYkhSWlYyUnNZM2s1ZDJGSVFYZElVVmxMUzNkWlFrSkJSMFIyZWtGQ1FtZFJVR050Vm0xamVUbHZXbGRHYXdwamVUbDBXVmRzZFUxSlIweENaMjl5UW1kRlJVRmtXalZCWjFGRFFrZ3dSV1YzUWpWQlNHTkJRMGREVXpoRGFGTXZNbWhHTUdSR2NrbzBVMk5TVjJOWkNuSkNXVGwzZW1wVFltVmhPRWxuV1RKaU0wbEJRVUZIUkRGRlRFTnlkMEZCUWtGTlFWTkVRa2RCYVVWQk4wbENMM0JZZWpCSWNURm1WRXg2TVdKUGNsY0tRVzE0VWxOWVFtMUdkMHhyUnpab015OWhLMDB2VnpCRFNWRkRkRGxUV0docGNGSnFUakpxTlUxYWJXSnVZbVprSzAxVVRYVndUekZ2UnpZclJHRkxhUW96U25odFJHcEJTMEpuWjNGb2EycFBVRkZSUkVGM1RtNUJSRUpyUVdwQ1IydDFUMnBMV0RBdk9UUmFMMnBTTUZZeGNVNWphMmRyVjNWTFoyRlRORFJxQ205bmRYZFlWVUZ1YUVZNU9HVjRibW94VDBKSU9GaDBlSG9yTVhadlFuTkRUVVp6TUN0SlpIa3lPVTVqZEZsSmNVeFdSblpoU0hoaVpVaE1OMFZoVlZFS1VGcEdXa3hMWjJJeFJGUnNiVGRvVW5ndlJ6TmFUa2ROVTBoQ1FUSnNUVEpDVVQwOUNpMHRMUzB0UlU1RUlFTkZVbFJKUmtsRFFWUkZMUzB0TFMwSyJ9fX19",
          "integratedTime": 1665713528,
          "logIndex": 5065185,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/php/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/php",
      "githubWorkflowSha": "800614f684e15e5c48860e44ffa4fc4dc779e61a",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3246963360",
      "sha": "800614f684e15e5c48860e44ffa4fc4dc779e61a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

