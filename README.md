# helm-repo-debug
Debugging publishing helm charts

helm repo add makalis-debug https://makalis.github.io/helm-repo-debug/
helm search repo makalis-debug
helm template makalis-debug makalis-debug/makalis-debug
