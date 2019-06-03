# ssh-sever

```
$ ssh-keygen -t rsa -b 4096 -C "" -m PEM
$ docker build . -t ssh-server
$ docker run -it -d -p 10000:22 --name ssh-server ssh-server 
$ ssh -i id_rsa root@localhost -p 10000
```
