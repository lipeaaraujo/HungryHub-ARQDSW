# Cenários Produzidos

## Introdução 
Neste documento serão apresentados os cenários produzidos. Na tabela 1, 2 , 3 estão enumerados os cenários de Cliente, Entregador e Loja respectivamente.

### Tabela 01: Cenários do Cliente

| ID | Titulo |
|------|---------|
| CN1 | Cliente cadastra uma conta |
| CN2 | Cliente faz login |
| CN3 | Cliente pesquisa um produto |
| CN4 | Cliente verifica produtos de uma loja |
| CN5 | Cliente adiciona item aos favoritos |
| CN6 | Cliente remove item dos favoritos |
| CN7 | Cliente solicita suporte |
| CN8 | Cliente adiciona produto ao carrinho |
| CN9 | Cliente remove produto ao carrinho | 
| CN10 | Cliente finaliza compra |
| CN11 | Cliente acompanha pedido |
| CN12 | Cliente acessa histórico de pedidos |
| CN13 | Cliente avalia entregador | 
| CN14 | Cliente avalia loja |

<center>

**Autores**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Davi Gonçalves Akegawa Pierre](https://github.com/DaviPierre), [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva), [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

</center>

### Tabela 02: Cenários do Entregador

| ID | Titulo |
|------|---------|
| CN15 | Entregador faz login |
| CN16 | Entregador atualiza disponibilidade|
| CN17 | Entregador recebe notificação de um novo pedido |
| CN18 | Entregador aceita ou recusa pedido|
| CN19 | Entregador verifica rota de entrega no mapa |
| CN20 | Entregador atualiza status do pedido (coletado/entregue)|
| CN21 | Entregador contata cliente via chat |
| CN22 | Entregador atualiza informações pessoais |
| CN23 | Entregador verifica histórico de entregas |

<center>

**Autores**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Davi Gonçalves Akegawa Pierre](https://github.com/DaviPierre), [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva), [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

</center>

### Tabela 03: Cenários de Loja

| ID | Titulo |
|------|---------|
| CN24 | Lojista cadastra sua loja |
| CN25 | Lojista gerencia cardápio |
| CN26 | Lojista acompanha pedidos |
| CN27 |  Lojista cadastra entregador |
| CN28 |  Lojista configura promoções |

<center>

**Autores**: [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Davi Gonçalves Akegawa Pierre](https://github.com/DaviPierre), [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva), [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)

</center>

## Cenários para Cliente

### CN01: Cliente cadastra uma conta

#### Tabela 04: CN01

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente cadastra uma conta |
| Objetivo | Cliente deseja cadastrar uma conta no app HungryHub |
| Contexto | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Aplicativo instalado e acesso a internet  |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja cadastrar uma conta. <br> Abre o aplicativo HungryHub. <br> Cliente acessa a tela de registro. <br> Cliente preenche o formulário com dados válidos. <br> A conta é criada e o cliente é direcionado a tela inicial.|
| Restrição | Cliente precisa fornecer informações válidas |
| Exceção | Perder a conexão a internet antes de concluir o cadastro |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)


### CN2: Cliente faz login

#### Tabela 05: CN02

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente faz login |
| Objetivo | Cliente deseja fazer login em uma conta já cadastrada |
| Contexto | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja cadastrar uma conta. <br> Abre o aplicativo HungryHub. <br> Cliente acessa a tela de login. <br> Cliente preenche o formulário com dados válidos. <br>Cliente é direcionado a tela inicial.|
| Restrição | Cliente precisa fornecer informações válidas |
| Exceção | Perder a conexão a internet antes de concluir o login |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN3: Cliente pesquisa um produto

#### Tabela 06: CN03

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente pesquisa um produto |
| Objetivo | Cliente deseja pesquisar um produto especifico |
| Contexto | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente clica na barra de pesquisa. <br> Cliente digita o que esta procurando. <br> Cliente é redirecionado para uma tela com produtos relacionados a pesquisa feita|
| Restrição | Pesquisar algo relacionado ao tipo de serviço disponibilizado no aplicativo |
| Exceção | Perder a conexão a internet antes de concluir a pesquisa|

### CN4: Cliente verifica produtos de uma loja

#### Tabela 07: CN04

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente verifica produtos de uma loja |
| Objetivo | Cliente deseja verificar os produtos fornecidos por determinada loja |
| Contexto | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente clica em um restaurante para visualizar os detalhes de seus produtos, incluindo preço e descrição. |
| Restrição | A loja deve ter produtos cadastrados |
| Exceção | Perder a conexão a internet antes de concluir o processo|

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN5: Cliente adiciona item aos favoritos

#### Tabela 08: CN05

| Elemento   | Descrição  |
|------------|-------------------------------------|
| **Título** | Cliente adiciona item aos favoritos     |
| **Objetivo** | Cliente deseja adicionar um item aos favoritos     |
| **Contexto** | Local: Qualquer lugar com acesso à internet. ou trabalho <br> Pré-condições: Aplicativo instalado, acesso à internet e conta cadastrada |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub  |
| **Episódios** |  Pesquisa produtos. <br> Cliente seleciona um produto desejado. <br> Cliente clica no icone de coração.  |
| **Restrição** | Item não pode já estar favoritado|
| **Exceção** | Cliente perde conexão à internet durante o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN6: Cliente remove item dos favoritos

#### Tabela 09: CN06

| Elemento   | Descrição  |
|------------|-------------------------------------|
| **Título** | Cliente remove item dos favoritos     |
| **Objetivo** | Cliente deseja remover um item dos favoritos     |
| **Contexto** | Local: Qualquer lugar com acesso à internet. ou trabalho <br> Pré-condições: Aplicativo instalado, acesso à internet e conta cadastrada |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub  |
| **Episódios** | Cliente clica no icone de coração na parte inferior da tela. <br> Cliente é redirecionado para tela de favoritos. <br> Cliente clica no icone de coração localizado ao lado do item que deseja remover.  |
| **Restrição** | Item deve estar favoritado|
| **Exceção** | Cliente perde conexão à internet durante o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN7: Cliente solicita suporte

#### Tabela 10: CN07

| Elemento   | Descrição            |
|------------|-----------------------------------|
| **Título** | Cliente solicita suporte                                                 |
| **Objetivo** | Permitir que o cliente entre em contato com o suporte pelo aplicativo    |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub                                                     |
| **Episódios** |  Cliente clica no perfil. <br> clica no ícone de ajuda perfil. <br> Escolhe uma opção e ver as orientaões relacionadas ao problema |
| **Restrição** | Horário de atendimento do suporte                                       |
| **Exceção** | Cliente não consegue se comunicar devido a problemas no chat             |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### CN8: Cliente adiciona produto ao carrinho

#### Tabela 11: CN08

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente adiciona produto ao carrinho |
|**Objetivo** | Cliente deseja adicionar um produto ao carrinho  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente clica em um restaurante para visualizar os detalhes de seus produtos, incluindo preço e descrição. <br> Cliente escolhe um produto e clica no botão "Adicionar ao carrinho" |
| **Restrição** | Produto não pode já estar no carrinho.   |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN9: Cliente remove produto do carrinho

#### Tabela 12: CN09

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente remove produto do carrinho |
|**Objetivo** | Cliente deseja remover um produto do carrinho  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente clica no icone de carrinho no canto superior direito <br> Cliente clica no item que deseja remover. <br> Cliente é redirecionado para uma tela que especifica o pedido. <br> Cliente clica no botão "Remover do carrinho" |
| **Restrição** | Cliente deve ter algum produto no carrinho   |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN10: Cliente finaliza compra

#### Tabela 13: CN10

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente finaliza compra |
|**Objetivo** | Cliente deseja finalizar a compra  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente clica no icone de carrinho no canto superior direito <br> Cliente clica no botão "Confirmar pedido" <br> Cliente adiciona o endereço de entrega e o metodo de pagamento. <br> Cliente clica no bptão "Confirmar pagamento" |
| **Restrição** | Cliente deve possuir dinheiro suficiente para realizar o pagamento    |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Bruno Araújo](https://github.com/brunocva)

### CN11: Cliente acompanha pedido

#### Tabela 14: CN11

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente acompanha pedido |
|**Objetivo** | Cliente deseja acompanhar um pedido  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Clica no ícone de pedidos na tab bar <br> O cliente é direcionado para a tela de detalhes do pedido, onde ele visualiza o histórico e status de cada pedido <br> Clica no pedido desejado e é levado para a tela de detalhes da entrega e do pedido |
| **Restrição** | Cliente deve ter realizado um pedido    |
| **Exceção** | Perder a conexão a internet enquanto acompanha o pedido |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN12: Cliente acessa histórico de pedidos

#### Tabela 15: CN12

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente acessa histórico de pedidos |
|**Objetivo** | Cliente deseja acessar todos os pedidos ja fez no aplicativo.  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente clica no icone de registro na parte central da tab bar. <br> Cliente é direcionado para a tela de "Meus pedidos" |
| **Restrição** | Cliente já deve ter realizado um pedido    |
| **Exceção** | Perder a conexão a internet durante o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN13: Cliente avalia entregador

#### Tabela 16: CN13

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente avalia entregador |
|**Objetivo** | Cliente deseja avaliar um entregador  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente acessa histórico de pedidos.<br> Cliente seleciona um dos pedidos. <br> Cliente é direcionado para tela "Detalhes pedido". <br> Cliente clica em "Avaliar entregador". <br> Cliente preenche os dados solicitados e clica no botão "Confirmar".   |
| **Restrição** | Pedido deve estar no historico de pedidos    |
| **Exceção** | Perder a conexão a internet enquanto acompanha o pedido |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN14: Cliente avalia loja

#### Tabela 17: CN14

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente avalia loja |
|**Objetivo** | Cliente deseja avaliar uma loja |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente acessa histórico de pedidos.<br> Cliente seleciona um dos pedidos. <br> Cliente é direcionado para tela "Detalhes pedido". <br> Cliente clica em "Avaliar loja". <br> Cliente preenche os dados solicitados e clica no botão "Confirmar".   |
| **Restrição** | Pedido deve estar no historico de pedidos    |
| **Exceção** | Perder a conexão a internet enquanto acompanha o pedido |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

## Cenarios para Entregador

### CN15: Entregador faz login

#### Tabela 18: CN15

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador faz login |  
| **Objetivo**    | O entregador deseja acessar sua conta no aplicativo HungryHub Driver. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada no aplicativo, app instalado e atualizado, e acesso à internet. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   |  O entregador abre o aplicativo HungryHub Driver. <br> O entregador acessa a tela de login. <br> Insere suas credenciais (e-mail e senha). <br> O aplicativo valida as informações. <br> O entregador é direcionado à tela inicial do app, que exibe seu status atual e pedidos disponíveis. |   
| **Restrição**   | O entregador precisa fornecer credenciais válidas para acessar sua conta. |  
| **Exceção**     | Credenciais inválidas: Exibe mensagem de erro e solicita nova tentativa. <br> Perda de conexão com a internet impede o login. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)

### CN16: Entregador atualiza disponibilidade  

#### Tabela 19: CN16

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador atualiza disponibilidade |  
| **Objetivo**    | O entregador deseja alterar seu status de disponibilidade para receber pedidos. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada, aplicativo atualizado, e entregador autenticado. |  
| **Recursos**    | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   |  O entregador clica no botão de status (online/offline). <br> O status é atualizado e uma confirmação é exibida na tela. |  
| **Restrição**   | O aplicativo deve estar conectado à internet e sincronizado com o servidor. |  
| **Exceção**     | Perda de conexão com a internet impede a atualização do status. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)

### CN17: Entregador recebe notificação de um novo pedido  

#### Tabela 20: CN17

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador recebe notificação de um novo pedido |  
| **Objetivo**    | O entregador é informado sobre um novo pedido disponível. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Entregador logado no aplicativo e com status definido como "online". |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O aplicativo recebe informações de um novo pedido. <br> Uma notificação é exibida na tela do entregador. <br> Detalhes do pedido (endereço de coleta e entrega) são exibidos. |  
| **Restrição**   | O entregador precisa estar com o aplicativo em funcionamento e conectado à internet. |  
| **Exceção**     | Notificação atrasada ou não recebida devido à falha na conexão. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)  

### CN18: Entregador aceita ou recusa pedido  

#### Tabela 21: CN18

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador aceita ou recusa pedido |  
| **Objetivo**    | O entregador decide se aceita ou recusa um novo pedido. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Notificação de novo pedido recebida. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador visualiza os detalhes do pedido na notificação. <br> O aplicativo exibe opções de "Aceitar" ou "Recusar". <br> O entregador seleciona uma das opções. <br> O sistema registra a decisão e atualiza o status do pedido. |  
| **Restrição**   | Decisão precisa ser tomada dentro do tempo limite configurado pelo sistema. |  
| **Exceção**     | Pedido expirado devido à demora na decisão. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)  

### CN19: Entregador verifica rota de entrega no mapa  

#### Tabela 22: CN19

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador verifica rota de entrega no mapa |  
| **Objetivo**    | O entregador deseja visualizar a rota para coleta ou entrega de um pedido. |  
| **Contexto**    | Local: Durante o percurso. <br> Pré-condições: Pedido aceito e conexão ativa. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel com GPS. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador acessa os detalhes do pedido no aplicativo. <br> Clica na opção "Visualizar rota". <br> O aplicativo exibe a rota no mapa, destacando os pontos de coleta e entrega. |  
| **Restrição**   | GPS e conexão com a internet devem estar ativos. |  
| **Exceção**     | Rotas podem não ser carregadas devido à falha no GPS ou na conexão. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)  

### CN20: Entregador atualiza status do pedido (coletado/entregue)  

#### Tabela 23: CN20

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador atualiza status do pedido (coletado/entregue) |  
| **Objetivo**    | O entregador informa o progresso do pedido no aplicativo. |  
| **Contexto**    | Local: Durante o percurso. <br> Pré-condições: Pedido em andamento e conexão ativa. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador acessa os detalhes do pedido no aplicativo. <br> Seleciona "Pedido coletado" após retirar o item. <br> Seleciona "Pedido entregue" ao concluir a entrega. <br> O aplicativo registra as atualizações e notifica o cliente. |  
| **Restrição**   | Atualizações dependem de conexão ativa com o servidor. |  
| **Exceção**     | Atualização falha devido à perda de conexão ou erro no aplicativo. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)  

### CN21: Entregador contata cliente via chat

#### Tabela 24: CN21

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador contata cliente via chat |  
| **Objetivo**    | O entregador deseja entrar em contato com o cliente para tirar dúvidas ou resolver problemas do pedido. |  
| **Contexto**    | Local: Durante o percurso ou no ponto de entrega. <br> Pré-condições: Pedido em andamento. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador acessa os detalhes do pedido no aplicativo. <br> Seleciona a opção "Contatar cliente". <br> A comunicação no chat é iniciada, permitindo a resolução de problemas. |  
| **Restrição**   | Cliente precisa estar disponível para responder. |  
| **Exceção**     | Falha na conexão impede a comunicação. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)

### CN22: Entregador atualiza informações pessoais (dados bancários ou contato)  

#### Tabela 25: CN22

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador atualiza informações pessoais (dados bancários ou contato) |  
| **Objetivo**    | O entregador deseja atualizar suas informações pessoais, como dados bancários ou informações de contato. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Entregador logado no aplicativo. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador acessa o menu de configurações no aplicativo. <br> Seleciona a opção "Editar informações pessoais". <br> Atualiza os dados desejados (como informações bancárias ou de contato). <br> Confirma as alterações. <br> O aplicativo salva as informações e exibe uma mensagem de sucesso. |  
| **Restrição**   | O entregador deve fornecer informações válidas e completas. |  
| **Exceção**     | Alteração falha devido à conexão instável ou erro no sistema. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)  

### CN23: Entregador verifica histórico de entregas  

#### Tabela 26: CN23

| **Elemento**   | **Descrição** |  
|-----------------|-------------------------------------------|  
| **Título**      | Entregador verifica histórico de entregas |  
| **Objetivo**    | O entregador deseja consultar o histórico de entregas realizadas. |  
| **Contexto**    | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Entregador logado no aplicativo. |  
| **Recursos**    | Aplicativo HungryHub Driver instalado. <br> Dispositivo móvel. <br> Conexão com a internet. |  
| **Atores**      | Entregador do HungryHub Driver. |  
| **Episódios**   | O entregador acessa o menu principal do aplicativo. <br> Seleciona a opção "Histórico de entregas". <br> O aplicativo exibe uma lista das entregas realizadas, com detalhes como data, horário e valor recebido. |  
| **Restrição**   | O histórico só inclui entregas associadas à conta do entregador. |  
| **Exceção**     | Histórico não é exibido devido a falha no carregamento ou erro no aplicativo. |  

**Autor:** [Gabryel Nicolas S de Sousa](https://github.com/gabryelns)

## Cenarios para Loja

### CN24: Lojista cadastra sua loja

#### Tabela 27: CN24

| Elemento   | Descrição    |
|------------|-------------------------------------------|
| **Título** | Lojista cadastra sua loja                                                |
| **Objetivo** | O lojista deseja registrar sua loja no aplicativo HungryHub.            |
| **Contexto** | Local: Escritório ou qualquer lugar com acesso à internet.              |
| **Recursos** | Aplicativo HungryHub Business instalado. <br> Dispositivo móvel ou computador. <br> Conexão com a internet. |
| **Atores** | Lojista do HungryHub Business                                                     |
| **Episódios** | O lojista acessa a tela de cadastro <br> Preenche o formulário com os dados da loja, incluindo endereço, horário de funcionamento e categorias de produtos. <br> Confirma o cadastro da loja. |
| **Restrição** | Todos os campos obrigatórios devem ser preenchidos corretamente.      |
| **Exceção** | Perder a conexão com a internet durante o preenchimento do formulário. |

**Autor:** [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva)

### CN25: Lojista gerencia cardápio

#### Tabela 28: CN25

| Elemento   | Descrição                      |
|------------|--------------------------------------|
| **Título** | Lojista gerencia cardápio                                                |
| **Objetivo** | O lojista deseja adicionar, editar ou remover itens do cardápio.       |
| **Contexto** | Local: Escritório ou qualquer lugar com acesso à internet.             |
| **Recursos** | Aplicativo ou portal web do HungryHub Business. <br> Dispositivo móvel ou computador. <br> Conexão com a internet. |
| **Atores** | Lojista do HungryHub Business                                                    |
| **Episódios** | O lojista faz login no aplicativo. <br> Acessa a seção "Gerenciar cardápio". <br> Adiciona novos itens, incluindo descrição, preço e imagem. <br> Edita itens existentes ou remove itens desatualizados. <br> Salva as alterações. |
| **Restrição** | Os itens precisam conter descrição, preço e categoria definidos.      |
| **Exceção** | Perder a conexão com a internet durante a edição do cardápio.          |

**Autor:** [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva)

### CN26: Lojista acompanha pedidos

#### Tabela 29: CN26

| Elemento   | Descrição                                     |
|------------|----------------------------|
| **Título** | Lojista acompanha pedidos                                                |
| **Objetivo** | O lojista deseja acompanhar os pedidos realizados pelos clientes.      |
| **Contexto** | Local: Escritório ou qualquer lugar com acesso à internet.             |
| **Recursos** | Aplicativo ou portal web do HungryHub. <br> Dispositivo móvel ou computador. <br> Conexão com a internet. |
| **Atores** | Lojista do HungryHub                                                     |
| **Episódios** | O lojista faz login no aplicativo. <br> Acessa a seção "Pedidos". <br> Visualiza os pedidos pendentes, em preparação e finalizados. <br> Atualiza o status dos pedidos conforme necessário. |
| **Restrição** | O pedido deve ter um status válido (pendente, em preparo, concluído).  |
| **Exceção** | O sistema não atualiza o status devido a falhas de conexão ou erros no aplicativo. |

**Autor:** [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva)

### CN27: Lojista cadastra entregador

#### Tabela 30: CN27

| Elemento   | Descrição           |
|------------|-------------------|
| **Título** | Lojista cadastra entregador                                              |
| **Objetivo** | O lojista deseja cadastrar um entregador para realizar entregas da sua loja. |
| **Contexto** | Local: Escritório ou qualquer lugar com acesso à internet.             |
| **Recursos** | Aplicativo ou portal web do HungryHub. <br> Dispositivo móvel ou computador. <br> Conexão com a internet. |
| **Atores** | Lojista do HungryHub                                                     |
| **Episódios** | O lojista faz login no aplicativo. <br> Acessa a seção "Gerenciar entregadores". <br> Seleciona a opção "Cadastrar entregador". <br> Preenche o formulário com os dados do entregador (nome, CPF, telefone, e-mail). <br> Confirma o cadastro do entregador. |
| **Restrição** | Todos os campos obrigatórios devem ser preenchidos corretamente.      |
| **Exceção** | Perder a conexão com a internet durante o preenchimento do formulário. |

**Autor:** [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva)

### CN28: Lojista configura promoções

#### Tabela 31: CN28

| Elemento   | Descrição                         |
|------------|---------------------------|
| **Título** | Lojista configura promoções                                              |
| **Objetivo** | O lojista deseja criar promoções para atrair mais clientes.            |
| **Contexto** | Local: Escritório ou qualquer lugar com acesso à internet. <br> **Pré-condições**: Loja cadastrada e ativa no aplicativo HungryHub. |    
| **Recursos** | Aplicativo ou portal web do HungryHub Business. <br> Dispositivo móvel ou computador. <br> Conexão com a internet. |
| **Atores** | Lojista do HungryHub Business                                                     |
| **Episódios** | O lojista faz login no aplicativo. <br> Acessa a seção "Promoções". <br> Configura promoções para itens selecionados (por exemplo, desconto, combo ou frete grátis). <br> Define a validade da promoção. <br> Salva as configurações. |
| **Restrição** | As promoções precisam ter uma data de início e fim claramente definidas. |
| **Exceção** | Perder a conexão com a internet durante a configuração da promoção.     |

**Autor:** [Bruno Cunha Vasconcelos de Araújo](https://github.com/brunocva)


# Histórico de versão 
| Versão | Data da alteração | Comentário                                                                      | Autor(es)                                    | Revisor(es) | Data de revisão |
| ------ | ----------------- | ------------------------------------------------------------------------------- | -------------------------------------------- | ----------- | --------------- |
| 1.0    | 25/11/2024        | Criação do documento de cenários, introdução e dos cenários CNE01, CNE02, CNE03 | [Davi Pierre](https://github.com/DaviPierre) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                |
| 1.1    | 26/11/2024        | Altera a introdução.<br> Subdive os cenarios anteriores em cenários menores e mais detalhados | [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                |
| 1.2    | 26/11/2024        | Inclusão dos cenários CNE05 e CNE06| [Bruno Araújo](https://github.com/brunocva) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                | 
| 1.3    | 26/11/2024        | Adiciona tabela de cenarios produzido e CN5, CN8, CN9, CN10|  [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                |
| 1.4    | 26/11/2024        | Adiciona os cenarios do CN11 ao CN28 |  [Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Bruno Araújo](https://github.com/brunocva), [Gabryel Nicolas Soares de Sousa](https://github.com/gabryelns)         | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                |
| 1.5    | 26/11/2024        | Nomeia e enumera as tabelas do documento |  [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)           | 27/11/2024                |          