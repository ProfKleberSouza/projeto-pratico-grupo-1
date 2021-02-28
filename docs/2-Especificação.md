# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na tabela abaixo.

|`Persona`|`Dados` |`Atividade`                 |
|--------------------|------------------------------------|----------------------------------------|
|<img src="../imgs/imagem1.jpg" width="100" height="120">| Joana Silva |Membro da comunidade|
|Idade: 32 anos|Ocupação: Comerciária|Joana trabalha no comércio local e divide o tempo entre o trabalho, os cuidados da casa e da filha de 3 anos.|
|<img src="../imgs/imagem2.jpg" width="100" height="120">| Ana Paula |Profissional de psicologia|
|Idade: 26 anos|Ocupação: Psicóloga|Ana é psicológa voluntária na ONG, ela dedica plantões semanais ao atendimento da comunidade além de cuidar do seu consultório particular. Ana acredita que dedicando parte do seu tempo a uma atividade voluntária tem o poder de melhorar o mundo e aprimorar sua experiência.|
|<img src="../imgs/imagem3.jpg" width="100" height="80">| João Santos |Secretário|
|Idade: 21 anos|Ocupação: Secretário|João Santos é membro da comunidade e secretário na ONG. João fez seu curso superior em letras graças a ações sociais e agora quer dedicar seu tempo ajudando outras pessoas da comunidade.|

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Joana Silva| Realizar inscrição para atendimento psicológico|Receber atendimento psicológico|
|Ana Paula|Realizar cadastro para atendimento psicológico na ONG|Ser incluído no grupo de profissionais que prestam serviços na ONG|
|Ana Paula|Preencher a ficha de atendimento de um paciente/cliente|Armazenar dados históricos dos atendimentos para controle e gestão|
|Ana Paula|Cadastrar horário de atendimento na agenda, cada atendimento tem a duração de 50 minutos, com 10 de intervalo|Registrar a disponibilidade para atendimento|
|João Santos|Criar os agendamentos psicológicos, associando os paciente/cliente com o Profissional de Psicologia que fará o atendimento|Preencher a agenda de atendimentos da semana|

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir. 

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir ao Membro da Comunidade realizar inscrição para atendimento psicológico. | ALTA | 
|RF-002| Permitir ao Profissional de Psicologia realizar cadastro para atendimento psicológico na ONG.    | ALTA |
|RF-003| Permitir ao Profissional de Psicologia preencher a ficha de atendimento de um paciente/cliente. | ALTA |
|RF-004| Permitir ao Profissional de Psicologia cadastrar horário de atendimento na agenda. Cada atendimento tem a duração de 50 minutos, com 10 de intervalo. | ALTA |
|RF-005| Permitir ao Profissional de Profissional de Psicologia excluir horário de atendimento da agenda. A exclusão só é permitida quando um agendamento não está associado. | ALTA |
|RF-006| Permitir a Secretária criar os agendamentos psicológicos, associando os paciente/cliente com o Profissional de Psicologia que fará o atendimento | ALTA |
|RF-007| Permitir a Secretária desmarcar agendamentos psicológicos | ALTA |
|RF-008| Permitir que a Secretária visualize a ficha de inscrição do Membro da Comunidade. | ALTA |
|RF-009| Permitir que a Secretária aprove ou rejeite uma ficha de inscrição de um Membro da Comunidade. Ao aprovar uma ficha, criar um registro efetivo para o Membro da Comunidade. A partir desse momento o Membro da Comunidade poderá ser atendido. | ALTA |
|RF-010| Permitir que a Secretária visualize a ficha de inscrição do Profissional de Psicologia. | ALTA |
|RF-011| Permitir que a Secretária aprove ou rejeite uma ficha de inscrição de um Profissional de Psicologia. Ao aprovar uma ficha, criar um registro efetivo para o Profissional de Psicologia. A partir desse momento o Profissional de Psicologia poderá realizar atendimentos. | ALTA |
|RF-012| Permitir que a Secretária visualize se um Membro da Comunidade está sem agenda. Se tiver agendamento marcado, visualizar em dias o próximo agendamento. | MÉDIA |

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender. 

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet. | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada. |  ALTA | 
|RNF-003| O site deve ter bom nível de contraste entre os elementos da tela em conformidade. |  MÉDIA | 
|RNF-004| O site deve apresentar uma linguagem ubíqua, de acordo com cada tipo de usário. Não deve ser usado termos técnicos para o Membro da Comunidade. Convém usar termos técnicos para os Profissional de Psicologia.  |  ALTA | 
|RNF-005| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |  ALTA | 
|RNF-006| Todo o back-end do sistema será desenvolvido utilizando a linguagem C# |  ALTA |
|RNF-007| Todo o sistema será hospedado na nuvem, dessa forma não haverá a necessidade de servidores físicos. |  ALTA |

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir. 

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 31/05/2021. |
