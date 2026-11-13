# ATEC-CISEG

Repositório do exercício de Git da ATEC (CISEG).

## Exercício 1

> No repositório criado, cria um ficheiro `mudame.txt` e conseguir editar o mesmo via CentOS CLI, PC de casa e de uma máquina qualquer com GUI.

| Máquina | Ambiente | Como foi editado |
|---|---|---|
| PC de casa | Windows | VS Code / terminal |
| CentOS Stream 10 | CLI | `nano` + `git` |
| Ubuntu | GUI | `gedit` + `git` |

### Fluxo usado em cada máquina

```bash
git pull
# editar mudame.txt
git add mudame.txt
git commit -m "Editado no <máquina>"
git push
```
