# 2. Fluxo de Trabalho com Git

O fluxo básico com Git pode ser representado por estes passos:

1. Clonar o repositório:
```bash
git clone https://github.com/usuario/repositorio.git
````

2. Criar uma nova branch para suas mudanças:

```bash
git checkout -b minha-feature
```

3. Fazer modificações e commitar:

```bash
git add .
git commit -m "Descreve claramente o que foi feito"
```

4. Enviar para o GitHub:

```bash
git push origin minha-feature
```

5. Criar um Pull Request

---

## Dica

Mantenha sua branch `main` ou `master` sempre atualizada com:

```bash
git pull origin main
```
