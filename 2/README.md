# Come utilizzare questo repository 

Generare una chiave SSH:
```
$ ssh-keygen -b 4096 -f key
```

Impostare le variabili relative al proprio tenant nel file `os-openrc.sh` ed eseguire il seguente comando:
```
$ docker run -it --rm -v $(pwd):/ansible matsca09/ansible-bash run.sh
```

