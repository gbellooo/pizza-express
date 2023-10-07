<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;PIZZA EXPRESS&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Análise de requisitos funcionais e não-funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de Componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)


# Autores

* Aluno 1 - Gabriel Bello - 32312822
* Aluno 2 - Lucas Lopes - 42228476


# Descrição do projeto

*&lt;Identificação das necessidades: A equipe realizará uma análise minuciosa das necessidades da Pizza-Express. Isso incluirá a investigação da perda de rendimento de vendas e o impacto da concorrência, especialmente de um concorrente que oferece entregas em 30 minutos. / Definição de objetivos do projeto: Os objetivos serão estabelecidos de forma clara e mensurável. Isso pode envolver metas como reduzir o tempo de entrega para 30 minutos ou menos, melhorar a eficiência operacional e aumentar as vendas. / Avaliação de tecnologias: Será realizada uma pesquisa para identificar e avaliar as tecnologias disponíveis que podem ser usadas para desenvolver as duas partes do sistema de software necessário para o projeto. / Escopo do projeto: O escopo do projeto será definido com base nas necessidades identificadas, abrangendo duas áreas principais: atendimento de pedidos e localização de fábricas de pizza mais próximas, bem como operações na fábrica de pizzas. / Plano de projeto: Um plano de projeto completo será desenvolvido, abordando as etapas específicas, prazos, alocação de recursos e orçamento necessários para a execução bem-sucedida do projeto. / Desenvolvimento de software: A equipe de desenvolvimento de software se concentrará em criar as soluções necessárias para atender às necessidades da Pizza-Express. Isso envolverá o desenvolvimento de um sistema de pedidos eficiente e um sistema de rastreamento de localização. / Testes e qualidade: Serão conduzidos testes rigorosos para garantir que o software funcione conforme o esperado. Testes de desempenho serão particularmente importantes para atender ao objetivo de entrega em menos de 30 minutos. / Treinamento e implantação: A equipe garantirá que os funcionários da Pizza-Express sejam treinados no uso do novo software e que as mudanças operacionais necessárias sejam implementadas de maneira eficaz. / Monitoramento e melhoria contínua: Será estabelecido um sistema de monitoramento para acompanhar o desempenho do sistema após a implementação. As melhorias serão feitas conforme necessário para atender às metas estabelecidas. / Colaboração e profissionalismo: Manter uma comunicação eficaz entre todas as partes envolvidas no projeto, incluindo a equipe da Pizza-Express, a equipe de desenvolvimento de software e outros colaboradores. Garantir um ambiente de trabalho profissional e colaborativo para alcançar com sucesso os objetivos do projeto.&gt;*

# Análise de requisitos funcionais e não-funcionais
Requisitos Funcionais:
Atendimento de Pedidos:
O sistema deve permitir que os clientes selecionem pizzas do menu, personalizem seus pedidos, especifiquem detalhes (como tamanho e coberturas) e forneçam informações de entrega.
Gestão de Pedidos:
O sistema deve receber, registrar e gerenciar todos os pedidos, incluindo a confirmação de disponibilidade de ingredientes.
Deve permitir a revisão e confirmação do pedido pelos funcionários.
Localização de Fábricas de Pizza:
O sistema deve identificar a loja Pizza-Express mais próxima do cliente com base em sua localização.
Deve selecionar a fábrica de pizza adequada para processar o pedido.
Preparação de Pizza:
O sistema deve auxiliar os funcionários na preparação das pizzas, incluindo a lista de ingredientes e instruções de montagem.
Entrega de Pizza:
O sistema deve coordenar as entregas, fornecendo instruções aos entregadores sobre a rota mais eficiente.
Deve monitorar o tempo de entrega e notificar os clientes sobre o status de suas entregas.
Gerenciamento de Clientes:
O sistema deve manter perfis de clientes com histórico de pedidos e informações de contato.
Requisitos Não-Funcionais:
Tempo de Entrega:
O sistema deve garantir a entrega de pizzas em menos de 30 minutos a partir da entrada do pedido.
Eficiência Operacional:
O sistema deve otimizar as operações da Pizza-Express, reduzindo o tempo de preparo das pizzas e minimizando os custos operacionais.
Escalabilidade:
O sistema deve ser escalável para lidar com um aumento significativo no volume de pedidos, especialmente durante horários de pico.
Usabilidade:
O software deve ser de fácil utilização tanto para os funcionários quanto para os clientes, garantindo uma experiência amigável.
Segurança de Dados:
O sistema deve garantir a segurança e a privacidade dos dados dos clientes, de acordo com as regulamentações de privacidade.
Disponibilidade:
O sistema deve estar disponível 24/7 para processar pedidos a qualquer momento, inclusive durante a noite e nos fins de semana.
Desempenho:
O sistema deve ser capaz de lidar com um grande número de transações simultâneas de forma eficiente, garantindo tempos de resposta rápidos.
Monitoramento e Análise:
O sistema deve oferecer recursos de monitoramento e análise de desempenho para avaliar e melhorar continuamente a eficiência e a qualidade do serviço.
Integração:
O sistema deve ser capaz de integrar-se a sistemas de pagamento online, sistemas de rastreamento de localização e outros sistemas de TI relevantes.
Conformidade com Regulamentações:
O sistema deve estar em conformidade com todas as regulamentações e padrões aplicáveis, especialmente em relação à segurança de alimentos e privacidade de dados

# Diagrama de casos de uso
Atores:
Cliente
Funcionário da Pizza-Express
Sistema de Pedido
Sistema de Localização
Casos de Uso:
Realizar Pedido
Ator Principal: Cliente
Resumo: O cliente faz um pedido de pizza através do sistema.
Receber Pedido
Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário recebe o pedido do cliente e confirma os detalhes.
Localizar Fábrica de Pizza
Ator Principal: Sistema de Localização
Resumo: O sistema de localização identifica a fábrica de pizza mais próxima do cliente.
Preparar Pizza
Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário da Pizza-Express prepara a pizza no local de produção.
Entregar Pizza
Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário entrega a pizza ao cliente.
Gerenciar Pedidos
Ator Principal: Sistema de Pedido
Resumo: O sistema de pedido gerencia o fluxo de pedidos, incluindo a alocação de pedidos às fábricas de pizza e o rastreamento do tempo de entrega.
Monitorar Desempenho
Ator Principal: Gerente de Sistemas de Informação (Elonn Muske)
Resumo: Elonn Muske monitora o desempenho do sistema e coleta dados para avaliação e melhoria contínua.
Manter Dados do Cliente
Ator Principal: Sistema de Pedido
Resumo: O sistema de pedido mantém os dados do cliente, incluindo histórico de pedidos e informações de contato.
Acessar Menu
Ator Principal: Cliente
Resumo: O cliente pode visualizar o menu de opções disponíveis para fazer seu pedido.

# Descrição dos casos de uso
Atores:

Cliente: O cliente que deseja fazer um pedido de pizza da Pizza-Express.

Funcionário da Pizza-Express: Um funcionário da Pizza-Express que recebe, prepara e entrega os pedidos dos clientes.

Sistema de Pedido: O sistema de software responsável por receber, registrar e gerenciar os pedidos dos clientes.

Sistema de Localização: O sistema de software que auxilia na identificação da fábrica de pizza mais próxima do cliente.

Casos de Uso:

Realizar Pedido

Ator Principal: Cliente
Resumo: Neste caso de uso, o cliente faz um pedido de pizza através do sistema. O cliente pode selecionar pizzas do menu, personalizar o pedido com detalhes específicos (como tamanho e coberturas) e fornecer informações de entrega, como endereço e número de telefone. Após a finalização, o pedido é encaminhado para processamento.
Receber Pedido

Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário da Pizza-Express recebe o pedido do cliente e confirma os detalhes, verificando a disponibilidade de ingredientes e, se necessário, entra em contato com o cliente para esclarecimentos adicionais. O pedido é preparado para processamento.
Localizar Fábrica de Pizza

Ator Principal: Sistema de Localização
Resumo: Neste caso de uso, o sistema de localização identifica a fábrica de pizza Pizza-Express mais próxima do cliente com base em sua localização. Isso é fundamental para determinar onde o pedido será preparado e entregue com eficiência.
Preparar Pizza

Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário da Pizza-Express prepara a pizza de acordo com as especificações do pedido, seguindo as instruções e utilizando ingredientes disponíveis no estoque da fábrica de pizza.
Entregar Pizza

Ator Principal: Funcionário da Pizza-Express
Resumo: O funcionário da Pizza-Express entrega a pizza ao cliente no menor tempo possível, seguindo as instruções de entrega fornecidas pelo sistema.
Gerenciar Pedidos

Ator Principal: Sistema de Pedido
Resumo: O sistema de pedido é responsável por gerenciar o fluxo de pedidos, incluindo a alocação de pedidos às fábricas de pizza apropriadas com base na localização do cliente. Ele também rastreia o tempo de entrega para garantir que o serviço atenda aos padrões estabelecidos.
Monitorar Desempenho

Ator Principal: Gerente de Sistemas de Informação (Elonn Muske)
Resumo: O gerente de sistemas de informação, Elonn Muske, monitora o desempenho do sistema e coleta dados para avaliação e melhoria contínua. Este caso de uso envolve a análise de métricas de desempenho e relatórios para garantir a eficiência do sistema.
Manter Dados do Cliente

Ator Principal: Sistema de Pedido
Resumo: O sistema de pedido é responsável por manter os dados do cliente, incluindo histórico de pedidos e informações de contato. Isso permite um atendimento personalizado e a possibilidade de reordenação rápida.
Acessar Menu

Ator Principal: Cliente
Resumo: O cliente pode visualizar o menu de opções disponíveis para fazer seu pedido. Isso envolve a exibição de opções de pizzas disponíveis e seus respectivos preços.

# Diagrama de sequencia
Cliente                      Sistema de Pedido
  |                                |
  | Pedido de Pizza               |
  | ----------------------------> |
  |                                |
  |                                |
  |                                |
  | Confirmação do Pedido         |
  | <---------------------------- |
  |                                |
  |                                |
  |                                |
  | Preparação da Pizza           |
  | ----------------------------> |
  |                                |
  |                                |
  |                                |
  | Entrega da Pizza              |
  | <---------------------------- |
  |                                |

Neste diagrama de sequência:

O cliente inicia a interação fazendo um "Pedido de Pizza" através da interface do aplicativo ou site.

O "Pedido de Pizza" é transmitido para o "Sistema de Pedido" que registra o pedido.

O "Sistema de Pedido" confirma o pedido, verificando os detalhes e a disponibilidade.

Após a confirmação, o "Sistema de Pedido" inicia a "Preparação da Pizza".

Paralelamente, o "Sistema de Pedido" verifica a "Localização da Fábrica de Pizza" mais próxima para o processamento.

A "Preparação da Pizza" é realizada pelos funcionários da Pizza-Express na fábrica de pizza apropriada.

Após a preparação, a "Entrega da Pizza" é organizada, incluindo a atribuição de um entregador e o cálculo da rota.

A pizza é entregue ao cliente, e o processo é concluído.

# Diagrama de classes
Diagrama de Classes - Pizza-Express:

Classe Cliente:

Atributos:
Nome
Endereço
Número de telefone
Histórico de pedidos
Operações:
Fazer Pedido()
Cancelar Pedido()
Consultar Histórico()
Classe Pedido:

Atributos:
Número de pedido
Detalhes do pedido (lista de pizzas, tamanho, coberturas)
Informações de entrega (endereço, horário de entrega)
Status do pedido (pendente, em preparação, entregue)
Operações:
Calcular Custo()
Confirmar Pedido()
Atualizar Status()
Classe FuncionárioPizzaExpress:

Atributos:
Nome
Cargo
Número de identificação
Operações:
Receber Pedido()
Preparar Pizza()
Entregar Pizza()
Classe SistemaPedido:

Atributos:
Lista de Pedidos
Dados do Cliente (histórico, informações de contato)
Operações:
Registrar Pedido()
Atualizar Pedido()
Gerenciar Pedidos()
Classe SistemaLocalizacao:

Atributos:
Mapa de Localização das Fábricas de Pizza
Operações:
Identificar Fábrica de Pizza Mais Próxima()
Classe SistemaMonitoramento:

Atributos:
Métricas de Desempenho
Registros de Entrega
Operações:
Monitorar Desempenho()
Coletar Dados()
Classe FábricaPizzaExpress:

Atributos:
Localização
Lista de Ingredientes Disponíveis
Operações:
Preparar Pizza()
Entregar Pizza()

# Diagrama de Componentes
Diagrama de Componentes - Pizza-Express:

Cliente Interface (Interface do Cliente):

Descrição: Representa a interface de usuário que os clientes usam para fazer pedidos de pizza.
Componentes:
Interface de Pedido: Permite que os clientes escolham pizzas, personalizem seus pedidos e forneçam informações de entrega.
Interface de Histórico: Permite que os clientes consultem seu histórico de pedidos.
Funcionário Interface (Interface do Funcionário):

Descrição: Representa a interface usada pelos funcionários da Pizza-Express para receber e processar pedidos.
Componentes:
Interface de Recebimento de Pedido: Permite que os funcionários recebam pedidos dos clientes e confirmem os detalhes.
Interface de Preparação de Pizza: Ajuda os funcionários a preparar as pizzas com base nos pedidos.
Interface de Entrega de Pizza: Facilita a entrega das pizzas aos clientes.
Sistema de Pedido (Componente de Software):

Descrição: Gerencia todos os aspectos relacionados aos pedidos, incluindo registro, confirmação e atualização de status.
Interfaces:
Interface de Pedidos: Fornece métodos para registrar, confirmar e atualizar pedidos.
Sistema de Localização (Componente de Software):

Descrição: Auxilia na identificação da fábrica de pizza mais próxima do cliente com base em sua localização.
Interfaces:
Interface de Localização: Fornece métodos para identificar a fábrica de pizza mais próxima.
Sistema de Monitoramento (Componente de Software):

Descrição: Monitora o desempenho do sistema, coleta dados e gera relatórios para avaliação e melhoria contínua.
Interfaces:
Interface de Monitoramento: Oferece métodos para coletar métricas de desempenho e gerar relatórios.
Fábrica de Pizza (Componente Físico):

Descrição: Representa uma fábrica física da Pizza-Express, onde as pizzas são preparadas e entregues.
Componentes:
Equipamento de Preparação: Inclui fornos, utensílios e ingredientes.
Entregadores: Pessoal responsável pela entrega das pizzas.
Banco de Dados (Componente de Infraestrutura):

Descrição: Armazena informações sobre pedidos, clientes e histórico de pedidos.
Interfaces:
Interface de Banco de Dados: Fornece métodos para acessar e atualizar dados no banco de dados.
Aplicação Web/Servidor (Componente de Infraestrutura):

Descrição: Hospeda a aplicação web usada pelos clientes para fazer pedidos e pelos funcionários para gerenciar pedidos.
Interfaces:
Interface de Comunicação: Fornece serviços web para comunicação entre clientes e funcionários.

# Decisões de arquitetura
1. Hospedagem em Nuvem:

Decisão: Optar por hospedar a infraestrutura do projeto na nuvem, utilizando um provedor de serviços em nuvem confiável, como Amazon Web Services (AWS), Microsoft Azure ou Google Cloud Platform (GCP).
Justificativa: A hospedagem em nuvem oferece escalabilidade sob demanda, alta disponibilidade e facilidade de gerenciamento, permitindo que o sistema Pizza-Express se adapte rapidamente às mudanças na demanda e mantenha um alto nível de disponibilidade.
2. Arquitetura de Microsserviços:

Decisão: Implementar a arquitetura de microsserviços para desacoplar os diferentes componentes do sistema, como pedidos, localização, monitoramento e entrega.
Justificativa: A arquitetura de microsserviços permite que cada componente seja desenvolvido, implantado e dimensionado de forma independente. Isso facilita a manutenção, o isolamento de falhas e a escalabilidade horizontal de partes específicas do sistema.
3. Balanceamento de Carga:

Decisão: Utilizar um balanceador de carga para distribuir o tráfego de entrada entre as instâncias dos microsserviços.
Justificativa: O balanceamento de carga ajuda a distribuir uniformemente a carga de trabalho, garantindo que o sistema permaneça responsivo e resiliente, mesmo durante picos de tráfego.
4. Contêineres e Orquestração:

Decisão: Utilizar contêineres (por exemplo, Docker) e uma plataforma de orquestração de contêineres (como Kubernetes) para empacotar, distribuir e gerenciar microsserviços.
Justificativa: Contêineres oferecem isolamento e portabilidade, enquanto a orquestração simplifica a implantação, a escalabilidade e a recuperação de falhas dos microsserviços.
5. Banco de Dados Escalável:

Decisão: Implementar um banco de dados escalável, como um banco de dados SQL ou NoSQL, dependendo dos requisitos específicos de armazenamento de dados.
Justificativa: Um banco de dados escalável é essencial para lidar com grandes volumes de dados de pedidos, históricos de clientes e outras informações críticas para o sistema.
6. Monitoramento e Registro:

Decisão: Incorporar ferramentas de monitoramento e registro, como Prometheus e Grafana, para monitorar o desempenho do sistema, rastrear erros e coletar métricas operacionais.
Justificativa: O monitoramento contínuo é essencial para identificar problemas de desempenho e garantir a qualidade do serviço.
7. Segurança em Camadas:

Decisão: Implementar medidas de segurança em várias camadas, incluindo proteção de rede, autenticação de usuário, autorização de acesso e criptografia de dados.
Justificativa: A segurança é uma prioridade, especialmente quando se lida com informações sensíveis dos clientes, como dados de pagamento e detalhes de entrega.
8. Backup e Recuperação de Dados:

Decisão: Estabelecer políticas e procedimentos de backup regulares e testes de recuperação de desastres para garantir a proteção dos dados críticos do sistema.
Justificativa: A perda de dados pode ser catastrófica; portanto, um plano de backup e recuperação sólido é essencial.
Essas decisões de arquitetura de infraestrutura visam garantir que o sistema Pizza-Express seja escalável, resiliente, seguro e eficiente em termos de custos. A escolha das tecnologias e práticas específicas dependerá das necessidades do projeto e dos recursos disponíveis.

# Diagrama de implantação
Diagrama de Implantação - Pizza-Express:

Neste diagrama de implantação textual, vamos representar os principais componentes de hardware e software no projeto Pizza-Express e como eles se relacionam:

                  +------------------+
                  |  Cliente (App)  |
                  +------------------+
                          |
                          |
                  +------------------+
                  |    Servidor      |
                  | (Web/Application)|
                  +------------------+
                          |
                          |
                  +------------------+
                  | Banco de Dados   |
                  +------------------+
                          |
                          |
                  +------------------+
                  |   Sistema de    |
                  |   Localização    |
                  +------------------+
                          |
                          |
                  +------------------+
                  |  Sistema de     |
                  |  Monitoramento  |
                  +------------------+
                          |
                          |
                  +------------------+
                  | Fábricas de Pizza|
                  +------------------+

Neste diagrama:

O "Cliente (App)" representa o aplicativo usado pelos clientes para fazer pedidos.
O "Servidor (Web/Application)" é onde a aplicação web do Pizza-Express é hospedada, incluindo a lógica de negócios e as interfaces do cliente e do funcionário.
O "Banco de Dados" armazena informações sobre pedidos, clientes, histórico de pedidos e outros dados relevantes.
O "Sistema de Localização" auxilia na identificação da fábrica de pizza mais próxima com base na localização do cliente.
O "Sistema de Monitoramento" é responsável por monitorar o desempenho do sistema e coletar métricas operacionais.
As "Fábricas de Pizza" são locais físicos onde as pizzas são preparadas e entregues pelos funcionários.