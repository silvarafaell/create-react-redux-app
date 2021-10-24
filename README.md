# Create React Redux App
### Exemplo de implementação do Redux com Create React App
- Passo a passo em: https://medium.com/reactbrasil/iniciando-com-redux-c14ca7b7dcf
- Iniciando com Redux em 9 passos > Este tutorial será o mais curto e objetivo sobre Redux que você vai encontrar!

Arquitetura do Redux > O Redux é uma implementação criada pelo Dan Abramov da arquitetura Flux, que foi criada pelo Facebook. Ela soluciona o problema de compartilhamento de estados entre componentes, tornando-o unidirecional. A ilustração a seguir descreve tudo

Através da ilustração percebemos que o Redux simplesmente simplifica a evolução de estados de uma aplicação quando há múltiplos estados para controlar e muitos componentes que precisam atualizar ou se inscrever nessa evolução, tirando a responsabilidade de cada componente de guardar o estado e passando para uma centralizada e única Store.

- Para realizar tal fluxo, o Redux depende de 4 partes:

Store: é o container que armazena e centraliza o estado geral da aplicação. Ela é imutável, ou seja, nunca se altera, apenas evolui.

- Podemos ter apenas uma Store por aplicação, ou seja, ela é a Única Fonte de Verdade (Single Source of Truth).

Actions: são fontes de informações que são enviadas da aplicação para a Store. São disparadas pelas Action Creators, que são simples funções que, ao serem executadas, ativam os Reducers.

Reducers: recebem e tratam as informações para que sejam ou não enviadas à Store.

Conexão dos componentes ao Redux: para poderem se inscrever à evolução de estados da Store ou disparar eventos para evoluí-la

Pode não ter ficado muito claro agora, mas não precisa se preocupar, pois com a aplicação será mais fácil de entender. Caso queira informações mais detalhadas, recomendo a leitura da documentação oficial: https://redux.js.org/


