# Diagrama Casos de Uso - Cliente

## Introdução
Nesse documento será apresentado o diagrama de casos de uso e suas respectivas especificações referentes ao Cliente.

## Metodologia
Para realização dos casos de uso relacionados ao cliente, foi dividido uma equipe de 3 integrantes, descrito na **Tabela 01**. Inicialmente, foi elaborado um diagrama que apresenta os casos de uso  específicos do cliente, com base nos requisitos e no protótipo elaborado. Em seguida, cada caso de uso foi detalhado por meio de suas respectivas especificações, garantindo uma descrição clara e objetiva das funcionalidades.

### Tabela 01: Integrantes

| Número | Integrante |
|---------|-----------------|
| 1 | [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns) |
| 2 | [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) |
| 3 | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

Na **Tabela 02: Especificações de Caso de Uso** é enumerado todos as especificações de caso de uso produzidas:

### Tabela 02: Especificações de Caso de Uso

| Numero | Caso de uso |
| ------ | -------- |
| 1 | Cadastrar Método de Pagamento |
| 2 | Acompanhar Entrega |
| 3 | Fazer Login |
| 4 | Cadastrar Conta |
| 5 | Visualizar Carrinho |
| 6 | Confirmar Pedido |
| 7 | Realizar Pagamento |
| 8 | Selecionar Método de Pagamento |
| 9 | Visualizar Produtos Disponíveis |
| 10 | Pesquisar Produtos Específicos |
| 11 | Pesquisar Lojas Específicas |
| 12 | Adicionar Produto ao Carrinho |
| 13 | Remover Produto do Carrinho |
| 14 | Editar Pedido |
| 15 | Visualizar Favoritos |
| 16 | Adicionar Produto aos Favoritos |
| 17 | Remover Produto dos Favoritos |
| 18 | Visualizar Histórico de Pedidos |
| 19 | Repetir Pedido |
| 20 | Avaliar Loja |
| 21 | Avaliar Entregador |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |

## Diagrama produzido

![Diagrama](/assets/CasosDeUsoCliente.drawio.png)


## Especificações dos Casos de Uso
A seguir, as tabelas das especificações de cada Caso de Uso do diagrama criado:

### Tabela 03 : Caso de Uso - Cadastrar Método de Pagamento

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Cadastrar Método de Pagamento   |
| Descrição |  Permite ao cliente cadastrar um novo método de pagamento no aplicativo.   |
| Atores |  Cliente   |
| Frequência de uso |   Baixa  |
| Pré-condições |  O cliente deve estar logado no aplicativo.   |
| Fluxo Principal | O cliente acessa o menu de perfil.<br>Clica "Pagamento".Preenche as informações do método de pagamento.<br>O sistema valida as informações.<br>O sistema armazena o método de pagamento com segurança. |
| Fluxos de exceção |  Dados informados invalidos <br> Exibe mensagem de erro. <br> Solicitar nova entrada  |
| Pós condições |  O método de pagamento é armazenado e vinculado à conta do cliente.   |
| Data criação |   27/11/2024  |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### Tabela 04 : Caso de Uso - Acompanhar Entrega

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Acompanhar Entrega   |
| Descrição | Permite ao cliente acompanhar em tempo real o status da entrega do pedido.   |
| Atores |  Cliente   |
| Frequência de uso |   Alta |
| Pré-condições |  O cliente deve ter um pedido em andamento.  |
| Fluxo Principal | O cliente acessa a aba "Pedidos".<br>Seleciona o pedido em andamento.<br>O sistema exibe o status atual da entrega.<br>O cliente visualiza a localização do entregador no mapa. |
| Fluxos de exceção |  Falha na atualização do status<br>Exibir mensagem de erro<br>Solicitar nova tentativa. |
| Pós condições |  O cliente visualiza as informações de entrega atualizadas.   |
| Data criação |   27/11/2024  |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### Tabela 05 : Caso de Uso - Fazer Login

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Fazer Login   |
| Descrição | Permite ao cliente acessar sua conta no aplicativo.   |
| Atores |  Cliente   |
| Frequência de uso |   Alta |
| Pré-condições |   O cliente deve ter uma conta cadastrada.  |
| Fluxo Principal | O cliente acessa a tela de login.<br>Insere e-mail e senha.<br>O sistema autentica as informações.<br>O cliente é redirecionado para a página inicial. |
| Fluxos de exceção |  Senha incorreta<br>Exibir mensagem de erro<br>Solicitar nova entrada.<br><br> Email não cadastrado.<br>Exibir mensagem de erro.<br> Solicitar novo email|
| Pós condições |  O cliente está logado no aplicativo.   |
| Data criação |   27/11/2024  |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### Tabela 06 : Caso de Uso - Cadastrar Conta

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso | Cadastrar Conta   |
| Descrição | Permite ao cliente criar uma nova conta no aplicativo.|
| Atores |  Cliente   |
| Frequência de uso |   Baixa |
| Pré-condições |   Nenhuma |
| Fluxo Principal | O cliente acessa a tela de cadastro.<br>Preenche as informações (nome, e-mail, senha).<br>O sistema valida e armazena os dados.<br>O cliente é redirecionado para a tela inicial. |
| Fluxos de exceção | Senha não atende aos padrões definidos.<br> exibe mensagem de erro. <br> Solicitar nova entrada<br><br>E-mail já cadastrado.<br>Exibir mensagem de erro.<br> Solicitar novo email |
| Pós condições |  Uma nova conta é criada   |
| Data criação |   27/11/2024  |

**Autor**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)


### Tabela 7: Caso de Uso - Visualizar Carrinho

| Campo                | Descrição                                                                 |
|----------------------|---------------------------------------------------------------------------|
| Caso de Uso       | Visualizar Carrinho                                                        |
| Descrição        | O usuário visualiza os itens adicionados ao carrinho de compras, incluindo quantidades, preços e opções de modificar ou remover produtos. |
| Atores            | Usuário, Sistema                                                           |
| Frequência de uso | Alta, pois o carrinho é visualizado sempre que o usuário deseja conferir os produtos antes de finalizar a compra. |
| Pré-condições     | O usuário deve estar autenticado no sistema e ter adicionado produtos ao carrinho. |
| Fluxo Principal   | 1. O usuário acessa a página do carrinho. <br> 2. O sistema exibe os itens do carrinho. <br> 3. O usuário pode visualizar detalhes dos produtos, quantidades e valores totais. |
| Fluxos de Exceção | 1. Se o carrinho estiver vazio, o sistema exibe uma mensagem informando que não há produtos. |
| Pós-condições    | O usuário pode continuar a navegação ou proceder para a confirmação do pedido. |
| Data Criação      | 27/11/2024                                                                 |

**Autor**: [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

### Tabela 8: Caso de Uso - Confirmar Pedido

| Campo                | Descrição                                                                 |
|----------------------|---------------------------------------------------------------------------|
| Caso de Uso          | Confirmar Pedido                                                          |
| Descrição            | O usuário revisa e confirma os detalhes do pedido antes de finalizar a compra. |
| Atores               | Usuário, Sistema                                                           |
| Frequência de uso    | Média, ocorre sempre que o usuário decide finalizar a compra. |
| Pré-condições        | O usuário deve ter produtos no carrinho e estar autenticado no sistema. |
| Fluxo Principal      | 1. O usuário acessa a página de revisão de pedido. <br> 2. O sistema exibe todos os produtos, preços e dados de envio. <br> 3. O usuário confirma os dados e clica em "Confirmar Pedido". |
| Fluxos de Exceção    | Se o carrinho estiver vazio, o sistema impede o avanço e solicita ao usuário adicionar produtos. |
| Pós-condições        | O pedido é registrado no sistema, aguardando o pagamento. |
| Data Criação         | 27/11/2024                                                                 |

**Autor**: [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

### Tabela 9: Caso de Uso - Realizar Pagamento

| Campo                | Descrição                                                                 |
|----------------------|---------------------------------------------------------------------------|
| Caso de Uso          | Realizar Pagamento                                                         |
| Descrição            | O usuário escolhe e confirma o pagamento do pedido, utilizando o método selecionado. |
| Atores               | Usuário, Sistema, Processador de Pagamento                                  |
| Frequência de uso    | Alta, ocorre sempre que um pedido é confirmado e está pronto para ser pago. |
| Pré-condições        | O usuário deve ter confirmado o pedido e ter escolhido um método de pagamento. |
| Fluxo Principal      | 1. O usuário acessa a página de pagamento. <br> 2. O sistema exibe os métodos de pagamento disponíveis. <br> 3. O usuário escolhe o método de pagamento e insere os dados necessários. <br> 4. O sistema valida os dados e processa o pagamento. |
| Fluxos de Exceção    | Se os dados do pagamento forem inválidos, o sistema exibe uma mensagem de erro. <br> 2. Se o pagamento não for aprovado, o sistema solicita uma nova tentativa. |
| Pós-condições        | O pagamento é realizado com sucesso ou o usuário é informado sobre o erro no pagamento. |
| Data Criação         | 27/11/2024                                                                 |

**Autor**: [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

### Tabela 10: Caso de Uso - Selecionar Método de Pagamento

| Campo                | Descrição                                                                 |
|----------------------|---------------------------------------------------------------------------|
| Caso de Uso          | Selecionar Método de Pagamento                                            |
| Descrição            | O usuário escolhe o método de pagamento para finalizar a compra. |
| Atores               | Usuário, Sistema                                                           |
| Frequência de uso    | Alta, ocorre sempre que um usuário precisa efetuar um pagamento. |
| Pré-condições        | O usuário deve ter confirmado o pedido e estar na página de pagamento. |
| Fluxo Principal      | 1. O usuário acessa a página de seleção de método de pagamento. <br> 2. O sistema exibe as opções de pagamento disponíveis (cartão de crédito, boleto, etc.). <br> 3. O usuário escolhe o método desejado e prossegue para inserir os dados. |
| Fluxos de Exceção    | Se o método de pagamento não estiver disponível, o sistema exibe uma mensagem de erro. |
| Pós-condições        | O usuário escolhe o método de pagamento e pode prosseguir com o processo de pagamento. |
| Data Criação         | 27/11/2024                                                                 |

**Autor**: [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

### Tabela 11: Caso de Uso - Visualizar Produtos Disponíveis

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Visualizar Produtos Disponíveis  |
| Descrição |  Permite ao cliente visualizar a lista de produtos disponíveis para compra no aplicativo.   |
| Atores |  Cliente   |
| Frequência de uso |   Alta  |
| Pré-condições |   O cliente deve acessar o aplicativo e estar logado.  |
| Fluxo Principal |  1. O cliente acessa a tela inicial para visualizar os produtos disponíveis. <br> 2. O sistema exibe os produtos organizados por categoria. <br> 3. O cliente pode navegar pelas categorias ou visualizar todos os produtos. <br> 4.O cliente seleciona um produto para ver mais detalhes.  |
| Fluxos de exceção |  -  |
| Pós condições |  O cliente visualiza a lista de produtos e pode selecionar itens para comprar.  |
| Data criação | 27/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 12: Caso de Uso - Pesquisar Produtos Específicos

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Pesquisar Produtos Específicos  |
| Descrição |  Permite ao cliente buscar produtos específicos  |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |   O cliente deve acessar o aplicativo e estar logado.  |
| Fluxo Principal |  1. O cliente acessa a tela de busca. <br> 2. O cliente pesquisa pelo produto desejado. <br> 3. O sistema exibe os produtos correspondentes a busca. |
| Fluxos de exceção |  Não há produtos que correspondam aos critérios de busca. |
| Pós condições |  O cliente visualiza os produtos que correspondem a pesquisa realizada.  |
| Data criação | 27/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 13: Caso de Uso - Pesquisar Lojas Específicas

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Pesquisar Lojas Específicas  |
| Descrição | Permite ao cliente buscar lojas específicas no aplicativo.  |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |   O cliente deve acessar o aplicativo e estar logado.  |
| Fluxo Principal |  1. O cliente acessa a tela de busca. <br> 2. Digita o nome da loja ou aplica filtros como "Perto de você". <br> 3. O sistema exibe a lista de lojas que correspondem aos critérios inseridos. |
| Fluxos de exceção |  Nenhuma loja encontrada. |
| Pós condições |  O cliente localiza a loja de interesse.  |
| Data criação | 27/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 14: Caso de Uso - Adicionar Produto ao Carrinho

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Adicionar Produto ao Carrinho  |
| Descrição | Permite ao cliente adicionar um produto selecionado ao carrinho de compras. |
| Atores |  Cliente   |
| Frequência de uso |   Alta  |
| Pré-condições |   O cliente deve acessar o aplicativo e estar logado.  |
| Fluxo Principal |  1. O cliente seleciona um produto na tela inicial. <br> 2. Clica no botão "Adicionar ao carrinho". <br> 3. O sistema adiciona o produto ao carrinho e atualiza o contador de itens. |
| Fluxos de exceção |  Produto indisponível. |
| Pós condições |  O produto é adicionado ao carrinho com sucesso.  |
| Data criação | 27/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 15: Caso de Uso - Remover Produto do Carrinho

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Remover Produto do Carrinho  |
| Descrição | Permite ao cliente remover um produto do carrinho de compras. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. <br> O cliente deve ter pelo menos um produto no carrinho.  |
| Fluxo Principal |  1. O cliente acessa a tela do carrinho. <br> 2. Seleciona o produto que deseja remover. <br> 3. Clica no botão "Remover". <br> 4. O sistema remove o produto e atualiza o carrinho. |
| Fluxos de exceção |  Falha ao remover o produto. |
| Pós condições |  O produto é removido do carrinho com sucesso.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 16: Caso de Uso - Editar Pedido

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Editar Pedido  |
| Descrição | Permite ao cliente editar um pedido do carrinho antes de confirmar a compra, ajustando itens, quantidades ou removendo produtos. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. <br> O cliente deve ter itens no carrinho.  |
| Fluxo Principal |  1. O cliente acessa o carrinho de compras. <br> 2. O sistema exibe todos os itens presentes no carrinho. <br> 3. O cliente altera a quantidade de um ou mais itens ou remove itens do carrinho. <br> 4. O sistema recalcula o valor total do pedido. <br> 5. O cliente confirma as modificações e prossegue para a confirmação do pedido. |
| Fluxos de exceção |  O sistema não consegue atualizar o valor total do pedido. |
| Pós condições |  O pedido é atualizado com as modificações feitas pelo cliente.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 17: Caso de Uso - Visualizar Favoritos

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Visualizar Favoritos  |
| Descrição | Permite ao cliente visualizar a lista de produtos que foram adicionados aos favoritos. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. |
| Fluxo Principal |  1. O cliente acessa a opção "Favoritos" no menu principal. <br> 2. O sistema exibe a lista de produtos marcados como favoritos. <br> 3. O cliente pode selecionar um item para ver mais detalhes. |
| Fluxos de exceção |   Não há itens favoritos. |
| Pós condições |  O cliente visualiza a lista de itens favoritos.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 18: Caso de Uso - Adicionar Produto aos Favoritos

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Adicionar Produto aos Favoritos  |
| Descrição | Permite ao cliente adicionar produtos à lista de favoritos para acesso rápido no futuro. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. |
| Fluxo Principal |  1. O cliente seleciona um produto na tela inicial. <br> 2. O sistema exibe os detalhes desse produto. <br> 3. O cliente clica no ícone de coração. <br> 4. O sistema adiciona o produto à lista de favoritos. |
| Fluxos de exceção |   Falha ao adicionar o produto. |
| Pós condições |  O produto é salvo na lista de favoritos.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 19: Caso de Uso - Remover Produto dos Favoritos

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Remover Produto dos Favoritos  |
| Descrição | Permite ao cliente remover produtos da lista de favoritos. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. <br> O cliente deve ter pelo menos um produto na lista de favoritos. |
| Fluxo Principal |  1. O cliente acessa a tela de favoritos. <br> 2. Seleciona o produto que deseja remover. <br> 3. O cliente clica no ícone de coração. <br> 4. O sistema remove o produto da lista de favoritos. |
| Fluxos de exceção |   Falha ao remover o produto. |
| Pós condições |  O produto é removido da lista de favoritos.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 20: Caso de Uso - Visualizar Histórico de Pedidos

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Visualizar Histórico de Pedidos  |
| Descrição | Permite ao cliente visualizar o histórico de pedidos realizados no aplicativo. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. <br> O cliente deve ter realizado algum pedido no aplicativo. |
| Fluxo Principal |  1. O cliente acessa a tela de "Meus pedidos". <br> 2. O sistema exibe uma lista de pedidos realizados anteriormente pelo cliente. <br> 3. O cliente seleciona um pedido para visualizar os detalhes. |
| Fluxos de exceção |   Não há pedidos no histórico. |
| Pós condições |  O cliente visualiza o histórico de pedidos realizados.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 21: Caso de Uso - Repetir Pedido

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Repetir Pedido  |
| Descrição | Permite ao cliente realizar novamente um pedido previamente feito, utilizando as mesmas informações de produtos, endereço e método de pagamento. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O cliente deve acessar o aplicativo e estar logado. <br> O cliente deve ter pelo menos um pedido no histórico. |
| Fluxo Principal |  1. O cliente acessa a tela de "Meus pedidos". <br> 2. Seleciona o pedido que deseja repetir. <br> 3. Clica na opção "Repetir Pedido". <br> 4. O sistema carrega os itens do pedido no carrinho. <br> 5. O cliente revisa o pedido e confirma. |
| Fluxos de exceção |    Produto indisponível. |
| Pós condições |  O pedido é confirmado e enviado para processamento.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 22: Caso de Uso - Avaliar Loja

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Avaliar Loja  |
| Descrição | Permite ao cliente avaliar uma loja após a conclusão de um pedido. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O pedido deve ter sido entregue. |
| Fluxo Principal |  1. O cliente acessa a tela de "Meus pedidos". <br> 2. Seleciona a opção "Avaliar Loja". <br> 3. Insere uma nota e comentário sobre a experiência. <br> 4. Confirma a avaliação. <br> 5. O sistema registra a avaliação. |
| Fluxos de exceção |    Falha ao registrar a avaliação. |
| Pós condições |  A avaliação é registrada.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

### Tabela 23: Caso de Uso - Avaliar Entregador

| Campo | Descrição |
| ------ | ------ |
| Caso de Uso |  Avaliar Entregador  |
| Descrição | Permite ao cliente avaliar o entregador que realizou a entrega do pedido. |
| Atores |  Cliente   |
| Frequência de uso |   Média  |
| Pré-condições |    O pedido deve ter sido entregue. |
| Fluxo Principal |  1. O cliente acessa a tela de "Meus pedidos". <br> 2. Seleciona a opção "Avaliar Entregador". <br> 3. Insere uma nota e comentário sobre a entrega. <br> 4. Confirma a avaliação. <br> 5. O sistema registra a avaliação. |
| Fluxos de exceção |    Falha ao registrar a avaliação. |
| Pós condições |  A avaliação é registrada.  |
| Data criação | 28/11/2024 |

**Autor**: [Raquel Ferreira Andrade](https://github.com/raquel-andrade)

## Referências

1. Caso de Uso – Include, Extend e Generalização, ATÉ O MOMENTO. Disponível em: https://www.ateomomento.com.br/caso-de-uso-include-extend-e-generalizacao/. Acessado em 27 de novembro de 2024.

## Histórico de Versão

| Versão | Data da alteração | Comentário | Autor(es) | Revisor(es) | Data de revisão |
|--------|-----------|-----------|-----------|-------------|-------------|
| 1.0 | 27/11/2024 | Criação do documento e adição do diagrama dos casos de uso | [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | [Lucas Martins Gabriel](https://github.com/martinsglucas) | 29/11/2024 |
| 1.1 | 27/11/2024 | Adição das especificações de casos de uso | [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | [Lucas Martins Gabriel](https://github.com/martinsglucas) | 29/11/2024 |
| 1.2 | 28/11/2024 | Adição das especificações de casos de uso 13 a 21 | [Raquel Ferreira Andrade](https://github.com/raquel-andrade) | [Lucas Martins Gabriel](https://github.com/martinsglucas) | 29/11/2024 |
