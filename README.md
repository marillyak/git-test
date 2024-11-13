# Relatório de Atividades com Git

## Relatório 1 - Commit de Arquivos Individuais

*Objetivo*: Criar três arquivos (notas.txt, resumo.md e tarefa.txt), adicionar conteúdo e fazer commits separados para cada um.

*Descrição*:
- Criei e adicionei cada arquivo ao Git, comitei cada um separadamente com mensagens explicativas.
- Cometi um erro em um dos commits e precisei desfazer e refazer usando git reset --soft HEAD~1. Depois de algumas tentativas, consegui finalizar todos os commits corretamente.

---

## Relatório 2 - Modificação e Reversão de Alterações

*Objetivo*: Criar e comitar o arquivo experimento.txt, fazer alterações e usar git restore e git reset --hard para reverter mudanças.

*Descrição*:
- Criei e comitei experimento.txt, fiz uma alteração e reverti com git restore.
- Fiz outra modificação, comitei e reverti o commit com git reset --hard.
- Todos os passos foram concluídos sem problemas.

---

## Relatório 3 - Branches e Merge com Conflitos

*Objetivo*: Criar uma branch melhorias, adicionar novidades.md e realizar um merge com a branch main, resolvendo conflitos.

*Descrição*:
- Inicializei o repositório, criei o arquivo principal.txt na branch main e comitei.
- Criei a branch melhorias, adicionei novidades.md e comitei.
- Ao tentar git checkout main, recebi um erro dizendo que main não existia. Resolvi renomeando master para main com git branch -m master main.
- Fiz o merge de melhorias em main e resolvi o conflito em principal.txt, finalizando com sucesso.

---

*Resumo Geral*: Concluí todas as atividades após resolver alguns problemas com commits e configuração de branches. Aprendi a usar comandos como git reset, git restore e a resolver conflitos de merge.