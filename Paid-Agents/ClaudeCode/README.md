# Claude CODE
Os comandos são dados via `terminal` e ele tem poder (se você permitir) sob o seu sistema operacional. Ou seja ela pode:
- Criar;
- Apagar;
- Modificar.
Pastas e arquivos. Por isso devemos tomar cuidado com o `prompt` enviado para o **Claude**.
> --resumo  # ele pega o histórico novamente (após encerrar uma sessão)

## Arquivos
- CLAUDE.md: Ele é como se fosse o `system prompt` inicial do seu agent.

## Modelos:
Para escolher o modelo desejado rode:
> /model
- *Haiku*: Mais leve e mais simples - voltado para coisas triviais;
- *Sonnet*: Um pouco melhor que o *Haiku* - voltado para o dia a dia;
- *Opus*: Problemas complexos - voltado para coisas complexas.

## Comandos
``` bash
/clear  # limpa a conversa
/compact  # limpa a memória
/model  # troca o modelo
/help  # abre os comandos disponiveis
/reward  # ele volta para algum checkpoint anterior do código
```