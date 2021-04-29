```
bash
argocd app create s50600822gb --repo https://github.com/s50600822/argocd-example-apps.git --path helm-guestbook --dest-namespace s50600822 --dest-server https://kubernetes.default.svc --helm-set replicaCount=1
```