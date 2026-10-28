# Day 36 - Kubernetes ConfigMaps, Secrets & RBAC

## Objective
Practice Kubernetes configuration management,
Secrets, ServiceAccounts and RBAC.

## Tools
- Kubernetes
- kubectl
- Killercoda
- Nginx

## Implementation
1. Created appdev namespace.
2. Created app-config and web-content ConfigMaps.
3. Created app-secret.
4. Created pod-reader ServiceAccount.
5. Configured Role and RoleBinding.
6. Deployed Nginx with ConfigMaps and Secrets.
7. Exposed Nginx using ClusterIP Service.
8. Tested application using port-forward.
9. Verified RBAC permissions.

## Test Results
- Pod: Running
- Deployment: Available
- Nginx HTTP Response: Success
- List Pods: yes
- Delete Pods: no
- Read Secrets: no

## Key Learnings
- ConfigMaps store non-sensitive configuration.
- Secrets hold sensitive data.
- Base64 is not encryption.
- ServiceAccounts provide workload identity.
- Roles define permissions.
- RoleBindings grant permissions.
- RBAC supports least privilege.

## Security
Only sample credentials are provided.
Never commit real secrets to GitHub.
