<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema de Entrega Rápida Pizza-Express&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores
* Gabriel Maciel Figueiredo Constantino da Silva
* Pedro Augusto Rubacow Iotti



# Descrição do projeto

O Grupo MB está trabalhando na ideia de abrir filiais da Pizza-Express localizadas em lugares estratégicos para melhorar a experiência do cliente e reduzir o tempo de entrega da pizza. E atualizando o nosso aplicativo e website, para melhorar a experiência do cliente.


# Análise de requisitos funcionais e não-funcionais
* Requisitos Funcionais:

* Sistema de Atendimento de Pedidos:

O sistema deve permitir que os clientes façam pedidos de pizzas.
Deve ser possível selecionar diferentes tipos de pizzas e personalizá-las com ingredientes.
Os clientes devem ser capazes de fornecer informações de entrega, incluindo endereço e detalhes de contato.
O sistema deve calcular o tempo estimado de entrega com base na localização do cliente e no tráfego atual.
Deve haver uma confirmação de pedido para o cliente após a submissão.

* Localização da Fábrica de Pizzas:

O sistema deve identificar a loja Pizza-Express mais próxima do cliente.
Ele deve considerar a disponibilidade de ingredientes e a capacidade da loja para atender ao pedido.
A localização da fábrica de pizzas deve ser determinada com precisão para minimizar o tempo de entrega.

* Sistema de Software da Fábrica de Pizzas:

Deve haver um sistema de software nas fábricas de pizzas para processar pedidos e preparar pizzas rapidamente.
O sistema deve otimizar o processo de cozimento e montagem das pizzas para atender ao prazo de entrega de 10 a 15 minutos.
Deve haver integração com os sistemas de atendimento de pedidos para receber pedidos e notificar os funcionários da fábrica.
* Investigação de Entrega em Menos de 30 Minutos:

A equipe deve investigar e propor métodos para entregar pizzas em menos de 30 minutos, possivelmente através da criação de lojas especializadas sem espaço de varejo.

------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Requisitos Não Funcionais:

* Tempo de Entrega:

O sistema deve garantir que o tempo de entrega das pizzas seja inferior a 30 minutos, conforme possível.
* Disponibilidade:

O sistema deve estar disponível 24 horas por dia para aceitar pedidos.
* Precisão na Localização:

O sistema de localização da fábrica de pizzas deve ser altamente preciso para garantir a eficiência na entrega.
* Eficiência Operacional:

O sistema de software da fábrica de pizzas deve ser altamente eficiente, minimizando o tempo de preparação e cozimento das pizzas.
* Integração com GPS:

O sistema deve integrar-se a um sistema de GPS para rastrear entregadores e otimizar rotas de entrega.
* Segurança de Dados:

Deve haver medidas de segurança para proteger os dados dos clientes, como informações de pagamento e endereços.
* Escalabilidade:

O sistema deve ser escalável para lidar com um aumento significativo no volume de pedidos durante horários de pico.
* Treinamento de Funcionários:

Os funcionários devem receber treinamento adequado para operar o sistema e preparar pizzas rapidamente.

# Diagrama de casos de uso

![Diagrama de Caso de Uso](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/9de99622-6328-4350-a9b4-b5def5fcc3d2)

# Descrição dos casos de uso


 ![UC01](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/a40b2abd-e872-4a49-baa4-3bb51e335ae2)
 -----------------------------------------------------------------------------------------------------------------------------------------
 ![UC02](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/f728524f-74d9-4a26-b570-3a4627eb5fe8)
 -----------------------------------------------------------------------------------------------------------------------------------------
 ![UC03](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/298a4357-6260-46bf-9570-5dd78b1ca69d)
 -----------------------------------------------------------------------------------------------------------------------------------------
 ![UC04](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/f98dfd1e-0599-4bc4-a273-274157dd57eb)
 -----------------------------------------------------------------------------------------------------------------------------------------
 ![UC05](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/4fb86f28-c9c1-4543-a048-d85daa518525)
 -----------------------------------------------------------------------------------------------------------------------------------------
 ![UC06](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/f323046f-fc8d-40de-9d07-f0303fd8c306)


# Diagrama de sequencia

![diagrama de sequência](https://github.com/gmaciel14/UML-Classroom-FCI/assets/64565201/d78008c6-ce15-485c-bb6f-30982a20ba68)


# Diagrama de classes
![Parte V](https://github.com/gmaciel14/UML-Classroom-FCI/assets/64565201/80872572-d493-40f4-ab08-823a1a3a9f26)

# Diagrama de Componentes

![image](https://github.com/gmaciel14/UML-Classroom-FCI/assets/142851938/fdc1c647-131b-4020-9c03-a5594b0ab34c)


# Decisões de arquitetura

A escolha estratégica da Arquitetura de Microsserviços pelo grupo MB para o desenvolvimento do aplicativo Pizza-Express reflete uma abordagem consciente e detalhada na concepção do sistema. Vamos aprofundar os aspectos dessa decisão:

1. Decomposição Funcional:

A Arquitetura de Microsserviços permite a decomposição das funcionalidades do aplicativo em unidades independentes e especializadas. Cada microsserviço é designado a uma responsabilidade específica, como pedidos, rastreamento, promoções, criando uma abordagem modular.

2. Fluxo de Trabalho como Linha de Montagem:

Dado o fluxo contínuo de operações desde o pedido até a entrega, a analogia com uma linha de montagem destaca a natureza sequencial e interconectada do processo. Cada microsserviço desempenha um papel fundamental nessa linha, contribuindo para uma experiência de usuário coesa e eficiente.

3. Vantagens na Manutenção:

A fragmentação do sistema em microsserviços independentes oferece vantagens significativas na manutenção contínua. Isso permite atualizações específicas em determinadas funcionalidades sem impactar o sistema como um todo, facilitando a implementação de melhorias e correções.

4. Escolha da Linguagem Java:

A decisão de utilizar a linguagem Java é fundamentada na familiaridade e expertise do grupo MB. A linguagem Java é reconhecida por sua robustez, portabilidade e vasto ecossistema, fornecendo uma base sólida para o desenvolvimento de microsserviços.

5. Recursos Abundantes da Linguagem:

Java oferece uma gama abrangente de recursos, desde a orientação a objetos até um coletor de lixo eficiente, além de uma extensa biblioteca padrão. Esses recursos proporcionam ao grupo MB uma plataforma robusta para implementar funcionalidades avançadas e garantir a qualidade do código.

6. Padrões de Comunicação:

No contexto de microsserviços, a escolha de padrões de comunicação é crucial. A utilização de protocolos modernos, como REST ou gRPC, estabelece uma comunicação eficaz e padronizada entre os microsserviços, promovendo uma integração harmoniosa.

7. Monitoramento e Orquestração:

Dada a natureza distribuída dos microsserviços, a implementação de ferramentas de monitoramento e orquestração é essencial. Essas ferramentas garantirão a observabilidade, desempenho e confiabilidade do sistema em sua totalidade.
Em síntese, a escolha da Arquitetura de Microsserviços e a utilização de Java evidenciam uma estratégia cuidadosa do grupo MB. Essa abordagem não apenas atende às necessidades específicas do Pizza-Express, mas também estabelece uma base sólida para a inovação contínua e aprimoramentos futuros.

# Diagrama de implantação

![parteVIII](https://github.com/gmaciel14/UML-Classroom-FCI/assets/64565201/3c0f0ab6-0a0e-4187-a330-59615dfde407)


# Referências

