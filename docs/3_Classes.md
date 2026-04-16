# ***Aluno*** - RF01, RF04, RF05, RF06, RF10
## Atributos:
- idAluno
- nome
- cpf
- email
- telefone
- endereco
- rfid
- status
## Métodos
- contratarPlano()
- consultarPlano()
- visualizarAulas()
- agendarAula()
- realizarPagamento()
- cancelarAgendamento()
- consultarNotificacoes()
# ***Plano*** - RF01, RF02, RF04
## Atributos:
- idPlano
- nome
- tipo
- valor
- ativo
## Métodos
- criarPlano()
- editarValorPlano()
- ativarPlano()
- desativarPlano()
# ***Pagamento*** - RF03, RF04, RF09
## Atributos:
- idPagamento
- data
- valor
- formaPagamento
- status
## Métodos
- registrarPagamento()
- gerarPagamentoOnline()
- gerarPagamentoPresencial()
- confirmarPagamento()
- cancelarPagamento()
- estornoPagamento()
- consultarStatus()
# ***Acesso*** - RF05, RF09
## Atributos:
- idAcesso
- dataHora
- autorizado
## Métodos
- validarRFID()
- autorizarAcesso()
- rejeitarAcesso()
- registrarEntrada()
# ***Aula*** - RF06, RF07, RF09
## Atributos:
- idAula
- nome
- horario
- capacidadeMaxima
## Métodos
- listarAulas()
- verificarHorarios()
- verificarVagas()
- reservarVaga()
- liberarVaga()
registrarPresenca()
# ***Agendamento*** - RF06, RF10
## Atributos:
- idAgendamento
- dataReserva
- status
## Métodos
- reservarVaga()
- cancelarReserva()
- confirmarAgendamento()
- cancelarAgendamento()
# ***Presenca*** - RF07
## Atributos:
- idPresenca
- data
- presente
## Métodos
- registrarPresenca()
- consultarPresenca()
# ***AvaliacaoFisica*** - RF08, RF10
## Atributos:
- idAvaliacao
- data
- peso
- imc
- percentualGordura
- observacoes
- anexo
## Métodos
- registrarAvaliacao()
- atualizarAvaliacao()
- anexarDocumento()
- consultarHistorico()
# ***Notificacao*** - RF10
## Atributos:
- idNotificacao
- tipo
- dataEnvio
- status
- mensagem
## Métodos
- enviarNotificacao()
- analizarNotificacao()
- marcarComoLida()
# ***Instrutor*** - RF07, RF08
## Atributos:
- idInstrutor
- nome
- especialidade
## Métodos
- registrarPresenca()
- realizarAvalicaoFisica()
- registrarAvaliacaoFisica()
- consultarAvaliacaoFisica()
# ***Recepcionista*** - RF01, RF03
## Atributos:
- idRecepcionista
- nome
## Métodos 
- cadastrarAluno()
- atualizarDados()
- registrarPagamento()
# ***Gerente*** - RF02, RF09
## Atributos:
- idGerente
- nome
## Métodos
- gerarRelatorio()
- gerenciarPlano()
