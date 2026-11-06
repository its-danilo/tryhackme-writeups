# Modelo de writeup

Cada sala fica em `Categoria/nome-da-sala/`, com o `README.md` e os prints em `img/`. Depois de escrever, atualizar a tabela da categoria e a contagem no README da raiz.

Antes de publicar:

- Conferir se a sala está marcada como aposentada (retired) no TryHackMe.
- Ocultar com caixa preta flags, senhas, hashes quebrados e cookies de sessão.
- Cortar a barra do sistema no topo dos prints.
- Marcar em vermelho o que importa em cada print.

---

```markdown
# Nome da sala

**Plataforma:** [TryHackMe](https://tryhackme.com/room/nome-da-sala)  
**Dificuldade:** Easy  
**Tema:** o assunto principal da sala  
**Ferramentas:** nmap, gobuster, ...  

## O objetivo

O que a sala pede, em uma ou duas frases.

## Passo a passo

### 1. Primeiro passo

O que eu fiz e o que apareceu.

![Descrição do print](img/01-nome-do-print.png)

### 2. Próximo passo

...

## Por que funcionou

A causa da falha, sem enrolação.

## Como corrigir

- O que o responsável pelo sistema deveria mudar.

## O que eu aprendi

O que levo dessa sala para as próximas.
```
