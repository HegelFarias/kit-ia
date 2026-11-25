# Meu Kit de IA

Kit adaptado para automatizar a geração de atas das reuniões recorrentes dos Núcleos de IA e Automação usando um agente do Microsoft 365 Copilot.

**Fluxo:** localizar reunião → aguardar transcrição → gerar ata → validar → gerar PDF → enviar e-mail.

## Minha Entrega

### Minha Tarefa Real
Automatizar o fechamento de duas reuniões recorrentes no Microsoft Teams:
- terça-feira, das 9h às 10h: Núcleo de IA;
- quinta-feira, das 9h às 10h: Núcleo de Automação.

Às 10h30, o agente deve localizar a reunião correspondente e a transcrição, gerar uma ata, produzir um PDF e enviar o resultado exclusivamente para francisco.fari@grendene.com.br.

### Meus Atalhos
1. Gerar uma ata estruturada com resumo, discussões, decisões, entregas, pendências e compromissos explicitamente acordados para a próxima reunião.
2. Validar a ata antes do envio, impedindo inferências sobre responsáveis, prazos, decisões ou compromissos.

### Minha Delegação
**Objetivo:** transformar a transcrição em uma ata confiável e enviá-la por e-mail com PDF anexo.

**Contexto:** as reuniões acontecem no Teams, possuem transcrição e são recorrentes. A ata deve listar os convidados do evento, ainda que não tenham participado efetivamente.

**Recursos:** evento do calendário, metadados da reunião, lista de convidados e transcrição do Teams.

**Limites:** não inventar informações; não tratar convidados como participantes; não incluir como compromisso futuro algo que não tenha sido explicitamente acordado; enviar somente para o endereço definido.

**Sucesso:** ata gerada com rastreabilidade, PDF legível, corpo de e-mail objetivo e envio para francisco.fari@grendene.com.br.

### O Plano da IA
1. Executar às 10h30 nas terças e quintas.
2. Identificar a reunião correta pelo dia, horário e assunto.
3. Confirmar que a transcrição está disponível.
4. Extrair discussões, decisões, entregas, responsáveis, prazos e pendências.
5. Aplicar o checklist de qualidade.
6. Gerar o PDF.
7. Enviar o e-mail somente para o destinatário autorizado.
8. Em caso de transcrição indisponível, não gerar conteúdo presumido e registrar a falha.

### O Resultado
A saída será composta pelo corpo do e-mail e por um PDF com a ata completa. A seção **Para a próxima reunião** conterá somente compromissos explicitamente acordados.

### Como Foi para Você
A automação reduz a revisão manual de transcrições e cria um histórico consistente de decisões, entregas e pendências, mantendo regras claras de validação e segurança.
