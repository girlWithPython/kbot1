Kubeplugin is designed to get resource usage statistics from Kubernetes, kube-system namespace, in the format: "Resource, Namespace, Name, CPU, Memory"

How to use kubeplugin*:
1. Use "kubectl kubeplugin" command**

*Pre-conditions: minikube has to be started, kubectl installed, minikube addons metrics-server enabled

**Troubleshooting:
In case of "error: unknown command "kubeplugin" for "kubectl" use the commands "sudo chmod +x ./kubectl-kubeplugin" and 'export PATH="/workspaces/kbot1/scripts:$PATH"' from the .scripts directory