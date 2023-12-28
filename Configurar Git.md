## 🖥️ Comandos para gerar autenticação por SSH:

```
ssh-keygen -t ed25519 -C seuemail@empresa.com
```
``` 
cat id****.pub e coloca no github
```

### Carregar o ssh-agent
```
eval $(ssh-agent -s)
```
```
ssh-add id**** (chave privada)
```