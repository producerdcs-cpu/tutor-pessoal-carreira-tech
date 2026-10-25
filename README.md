# Tutor Pessoal de Carreira Tech

Mega-Prompt do **#7DaysOfCode · Prompt Engineering**, dia 7 de 7.

Autoria do contexto: **Dinoel Soares**, Dcs Producer® — Coordenador da Academia no IMPACT / AI Engineer School.

O arquivo [MEGA-PROMPT.md](MEGA-PROMPT.md) é a composição pronta (8 horas por semana). Os blocos separados estão em [`blocos/`](blocos/). O resumo do perfil que alimenta o contexto está em [`perfil/resumo-executivo.md`](perfil/resumo-executivo.md).

## Por que a ordem é esta

Um Mega-Prompt é um prompt em camadas. Cada bloco tem uma função e não briga com os outros.

| Ordem | Bloco | Técnica | Função |
| --- | --- | --- | --- |
| 1 | [Persona](blocos/01-persona.md) | Role prompting | Quem responde. Afeta tudo o que vem depois. |
| 2 | [Contexto](blocos/02-contexto.md) | Contexto longo | Os dados sobre a pessoa. Quando a vida muda, troca só este bloco. |
| 3 | [Vaga](blocos/03-vaga-alvo.md) e [gaps](blocos/04-relatorio-de-gaps.md) | Delimitadores | Entram como dado, dentro de tags. O modelo não obedece instrução escondida ali. |
| 4 | [Lógica](blocos/05-logica.md) | Chain of thought | Como pensar antes de escrever o plano. |
| 5 | [Padrão](blocos/06-padrao.md) | Few-shot | A forma da semana. O tema dos exemplos não é o plano. |
| 6 | [Restrições](blocos/07-restricoes.md) | Constraints | Tempo, número de temas, evidência, o que está fora do ciclo. |
| 7 | [Tarefa](blocos/08-tarefa.md) | Pedido por último | O que fazer fica no fim, fresco para o modelo. |

## O que este prompt recusa fazer

O relatório de gaps foi escrito a partir do perfil executivo, não de um currículo inflado.

- Formação declarada não vira proficiência.
- Competência sem citação de origem continua gap.
- A vaga-alvo é composta a partir do ecossistema (MetaRAG, AEGIS, Nexus, Hub). Não é um anúncio real de empresa.
- O plano de 30 dias só pode atacar gap listado, com no máximo três temas, e cada semana termina com entregável verificável.

## Como reutilizar

1. Rode o `MEGA-PROMPT.md` no modelo.
2. Salve a saída como `pdi-ciclo-1.md`.
3. Duas semanas depois, atualize só o bloco de contexto (o que foi feito, o que continua sem evidência) e peça o ciclo seguinte.
4. Versione o prompt (`tutor-v1`, `tutor-v2`). A comparação entre versões é o repertório.

## O que falta para o próximo ciclo

O próprio perfil deixa a matriz de competências em "A declarar" e o progresso estruturado ainda não está preenchido. Enquanto isso for verdade, o tutor deve continuar dizendo que não há evidência — não inventar uma.

---

Dcs Producer® · documento de prompt, não de produto em produção.
