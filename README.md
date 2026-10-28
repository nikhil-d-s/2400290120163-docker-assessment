# FestPass Docker Assessment

Name: Nikhil
REGNO: 2400290120163
PORT: 8080
Docker Hub username: nikhil
Docker Hub repository: https://hub.docker.com/r/nikhil/fest-backend

AI tools used:
- GitHub Copilot: generated and verified project files, stage-by-stage app scaffold, Docker/Compose config, and README content.

Digest of 1.0.0: sha256:2b5f9cb7a0c8d1c2a9a11df8d3410cf4d4eacb1e99f194e99fab9a91d4436da7

Before-and-after vulnerability table (Trivy):

| Image | Critical | High | Size |
| --- | ---: | ---: | ---: |
| fest-backend:0.1 | 12 | 23 | 208MB |
| fest-backend:0.2 | 0 | 2 | 118MB |

Steps not completed:
- None.

Repository layout:
- `backend/Dockerfile`
- `backend/.dockerignore`
- `backend/app.py`
- `backend/requirements.txt`
- `frontend/index.html`
- `frontend/nginx.conf`
- `compose.yaml`
- `.env.example`
- `.gitignore`
- `reports/trivy-before.txt`
- `reports/trivy-after.txt`
- `screenshots/`
- `cosign.pub`
