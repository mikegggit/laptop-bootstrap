Installs
========

DMG
---
* Visual Studio Code
* IntelliJ CI
* Docker Desktop (if using as driver for minikube)

Appstore
--------
* TODO


CLI
---
oh-my-zsh - https://ohmyz.sh/#install



Brew
----
xargs brew install < brew-leaves.txt




Minikube
--------

See https://minikube.sigs.k8s.io/docs/start/


brew install minikube


minikube start

``` 
➜  minikube-setup git:(main) k config get-contexts
CURRENT   NAME             CLUSTER          AUTHINFO         NAMESPACE
          docker-desktop   docker-desktop   docker-desktop   networking
*         minikube         minikube         minikube         default
```

minikube stop



minikube start --network-plugin=cni --cni=calico


➜  minikube-setup git:(main) minikube status
🎉  minikube 1.31.1 is available! Download it: https://github.com/kubernetes/minikube/releases/tag/v1.31.1
💡  To disable this notice, run: 'minikube config set WantUpdateNotification false'

minikube
type: Control Plane
host: Running
kubelet: Running
apiserver: Running
kubeconfig: Configured

### Calico
https://docs.tigera.io/calico/latest/getting-started/kubernetes/minikube


Repos
-----
cd ~/.
git clone git@github.com:mikegggit/dotfiles.git


# install 
cd ~/dotfiles
stow ssh
stow omz
stow zsh



