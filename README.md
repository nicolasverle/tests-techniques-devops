# Tests techniques profils DevOps / Intégration continue

## Pré-requis

* Machine suffisamment véloce pour supporter 3 VMs lancées simultanément avec 2vcpus et 1 Go de RAM
* Accès Internet
* Vagrant >= 1.8.0 + plugin "vagrant-hosts"
* Virtualbox 5
* Git

## Installation

```bash
git clone https://github.com/nicolasverle/tests-techniques-devops.git
cd tests-techniques-devops/Exercice1/<niveau>
vagrant plugin install vagrant-hosts && vagrant up
```