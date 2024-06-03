# <p align=center>Sistema de Academia</p>
# 👐 Integrantes

Vitor Siedschlag Hervella

Luan da Costa Silva

# 💻 Sobre
O proposito deste sistema é facilitar a vida tanto dos administradores quanto dos alunos, para simplificar a gestão das atividades da academia, desde o cadastro de alunos até o acompanhamento do progresso físico. Para os administradores, ferramentas para gerenciar alunos, agendar aulas, controlar o acesso e administrar as finanças. Para os alunos, permissão para que reservem aulas, acompanhem seu progresso e se comuniquem com os instrutores. Meu objetivo é tornar a experiência na academia mais eficiente, motivadora e gratificante para todos os envolvidos.

# ⚙️ Ferramentas e Tecnologias utilizadas:
- [x] GitHub

- [x] PlantUML

- [x] Draw.io

# 📚 Conceitos utilizados
- [x] Design Patterns - *Singleton*, *Strategy*

- [x] Padrão Arquitetural - *Camadas*, *MVC*, *Clean arquitetura*

- [x] C4Model

- [ ] Persitencia de Dados

# <p align=center>Arquitetura de Software - AWS</p>
## 🗺️ Diagramas C4 Model
### Diagrama de contexto
![DiagramaContexto](https://github.com/VitorHervella/C4Model/assets/36939208/f090dd87-a7bf-4959-a090-f6c8f39f9228)
### Diagrama de Containers
![DiagramaContainers](https://github.com/VitorHervella/C4Model/assets/36939208/b2781f20-ea3f-4d41-89e4-482fb5ff0d44)
### Diagrama de Componentes
![DiagramaComponente](https://github.com/VitorHervella/C4Model/assets/36939208/704fddab-05bd-4105-b172-88cdf71a61f8)
### Diagrama de Código
![DiagramaCodigo](https://github.com/VitorHervella/C4Model/assets/36939208/963fcc02-103c-427b-a1db-2e2bb3a5b109)

## 📐 Padrões de Projeto
![PadroesProjetoC4](https://github.com/VitorHervella/C4Model/assets/36939208/4bf8eba5-c2ba-478f-b8fd-b9ef031ce3a4)

*Padrão Singleton:* Aqui, temos as classes Database e Logger, ambas implementadas como singletons. Isso significa que elas têm uma única instância em toda a execução do programa. A classe Database é responsável pela interação com o banco de dados, enquanto a classe Logger é responsável pelo registro de mensagens. Ambas garantem que apenas uma instância exista e podem ser acessadas globalmente.

*Padrão Strategy:* Este padrão é utilizado para representar diferentes estratégias de treino para os alunos. A interface TreinoStrategy define um método executarTreino(), que é implementado pelas classes TreinoIniciante e TreinoAvancado. A classe Aluno possui um atributo treinoStrategy que é definido com uma das estratégias e pode realizar o treino chamando o método realizarTreino(). Isso permite que diferentes tipos de treino sejam facilmente alternados e adicionados ao sistema.

## 🔨 Padrão Arquitetural 
### Camadas
![Camadas](https://github.com/VitorHervella/C4Model/assets/36939208/713f562d-89fb-4857-a63f-48264d9fe6b0)

*Camadas:* As principais camadas são Interface do Usuário (UI), Aplicação, Domínio e Infraestrutura. A UI contém controladores que interagem com os casos de uso na camada de aplicação. Os casos de uso operam no domínio, acessando entidades, repositórios e serviços. A infraestrutura fornece implementações concretas para o banco de dados, APIs externas e outros frameworks.
### MVC
![MVC](https://github.com/VitorHervella/C4Model/assets/36939208/de479ca8-d7b2-4f51-964c-b36278f9f2e9)

*MVC:* O padrão Model-View-Controller separa a aplicação em três componentes principais. O modelo (Model) inclui as entidades, repositórios e serviços que representam a lógica de negócios. A visualização (View) inclui a interface do usuário (UI). O controlador (Controller) lida com as interações do usuário, manipulando as solicitações e atualizando o modelo conforme necessário.
### Clean Arquitetura
![CleanArquitetural](https://github.com/VitorHervella/C4Model/assets/36939208/8667a859-00f9-45f5-bdf6-256723e897d0)

*Clean Architecture:* Esta arquitetura enfatiza a separação de preocupações e a independência das camadas internas. As entidades representam objetos de negócios, os casos de uso contêm a lógica de negócios, as interfaces incluem os controladores e a UI, e o framework & drivers contêm implementações de infraestrutura.

#
# <p align=center>👏 Obrigado!</p>


