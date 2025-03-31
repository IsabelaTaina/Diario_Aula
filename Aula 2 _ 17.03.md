Nessa aula o professor solicitou um trabalho em equipe com o intuito de compreendermos sobre o termo SDLC, seus ciclos de vida e metodologias usadas.

## Orientações para pesquisa em equipe:
1. Buscar fontes confiáveis para utilizar como base para o desenvolvimento (artigos e sites oficiais);
2. Buscar no mínimo 3 diferentes exemplos de ciclos de vida de desenvolvimento de software (SDLC);
3. Fazer análise dos SDLCs encontrados, verificar as fases e classificar em Estruturação, Execução e Finalização;
4. Citar Metodologias ágeis.

## SDLC - Definição

Software Development Life Cycle (SDLC) consiste em um processo útil nas etapas de desenvolvimento de software, pois visa projetar, desenvolver e tornar o software manutenível para manter sua alta qualidade. Dessa forma, é um processo que utiliza modelos para guiar e estruturar todas as etapas de construção do software, desde a fase inicial até sua entrega.

## Modelos de Ciclo de Vida

### Modelo Cascata

É um dos primeiros modelos, muito utilizado, porém, por ser bem estruturado (linear e sequencial) pode apresentar algumas limitações, considerando que uma fase depende da conclusão da anterior e não é possível retornar caso haja falhas.

#### Fases: 
- **Estruturação**: Envolve o levantamento de requisitos, análise e planejamento. Nessas fases é onde o escopo do projeto é definido e as especificações estabelecidas conforme as necessidades dos clientes.
- **Execução**: No processo de execução do modelo Cascata é realizada a etapa de codificação onde os programadores implementam os códigos para atender o que foi estabelecido na estruturação.
- **Finalização**: Por fim, nessa fase é feito os testes para verificar se todas as solicitações foram atendidas no processo de execução e se o sistema pode ser implantado. Todavia, caso apresente um erro nessa parte final, pode ser impossível ou difícil retornar para a fase anterior porque o modelo ocorre de uma maneira não cíclica e inflexível em relação às mudanças.

#### Problemas:
- **Erro na Fase de Codificação**: A dificuldade em retornar para uma fase anterior atrasa muito o desenvolvimento do software, principalmente se o erro aconteceu no início (levantamento de requisitos) e foi identificado somente no final (codificação e testes). Essa limitação em reparar os erros de forma contínua é um grande problema pois torna o processo mais caro e demorado.
- **Erro na Elicitação**: Se um erro na fase de elicitação ocorrer, seja de interpretação ou comunicação falha, todo o projeto é atingido e comprometido.

### Modelo Incremental:

Diferente do modelo Cascata que segue um sistema concreto, o modelo incremental é iterativo, isso significa que permite mudanças durante os ciclos do projeto e adaptado. 

#### Fases: 

- **Estruturação**: No modelo Incremental a fase envolve a definição do escopo do projeto, identificação dos requisitos e divisão do sistema em incrementos.
Utilizar esse modelo é eficiente porque em cada incremento é entregue uma parte utilizável do produto, nesse sentido o cliente tem acesso a uma versão do software antes mesmo de sua finalização completa. Outro ponto positivo é o fato de o planejamento extrair e priorizar as funcionalidades de maneira mais enxuta para que a primeira entrega seja exata e de valor.
- **Execução**: É a fase onde os incrementos são desenvolvidos e testados.
Diferente do modelo cascata, o código é construído separadamente, reduzindo riscos. Como a entrega é feita em ciclos menores o código se torna mais manutenível, permitindo correções sem acumular erros, consequentemente isso é vantajoso, pois, como o cliente pode manusear uma parte do produto, sugestões podem ser feitas para ajustes mais assertivos. 
- **Finalização**: Todos os incrementos são reunidos para tornar o software completo.
Com os incrementos finalizados é feita a junção para que o sistema funcione de maneira adequada. Apesar de os testes serem feitos individualmente, é preciso verificar se ele funciona como um todo e caso o usuário queira novas funcionalidades, novas versões podem ser adicionadas conforme a exigência sem comprometer o projeto.

#### Problemas: 
A integração dos incrementos podem ser complexos que se não forem bem planejadas podem acarretar em retrabalho.

## Referências
- TUSKR. Software Development Life Cycle (SDLC). Disponível em: [https://tuskr.app/learn/software-development-life-cycle](https://tuskr.app/learn/software-development-life-cycle). Acesso em: 18 mar. 2025.
- UDS. Ciclo de Vida do Software (Web). Disponível em: [https://uds.com.br/blog/ciclo-de-vida-do-software-web/](https://uds.com.br/blog/ciclo-de-vida-do-software-web/). Acesso em: 18 mar. 2025.
- MEDIUM. O Modelo em Espiral de Boehm. Disponível em: [https://medium.com/contexto-delimitado/o-modelo-em-espiral-de-boehm-ed1d85b7df](https://medium.com/contexto-delimitado/o-modelo-em-espiral-de-boehm-ed1d85b7df). Acesso em: 18 mar. 2025.
