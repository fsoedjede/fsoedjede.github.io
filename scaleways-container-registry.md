Scaleways

1. Créer un "namespace"

2. Créer un jeton secret

Lien: https://console.scaleway.com/project/credentials

Nom: `CPHLabs: Accès pour le container registry`

SCW_ACCESS_KEY: `SCWH72VVMFTTBT389H58`

SCW_SECRET_TOKEN: `26dcfd41-7515-41b5-bd84-491ea8de26f9`

4. Tester la connexion

```shell
docker login rg.fr-par.scw.cloud/cphlabs -u nologin -p $SCW_SECRET_TOKEN
docker pull ubuntu:latest
docker tag ubuntu:latest rg.fr-par.scw.cloud/cphlabs/ubuntu:latest
docker push rg.fr-par.scw.cloud/cphlabs/ubuntu:latest
```


https://registry.docker.soedjede.net/v2/cphlabs/docpross/tags/list


docker pull registry.docker.soedjede.net/cphlabs/docpross:latest
docker tag registry.docker.soedjede.net/cphlabs/docpross:latest rg.fr-par.scw.cloud/cphlabs/docpross:latest
docker push rg.fr-par.scw.cloud/cphlabs/docpross:latest

docker pull registry.docker.soedjede.net/cphlabs/docpross:1.5.1
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.5.1 rg.fr-par.scw.cloud/cphlabs/docpross:1.5.1
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.5.1
docker pull registry.docker.soedjede.net/cphlabs/docpross:1.4.2
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.4.2 rg.fr-par.scw.cloud/cphlabs/docpross:1.4.2
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.4.2

docker pull registry.docker.soedjede.net/cphlabs/docpross:1.0.0
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.0.0 rg.fr-par.scw.cloud/cphlabs/docpross:1.0.0
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.0.0
docker pull registry.docker.soedjede.net/cphlabs/docpross:1.0.20
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.0.20 rg.fr-par.scw.cloud/cphlabs/docpross:1.0.20
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.0.20
docker pull registry.docker.soedjede.net/cphlabs/docpross:1.1.2
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.1.2 rg.fr-par.scw.cloud/cphlabs/docpross:1.1.2
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.1.2
docker pull registry.docker.soedjede.net/cphlabs/docpross:1.2.12
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.2.12 rg.fr-par.scw.cloud/cphlabs/docpross:1.2.12
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.2.12
docker pull registry.docker.soedjede.net/cphlabs/docpross:1.3.23
docker tag registry.docker.soedjede.net/cphlabs/docpross:1.3.23 rg.fr-par.scw.cloud/cphlabs/docpross:1.3.23
docker push rg.fr-par.scw.cloud/cphlabs/docpross:1.3.23
