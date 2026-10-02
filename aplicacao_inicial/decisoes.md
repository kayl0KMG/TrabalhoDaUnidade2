# Diário de Decisões e Conflitos

## Merge das features em develop — 01/10/2026

Resolvido por: Kayla (Aluna A), com decisões tomadas pela equipe.
Ordem dos merges: primeiro feature/tema-ajustavel, depois feature/incremento-rename.

### 1. aplicacao_inicial/app.js

- **Linhas:** função de contagem e eventos dos botões + e –.
- **Causa:** as duas features alteraram o incremento para 2 em 2; a feature do B renomeou setCount para updateCount e a do C manteve setCount e também mudou o decremento para –2.
- **Alternativas:** manter a versão do B, a do C, ou misturar.
- **Decisão:** mantida a versão do B no contador (updateCount, +2 e –1). O toggleTheme ampliado do C (alterando --card e --border) foi mantido, pois não conflitou.
- **Motivo:** o rename da função era responsabilidade do Aluno B.

### 2. aplicacao_inicial/styles.css

- **Linha:** variável --primary.
- **Causa:** B mudou para verde (#00e723) e C para vermelho (#f63b3b).
- **Alternativas:** verde ou vermelho.
- **Decisão:** vermelho (versão do C).
- **Motivo:** preferência da equipe.

### 3. aplicacao_inicial/index.html

- **Linhas:** <title> e <h1>.
- **Causa:** B mudou o título para incluir "Equipe B" e C para "Modo Escuro".
- **Alternativas:** "Equipe B" ou "Modo Escuro".
- **Decisão:** "Modo Escuro" (versão do C).
- **Motivo:** coerência com o hotfix previsto, que trata do título ao voltar para o modo claro.
