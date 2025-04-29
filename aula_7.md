# Diagrama de Casos de Uso - Revisão

O **Diagrama de Casos de Uso** é um dos tipos de diagramas da **UML** (Unified Modeling Language) e faz parte das fases iniciais do desenvolvimento de software, sendo utilizado para representar as interações entre os usuários (**atores**) e o sistema. Seu objetivo principal é descrever os **casos de uso**, ou seja, as funcionalidades que o sistema oferece para os usuários.

## Tipos de Diagramas UML

Existem dois tipos principais de diagramas na **UML**: **estruturais** e **comportamentais**.

### Diagramas Estruturais
Os diagramas **estruturais** são usados para definir toda a estrutura do sistema, ou seja, **onde** o sistema será implementado e **como** ele será estruturado. Um exemplo clássico de diagrama estrutural é o **Diagrama de Classes**. Esse tipo de diagrama tende a ser mais técnico e complexo, o que torna mais difícil envolver o cliente nesse estágio, pois exige um conhecimento prévio mais profundo sobre a arquitetura e design do sistema.

### Diagramas Comportamentais
Por outro lado, os diagramas **comportamentais** são mais focados nas interações e ações do sistema. Eles são projetados para ser mais acessíveis ao usuário final, facilitando a validação e o entendimento das funcionalidades de maneira mais visual e intuitiva. Esses diagramas são menos técnicos e são úteis para apresentar e validar as funcionalidades do sistema com os stakeholders, incluindo clientes.

O investimento em documentação de diagramas pode variar de acordo com o tamanho da empresa. Empresas menores tendem a focar mais na **produtividade**, o que faz com que a documentação comportamental seja mais frequentemente utilizada, enquanto empresas maiores podem investir mais em diagramas estruturais detalhados.

## Elementos do Diagrama de Casos de Uso

O **Diagrama de Casos de Uso** não é composto apenas por **atores**, mas também por outros elementos que interagem diretamente com o sistema. Esses elementos incluem:

- **Ator**: Representa um usuário ou outra entidade externa que interage com o sistema. Pode ser uma pessoa, outro sistema ou dispositivo.
- **Caso de Uso**: Representa uma funcionalidade ou tarefa que o sistema deve realizar, geralmente do ponto de vista do usuário.
- **Sistema**: Representa o próprio sistema, delimitando os limites do que ele pode fazer e interagir com o ator.
- **Associação**: Conecta os atores aos casos de uso, indicando que eles interagem de alguma forma.
- **Include**: Refere-se a um caso de uso que é sempre invocado como parte de outro caso de uso, indicando uma relação obrigatória.
- **Extend**: Indica uma extensão de um caso de uso, que é acionada de forma condicional.
- **Generalização**: Representa a relação de especialização entre atores ou casos de uso, onde um ator ou caso de uso herda o comportamento de outro.

Cada elemento do **Diagrama de Casos de Uso** tem um papel crucial para representar as interações do sistema de forma clara e compreensível, tanto para os desenvolvedores quanto para os usuários e clientes.
