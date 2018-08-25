# teste_tecnico_front-end
1) Se você tivesse 5 diferentes arquivos de folhas de estilo, qual seria a melhor forma de integrá-los no site?
- Inserindo essas folhas de estilo provenientes de um arquivo externo dentro do <head> das páginas: <link rel=”stylesheet” type=”text/css” href=”estilo.css” />
- Utilizando Less é possível organizar a construção dessas folhas de estilo separando – as em diferentes responsabilidades, por exemplo, construir uma folha de estilo apenas para cores
2) Fale 3 formas de diminuir o page load (tempo de carregamento real e percebido).
1. Uso de ferramentas para otimização do código
2. Posicionar as folhas de estilo no topo da página para que elas possam carregar progressivamente e desde o início do seu carregamento o usuário possa ver o design
3. Redimensionar as imagens para que aumente a velocidade do seu carregamento e com isso diminuir o page load
3) Quais ferramentas você usa para testar a performance do seu código?
- Google PageSpeed Insights e Pingdom Tools
4) Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
- div (divisão)
- h1 ao h6 (títulos)
- ul (lista não ordenada)
- ol (lista ordenada)
- form (formulários)
- p (parágrafos)
 - blockquote (citação em bloco)
5) Você pode explicar a diferença entre GET e POST?
Em resumo, o método GET pode enviar uma quantidade limitada de dados em comparação a quantidade de dados que o método POST pode enviar; no método GET a informação é enviada para o sistema de destino com o endereço dele, já o método POST a informação é enviada de forma encapsulada, não “aparecendo” na URL o que torna o POST mais seguro que o GET 
6) Liste quantas propriedades display você puder lembrar.
display: none
display: inline
display: block
display: inline–block
display: table
display: inline–table
display: table–collum
display: table–cell
display: table–collum–group
display: table–header–group
display: table–footer–group
display: table–row
display: table–row–group
display: grid
display: inline–grid
display: run–in
display: inherit
display: flex
display: inline–flex
display: list–item  
7) Qual a diferença entre inline e inline-block?
Inline-block é a junção dos comportamentos inline (ocupando apenas o espaço do conteúdo, sem quebrar a linha) e block (dimensões configuráveis) em um único elemento HTML.
8) Qual a diferença entre elementos posicionados de forma relativa, fixa, absoluta e estática?
Fixa: 
A posição fixa é usada para fixar um elemento na janela. Normalmente aquilo que queremos fazer aos nossos headers com menu! Se algo está por baixo desta camada não é clicável!
Estática:
Modelo padrão das posições. Todos os elementos com esta posição são estáticos ao fluxo. Move-se se o outro se mover. Uma escolha ótima e segura, com limites definidos ajuda a manter o design perfeito.
Relativa:
Os elementos são sempre posicionados relativamente ao seu “pai”. Há possibilidade de definir a relação que esta mantêm com o seu superior, por exemplo estar sempre a 50px da margem esquerda do container “pai”. É das posições mais utilizadas em frameworks como o Bootstrap.
Absoluta:
Elementos que vivem sob a sua própria regra em relação ao seu “pai” com posição relativa. Não obedecem ao fluxo, apenas se importa em manter a posição X e Y que foi definida ao longo da navegação relativa. A Posição Absoluta não é por isso a melhor amiga do layout responsive!
9) Qual a diferença entre .call e .apply?
Eles possuem a mesma função no Javascript, ambos emprestam métodos, a diferença entre eles está nos parâmetros. O .call utiliza como primeiro parâmetro o this (contexto) e os próximos são os parâmetros da função. Já o .apply invoca uma função com o this (contexto) e um array com os parâmetros da função. 
10) Qual a diferença entre == e ===?
A diferença entre == (igualdade) e === (igualdade estrita) é que o operador de igualdade forçará valores de diferentes tipos antes de verificar a igualdade.  O operador de igualdade estrita, por outro lado, não forçará valores para diferentes tipos.
