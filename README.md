# LAB | Multi-Tier Guestbook App on K8s

This repo contains Kubernetes manifests for the classic **PHP Guestbook** app backed by **Redis Leader/Followers**.

- **Repo**: LAB-Multi-Tier-Guestbook-App-on-K8s
- **Owner (GitHub)**: `MTFerdi`
- **DockerHub user (optional image override)**: `fmtorres`

## Structure

```
LAB-Multi-Tier-Guestbook-App-on-K8s/
├─ k8s/
│  ├─ redis-leader-deployment.yaml
│  ├─ redis-leader-service.yaml
│  ├─ redis-follower-deployment.yaml
│  ├─ redis-follower-service.yaml
│  ├─ frontend-deployment.yaml
│  └─ frontend-service.yaml
└─ README.md
```

These manifests are adapted from the official Kubernetes Guestbook example.

