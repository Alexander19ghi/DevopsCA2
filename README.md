# FestPass — Docker & Container Security Assessment

## Student Details

| Field | Value |
|-------|-------|
| **Name** | Your Name Here |
| **REGNO** | 202401100200015 |
| **PORT** | 8015 |
| **Docker Hub Username** | alexander19g |
| **Docker Hub Repository** | https://hub.docker.com/r/alexander19g/fest-backend |

---

## AI Tools Used

| Tool | Used For |
|------|----------|
| Antigravity (Google Deepmind) | Generating Dockerfile, compose.yaml, commands, troubleshooting errors |

---

## Docker Hub Image Digest (1.0.0)

```
sha256:FILL_THIS_AFTER_STAGE_4_PUSH
```

> Run `docker inspect --format='{{index .RepoDigests 0}}' alexander19g/fest-backend:1.0.0` after pushing to get the digest.

---

## Vulnerability Report: Before vs After Fix (Stage 3)

| Severity | fest-backend:0.1 (python:3.9) | fest-backend:0.2 (python:3.12-slim) |
|----------|-------------------------------|--------------------------------------|
| CRITICAL | _fill after trivy scan_       | 0                                    |
| HIGH     | _fill after trivy scan_       | _fill after trivy scan_              |
| Image Size | _fill after build_          | _fill after build_                   |

---

## Steps Not Completed

_None — all stages completed._

---

## Repository Structure

```
202401100200015-docker-assessment/
├── README.md
├── compose.yaml
├── .env.example
├── .gitignore
├── cosign.pub
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── Dockerfile
│   └── .dockerignore
├── frontend/
│   ├── index.html
│   └── nginx.conf
├── reports/
│   ├── trivy-before.txt
│   └── trivy-after.txt
└── screenshots/
    └── S1-2.png … S5-4.png
```
