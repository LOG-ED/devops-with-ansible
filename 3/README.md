# Link alle slide del corso

https://docs.google.com/presentation/d/1t-SMaYgR7g6o0I1if68hM322bBpqnPnRDPxcCP7sR_Y/edit?usp=sharing

# Come utilizzare questo repository 

Generare una chiave SSH:
```
$ ssh-keygen -b 4096 -f key
```

Impostare le variabili relative al proprio tenant nel file `os-openrc.sh` ed eseguire il seguente comando:
```
$ docker run -it --rm -v $(pwd):/ansible jsecchiero/ansible-bash run.sh
```

