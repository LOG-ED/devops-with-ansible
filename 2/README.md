# Link alle slide del corso

https://docs.google.com/presentation/d/1kYOHZcpNRV2c1ylVdPPN_k4ChYSFxLLX1pjtx8I28As/edit?usp=sharing

# Come utilizzare questo repository 

Generare una chiave SSH:
```
$ ssh-keygen -b 4096 -f key
```

Impostare le variabili relative al proprio tenant nel file `os-openrc.sh` ed eseguire il seguente comando:
```
$ docker run -it --rm -v $(pwd):/ansible matsca09/ansible-bash run.sh
```

