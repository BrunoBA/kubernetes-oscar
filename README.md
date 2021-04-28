# kubernetes-oscar


# Initialize Backend

```bash
k create -f backend.yaml -f service-backend.yaml -f ingress-backend.yaml
```

# Initialize Frontend

```bash
k create -f frontend.yaml -f service-frontend.yaml -f ingress-frontend.yaml
```