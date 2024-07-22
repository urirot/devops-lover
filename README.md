# devops-lover

:green_book: **Just learning** :green_book:

## Content

- docker
- docker-compose
- GCR
- kubernetes
- GKE

## Material

- [Docker Tutorial for Beginners](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [Docker Compose Tutorial](https://www.youtube.com/watch?v=SXwC9fSwct8)
- [Kubernetes Tutorial for Beginners](https://www.youtube.com/watch?v=X48VuDVv0do)


## Debug locally with minikube
```brew install qemu```  
```brew install socket_vmnet
brew tap homebrew/services
HOMEBREW=$(which brew) && sudo ${HOMEBREW} services start socket_vmnet
```  
```brew install minikube```  
```minikube start --driver qemu --network socket_vmnet```


## Kubernetes setup
### mongodb
[How To Create the resources](https://medium.com/@ravipatel.it/deploying-mongodb-on-kubernetes-minikube-2c4f19a151f7)


## Run the project

run
`docker-compose up --build`
