# Docker

### Docker kısa açıklamalar
* Anlatımın girişinde bahsettiğim bilgilerin geneline bu paylaşımdan ulaşabilirsiniz. 
[Docker Bölüm 1: Nedir, Nasıl Çalışır, Nerede Kullanılır?](https://gokhansengun.com/docker-nedir-nasil-calisir-nerede-kullanilir/)
* DockerHub üzerinden gerekli kurulum yapıldıktan sonra doğru kurulum olup olmadığını `docker version` komutuyla görebilirsiniz.

* [Docker official page](https://www.docker.com/)
* [Dockerhub](https://hub.docker.com/)
* [Docker Dokümanlar](https://docs.docker.com/)

* DevOps ve Docker ile ilgili konularda Gökhan Şengün'ün kişisel bloguna, medium sayfasına ve youtube üzerindeki sayfalarına erişebileceğiniz sayfa. [Gökhan Şengün Blog'u](https://gokhansengun.com/)

* Tarık Güney - Senior Software Engineering Manager at Motorola Solutions. [Tarık Güney'in Docker Anlattığı youtube playlist'i](https://www.youtube.com/watch?v=isbsABbZghs&list=PL_Z0TaFYSF3LTfMIRjPUlVoUipQA0JlL2)

### DockerHub'dan indirilen hello-world imajı ayağa kaldırma
`docker search hello-world`
`docker pull hello-world`
`docker images`
`docker run hello-world`
`docker ps`

### ubuntu imajından container ayağa kaldırma
* docker conteiner'ı ayağa kaldırma.
`docker run ubuntu`
`docker ps`
`docker run -it ubuntu`

> * ubuntu içi bash işlemleri.
> `ls`
`cd home`
`nano first-try.py`
`apt-get install nano`
`apt-get install`
`apt-get update`
`apt-get install nano`
`nano first-try.py`
> * nano text editörü işlemleri (işlem bittikten sonra ctrl + x ile çıkılacak)
   >> print "bu bir ubuntu containerinde calisan python scriptidir. 
>
> `python first-try.py`
`apt-get install python`
`python first-try.py`
`exit`

### Infrastructure as a Code ve Dockerfile

* Docker Bölüm 2: Yeni bir Docker Image'ı Nasıl Hazırlanır? [Gökhan Şengün Blog'u 2](https://gokhansengun.com/docker-yeni-image-hazirlama/)