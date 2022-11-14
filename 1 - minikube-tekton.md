- install minikube  
https://formulae.brew.sh/formula/minikube
- run minikube
    `minikube start`
- verify minikube has started
    `kubectl cluster-info`
- install tekton    
    `kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml`
- monitor the installation
    `kubectl get pods --namespace tekton-pipelines --watch`

