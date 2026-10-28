# FestPass: Docker & Container Security Assessment (CA-2)

| Item | Value |
|---|---|
| Name | Anurag Shrivastav |
| REGNO | 202401100200071 |
| PORT | 8071 |
| Docker Hub username | anurag018018 |
| Docker Hub repository | https://hub.docker.com/r/anurag018018/fest-backend |
| GitHub repository | https://github.com/Anurag-spec1/202401100200071_docker_assesment |

## AI tools used

- Copilot in VS Code: helped inspect and fix the provided backend DB configuration, update the Docker image hardening and Compose settings, and run the assessment commands. I ran the builds and scans locally.

## Digest of 1.0.0 as pushed to Docker Hub

```
sha256:cecce84f94b3a5d11c0567246fccc95161ce5fbf4c42a5d0022b098ed0104c1a
```

## Vulnerability table (Stage 3.3)

| Image | CRITICAL | HIGH | Size |
|---|---:|---:|---:|
| fest-backend:0.1 (python:3.9) | 234 | 2,249 | 1.61 GB |
| fest-backend:0.2 (python:3.13-slim, non-root) | 0 | 49 | 216 MB |

Counts sum the per-target `Total:` lines in the corresponding Trivy report. Image sizes are from `docker images fest-backend`.

## Steps not completed

- Cosign key generation, signing 1.0.0, verifying the signed and unsigned images, and their screenshots remain to be done.
- Assessment screenshots still need to be captured by the student on their machine; the required registration entries also need to be added in the browser for the screenshots.
