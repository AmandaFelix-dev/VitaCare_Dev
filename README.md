
# Comandos do git.


### Clonar a aplicação
```bash
git clone https://github.com/AmandaFelix-dev/VitaCare_Dev.git
```

### Adicionar as alterações no repositório
```bash
git add . 
```

### Salvar alterações
```bash
## MSG sendo sua mensagem
git commit -m "MENSAGEM"
```

### Enviar as alterações para o repositório
```bash
# sendo NAME o q nome da branch q eu quero enviar
git push origin NAME
```
---

### Criar uma branch (Sugestão: criar branch de dev)
```bash
# sendo NAME o q nome q quero para minha branch
git checkout -b NAME
```

### Navegar para uma branch
```bash
# sendo NAME o nome da sua branch
git checkout NAME
```

### Merjar branch
```bash
# sendo NAME o nome da branch que vc quer merjar //vc deve estar na branch q não esta "atualizada"
git merge NAME
```