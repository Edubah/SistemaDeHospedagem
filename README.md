# SistemaDeHospedagem
Construirei um sistema de hospedagem de hotel - Curso DIO

Classes:
Pessoa
  Nome: string
  Sobrenome: string

Suite
  TipoSuite: string
  Capacidade: int
  ValorDiaria: decimal

*Reserva
  Hospedes: List<Pessoa>
  Suite: Suite
  DiasReservados: int
  _______________________
  + void CadastrarHospedes(List<Pessoa>hospedes)
  + void CadastrarSuite(Suite suite)
  + in ObterQuantidadeHospedes()
  + decimal CalcularValorDiaria()
