
__Nome:                     | nºUSP:__  
_Beatriz Helena Dias Rocha   | 11300051_  
_Juliana Bernardes Freitas   | 11317928_  
_Lucas Henrique Sant'Anna    | 10748521_  
_Lucas Viana Vilela          | 10748409_  
_Rafaela Cristina Bull       | 11233651_  
__Grupo - 1__  
  
------------------------------------------  
  
# Relatório do Projeto: E-Commerce
## SCC219 - Introdução ao Desenvolvimento Web


### 1. Requerimentos

  
  A descrição do projeto em sua versão final requeria para a presente etapa já algumas funcionalidades. Porém como o e-commerce aqui implementado é voltado para servir a uma entidade universitária para suas eventuais vendas de artigos e eventos, algumas particularidades foram adicionadas aos requerimentos iniciais. E resumo os requerimentos são estes:  
  - Dois tipos de usuários:  
    - Cliente - Esse tipo de conta conseguem escolher os produtos que deseja comprar e percorrer todo o processo para realizar o pedido. 
    
    - Administrador - Uma conta de administrador consegue adicionar novos administradores e gerencia-los, assim como pode fazer o mesmo para contas cliente. Também gerencia o estoque dos itens e o fluxo de pedidos. 
    
    
 - Como a SA-SHREK vende produtos então seguimos os requerimentos correspondetes a tal. Isto é, o cliente pode escolher entre produtos e eventos. Selecionando, quando habilitado, as especificação do item (tamanho, quantidade e modelagem) e adicionando-o ao carrinho de compras. Passando por todo o processo até concluir a compra e escolhendo no caminho outras especifiações do pedido, como por exemplo a forma de pagamento. Nas especificações fornecidas cosntava o cartão de crédito como uma forma de pagamento, utilizamos na implementação apenas transferências por essa ser a opção mais dentro do contexto onde a loja está inserida, mas para a versão final planeja-se incluir a opção sugerida para fins de demonstração. Foi incluido ainda nesse projeto a funcionalidade de cupons de desconto.
 
 - Funcionalidade implementada especificamente para nossa implementação foi o cupom de desconto
 - Foram implementados ao projeto funcionalidades e ferramentas para prover cada um dos itens a seguir:  
   - __Acessibilidade:__   
   Além de resursos de acessibilidade padrão, como texto alternativo para imagens, foram implementados recursos de menor presença nos projetos web. O primeiro é a mudança de cores das páginas para torna-las acessiveis para daltônicos. Tal recurso pode ser visualizado mudando o botão na parte direita do cabeçalho. O outro recurso permite dar uma no site, aumentado o tamanho de todos os elementos da página. Essas funcionalidade menos difundidas são apresentas na página _Acessiblidade_ com link no rodapé do site. 
   
   - __Usabilidade:__  
   A aplicação foi implementada até aqui para ser funcional e entregar ao usuário aquilo que ele procura. Em questão de design, o site apresenta páginas limpas que mostram apenas o essencial para que o usuário saiba onde está e o que deve fazer. Botões e links que apresentam suas funções de forma lógica e dentro dos hábitos de navegação dos consumidores. Como o site foi desenvolvido pensando para vendas em uma pequena comunidade e com uma pequena diversidade de produtos, não é mostrado durante o processo de verificação da compra outros produtos além daquele que o usuário selecionou para o seu carrinho de compras. Temos assim um circuito linear e sem ramificações que leva da seleção do produto à confirmação da compra, algo não aconselhável para grades e-commerces, mas que é ideal para o contexto.  
   
      A arquitetura de informação do site é bastante lógica e simples. As conexões entre links, menus e outros elementos são práticos e funcionais. A divisão dos  produtos dentro do site é clara, as duas principais categorias são artigos físicos e eventos, logo ambos aparecem diretamente no menu da cabeçalho. Ao passar o mouse  por cima do botão, um menu _dropdrow_ aparece apresentando as subcategorias. Clicar no botão do menu inicial te leva para uma página de geral com um filtro lateral que mostra só os produtos da subcategoria seleciona. Outro modo de chegar até o produto é digitar seu nome ou da sua subcategoria na caixa de pesquisa.  
   
      Muitas facilidades podem ser encontras também para um usuário do tipo administrador. Como o objetivo do administrador é fazer a gestão da loja, todas suas funções foram divididas por abas e  colocadas em uma página chamanda de __Página do Administrador__,. Nela o administrador consegue ter o controle de todos os produtos que são vendidos na loja, podendo editar suas propriedades (Nome, Imagens, texto da Imagem, Preço, Preço com desconto, Tipo, Categoria, Descrição e Quantidade) e opção de escolha (Modelagem, Tamanho e Cor). Consegue ver os pedidos realizados e seus status, assim como produtos cadastrados no site, mas que não estão visíveis aos clietes. Outra aba desta página é a Novo Pedido, onde há a opção de cadastras novos produtos especificando as propriedades já citadas. A ultima aba contém todos os usuários cadastrados, por ela se administra tanto cliente quanto administradores dependendo da hierarquia. 
   
   
   - __Responsividade:__  
   Os componentes da página foram implementados para serem responsivos para qualquer tamanho de tela de computador. Grande parte do site não foi configurado para se adaptar para telas mobile, tendo suas estruturas sido definidas dentro das folhas de estilo CSS. Outros janelas e compoenentes, por serem construídos com o framework Bootstrap, têm responsividade com dispositivos mobile, porém são exceções de modo que não há uma página inteira que se mostre compatível em um table ou celular. 

