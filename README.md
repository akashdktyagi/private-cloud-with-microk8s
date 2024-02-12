# My private cloud wit microk8s stuff

### Sample k8s yml file for various use cases

### Volumes
* Empty Dir: [empty dir- WORKING](volumes/empty-dir-volume-pod.yml)
* Host Path:  [host path - WORKING](volumes/empty-dir-volume-pod.yml)
* GitRepo: [git repo - Not Working](volumes/empty-dir-volume-pod.yml)
    * Unable to make it work due to git repo not being clones and container unable to start due to failed mount.
* MongoDB with Host path: [mongo db with host path-NOT WORKING](volumes/empty-dir-volume-pod.yml) 
    * Tried but unable to create a DB and Test. Need to try again.