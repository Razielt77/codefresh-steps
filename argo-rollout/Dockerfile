FROM codefresh/kubectl:1.18.2
RUN curl -LO https://github.com/argoproj/argo-rollouts/releases/latest/download/kubectl-argo-rollouts-linux-amd64
RUN chmod +x ./kubectl-argo-rollouts-linux-amd64
RUN mv ./kubectl-argo-rollouts-linux-amd64 /usr/local/bin/kubectl-argo-rollouts
RUN curl -sSL -o /usr/local/bin/argocd https://github.com/argoproj/argo-cd/releases/download/v1.5.5/argocd-linux-amd64
RUN chmod +x /usr/local/bin/argocd
