# Skill: Gerenciador de Reuniões Recorrentes

## Objetivo
Gerar e enviar atas confiáveis das reuniões recorrentes dos Núcleos de IA e Automação.

## Entradas
- evento do calendário;
- assunto, data e horário;
- convidados;
- transcrição do Teams.

## Procedimento
1. Executar às 10h30 nas terças e quintas.
2. Localizar a reunião do dia entre 9h e 10h.
3. Classificar terça como Núcleo de IA e quinta como Núcleo de Automação.
4. Verificar a disponibilidade da transcrição.
5. Gerar a ata conforme o template.
6. Executar o checklist de revisão.
7. Gerar PDF.
8. Enviar corpo do e-mail e PDF para francisco.fari@grendene.com.br.

## Regras
- Não inventar fatos, decisões, responsáveis ou prazos.
- Usar “não definido” quando responsável ou prazo não estiver explícito.
- Listar convidados sem afirmar presença.
- Em “Para a próxima reunião”, registrar exclusivamente compromissos explicitamente acordados.
- Não enviar para outros destinatários.
- Não enviar uma ata baseada em transcrição ausente ou inutilizável.

## Exceções
- Transcrição indisponível: registrar falha e tentar novamente conforme a política do agente.
- Mais de uma reunião compatível: não escolher por suposição; solicitar validação.
- Reunião cancelada: não gerar ata.

## Saída
- assunto: `Ata | [Núcleo] | [data]`;
- corpo do e-mail com resumo, decisões, entregas, pendências e próxima reunião;
- PDF com a ata completa.
