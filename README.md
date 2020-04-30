# 2020-04-cncf-rancher-meetup

Show notes from April 2020 CNCF + Rancher Labs meetup

## Rancher K3s on Raspberry Pi

* To prepare the Pi, I just used [Raspbian](https://www.raspberrypi.org/downloads/).
* On my Mac, I used [BalenaEtcher](https://etcher.io/) to transfer the zip on the MicroSD. *TIP*: [creating an empty file named SSH on the root filesystem enable `ssh` at first boot](https://www.raspberrypi.org/documentation/remote-access/ssh/README.md).
* All other steps are documented in the files in `k3s` directory.

## Minikube

* discover minikube option that could be useful 
* test deployment of a go application to your minikube 
* test skaffold inside k8s through minikube
* all steps to test minikube and the go application are int the scenario text file

## Other notes

* Minikube: [kubernetes.io](https://kubernetes.io/docs/setup/learning-environment/minikube/).
* Skafold: [skaffold.dev](https://skaffold.dev/).
* [Hofstadter law](https://fr.wikipedia.org/wiki/Loi_de_Hofstadter), or why David's demo takes so long.
* Trainings on K8s:
  * [Linux Foundation](https://training.linuxfoundation.org/training/introduction-to-kubernetes/).
  * [Udemy](https://www.udemy.com/course/docker-mastery/).
  * [Katacoda](https://katacoda.com/).
  * [Game of pods game](https://kodekloud.com/p/game-of-pods-game).
* As mentionned, [Scaleway doesn't provide anymore arm64 instances](https://www.theregister.co.uk/2020/04/21/scaleway_arm64_cloud_end_of_life/)... That's life.
* You can find the recording of the show on our [Youtube channel](https://www.youtube.com/channel/UC0P65MiWcYcHJ4HgoACbLCQ).
