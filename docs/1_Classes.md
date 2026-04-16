# Classes

**<span style="color: rgb(200,200,0);">Aluno</span>**
> RF01, RF04, RF05, RF06, RF10
- idAluno
- nome
- cpf
- email
- telefone
- endereco
- rfid
- status

**<span style="color: rgb(200,200,0);">Plano</span>**
> RF01, RF02, RF04
- idPlano
- nome
- tipo
- valor
- ativo

**<span style="color: rgb(200,200,0);">Pagamento</span>**
> RF03, RF04, RF09
- idPagamento
- data
- valor
- formaPagamento
- status

**<span style="color: rgb(200,200,0);">Acesso</span>**
> RF05, RF09
- idAcesso
- dataHora
- autorizado

**<span style="color: rgb(200,200,0);">Aula</span>**
> RF06, RF07, RF09
- idAula
- nome
- horario
- capacidadeMaxima

**<span style="color: rgb(200,200,0);">Agendamento</span>**
> RF06, RF10
- idAgendamento
- dataReserva
- status

**<span style="color: rgb(200,200,0);">Presenca</span>**
> RF07
- idPresenca
- data
- presente

**<span style="color: rgb(200,200,0);">AvaliacaoFisica</span>**
> RF08, RF10
- idAvaliacao
- data
- peso
- imc
- percentualGordura
- observacoes
- anexo

**<span style="color: rgb(200,200,0);">Notificacao</span>**
> RF10
- idNotificacao
- tipo
- dataEnvio
- status
- mensagem

**<span style="color: rgb(200,200,0);">Classe: Instrutor</span>**
> RF07, RF08
- idInstrutor
- nome
- especialidade

**<span style="color: rgb(200,200,0);">Recepcionista</span>**
> RF01, RF03
- idRecepcionista
- nome

**<span style="color: rgb(200,200,0);">Gerente</span>**
> RF02, RF09
- idGerente
- nome