---
layout: default
---

[Link to another page](./another-page.html).

## Sobre mim

Graduando em Matemática Computacional pela Universidade Federal de Minas Gerais (UFMG). Possui curso técnico em Informática pelo Sistema FIEMG, participação na Olimpíada do Conhecimento e atividades extracurriculares como Iniciação Científica e monitoria. Conhecimentos em programação em C, C++, R, Java e Desenvolvimento Mobile. Atualmente pesquisador júnior na ENACOM na célula de Otimização.

[<img src="assets/img/lattes.png" alt="drawing" style="width:100px;"/>](http://lattes.cnpq.br/0983117412894173) 
  [<img src="assets/img/linkedin.png" alt="drawing" style="width:100px;"/>](https://www.linkedin.com/in/igor-lucas-a92550106)

```python
#Python
from cProfile import Profile
profiler = Profile()

def decorator(fn):
   def inner(self, *args, **kwargs):
      return profiler.runcall(fn, *args, **kwargs) 
   return inner

```