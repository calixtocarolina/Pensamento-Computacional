# Navegação, pesquisa e filtragem: abstraindo e exemplificando :computer:



## Introdução



Agora que já saímos do nosso ponto inicial, que é conhecer o processo de pensar computacionalmente e entender os passos de decomposição, reconhecimento de padrões recorrentes, abstração e explicitação para criar um algoritmo e solucionar um problema ou executar uma tarefa, vamos continuar a jornada pelo conteúdo! 

A discussão agora passará pela tarefa que é bem conhecida por qualquer pessoa que um dia já acessou a web, ou seja, _navegou_ pela web: o funcionamento de pesquisa e navegação pela internet.

Para fins educacionais e já exercitar um dos pilares do pensamento computacional, vamos abstrair e utilizar uma abordagem com conceitos. Assim, não vou utilizar como exemplos o serviço de busca específico X ou Y, mas referindo a quais tarefas eles realizam. Em alguns casos, posso utilizar uma referência de sites para exemplificar melhor.



## Navegação na web



### Navegação interna e externa em sites

 Você certamente já entrou na web hoje. Agora mesmo, você está vendo uma página de web no site do GitHub para ler esse conteúdo. E fora esse, em quais outros sites você navegou antes? E ontem? Qual foi o último site que você visitou? Lembra o que foi fazer nele?

Agora que você remexeu um pouco a memória e se lembrou o último site que visitou e o motivo, pense novamente: você lembra em quantos links internos (links internos são links que conectam páginas dentro do mesmo site) ao site, aproximadamente, você clicou? Se o site foi um _e-commerce_, posso acreditar que foram muitos!

Como você chegou até esse site? Fez uma pesquisa em uma página de serviço de busca ou já havia guardado esse site entre os seus favoritos? Utiliza o site frequentemente, em caso de uma rede social, e como o navegador guarda os sites em que você costuma navegar, foi só você começar a digitar algumas letras que o próprio navegador já completou o endereço para você?

Afinal, o que é navegar em um site, navegar na web?

Podemos afirmar que navegação em um site é o ato de clicar em várias páginas de um mesmo site, com um determinado fim. Esse fim pode ser para se informar, comprar um produto, utilizar alguma funcionalidade, as possibilidades são diversas!

Por ter diferentes funcionalidades e funções, os sites são estruturados de forma diferente também. Por exemplo, o GitHub não possui a mesma estrutura que um site de jogos ou um site de plataforma de universidade, ou um _e-commerce_. 

É importante pontuar que além dos links internos, que, ao serem clicados, nos levam a páginas dentro do próprio site em que estamos navegando, também existem os links externos, que são os links que conectam o site em questão a outros sites.



### Navegadores __(browsers)__

Para navegar na web, utilizamos programas criados para esse fim, nomeados de navegadores ou _browsers_. Estes programas utilizam regras definidas para documentos web para apresentar seu conteúdo aos usuários, sejam textos, tabelas, menus, imagens, vídeos, áudios, etc. Os navegadores interpretam as operações de navegação oferecidas aos usuários por meio de links internos e externos de cada página.

Nós, seres humanos, temos uma memória de curto prazo muito limitada e nada parecida com a memória de um computador, infelizmente.

Quando navegamos na web por um conjunto de páginas, o número de links que selecionamos para reter em nossa memória é muito pequeno se comparado a quantidade que realmente utilizamos durante todo o nosso dia, diariamente. 

Se tivéssemos que lembrar e registrar cada link que selecionamos para poder retornar as páginas anteriores, por exemplo, nossa navegação na web seria extremamente limitada. 

Já os programas, advindo dos computadores, podem armazenar grande quantidades de informação. Por isso, os navegadores são um auxílio e tanto nas nossas tarefas diárias e estão presentes nas atividades na web dos usuários de várias maneiras!

Alguns exemplos são: salvar uma lista de links favoritos, registro automático de endereços de site pelo próprio navegador (inclusive com a operação de _voltar_ e retornar aos sites anteriores quantas vezes desejar), apresentar opções de endereços similares aos sites que visitamos anteriormente, etc.

### Sites e Cookies :cookie:

Você já deve ter se deparado com o termo "cookies" enquanto navegava em um site, ms sabe o que significa isso na prática?

Quando você navega em um site, ele pode necessitar realizar uma coleta de informações sobre quem é o usuário que está acessando as páginas internas. Os arquivos que registram essas informações e as preferências do usuário se chamam cookies.

Existem cookies temporários e permanentes. Os temporários são removidos da máquina quando o usuário fecha o navegador, já os cookies permanentes se mantém no computador até a sua data de validade expirar. 

E quando é que a exigência de cookies é essencial? Podemos dizer que em sites que precisam de um login e senha é essencial para um bom funcionamento, ou em sites em que o usuário visualiza produtos e anúncios, mas não é necessário caso não seja de sua vontade. 

Para saber mais informações e dicas sobre os cookies, incluindo cuidados e questões relativas ao tratamento de informações, entre no [projeto Cidadão na Rede](https://cidadaonarede.nic.br/pt/videos/cookies-do-navegador).



### A web (gigaaaante)

O conceito de web que hoje utilizamos foi criado em 1989 por Tim Berners-Lee, um cientista da computação e físico, enquanto trabalhava em uma organização europeia de pesquisa que opera o maior laboratório de física de partícula do mundo.

Tim Berners-Lee, em 1989, não pensava que a web iria tomar as proporções que tomou, pois seu objetivo com o projeto era de facilitar o compartilhamento de dados entre físicos do mundo todo. 

Naquela época, aplicando o conceito de hiperlink que já existia há algumas décadas, ele desenvolveu o primeiro servidor web, o primeiro navegador web e os protocolos que permitiam formatar e transferir documentos anotados com as referências associam um documento a outro.

E qual era a denominação desse protocolo? Isso mesmo, a nossa querida _Hypertext Markup Language (HTML)_, que utilizamos até hoje como linguagem de marcação hipertexto em diversas funcionalidades.

Já o protocolo de comunicação entre navegador e servidores, que permite acessar documentos e navegar entre eles foi chamado de _Hypertext Transfer Protocol (HTTP)_. 

Já dá pra perceber que esse pesquisador contribuiu e muito com a computação, pois tanto o HTML quanto o HTTP são protocolos usados diariamente até hoje por nós, estudantes, programadores, usuários e interessados na área!

Ao final dos anos 1990, o primeiro website já estava disponível na web, em domínio público, em conjunto com o primeiro navegador. E o mais legal de tudo isso é que o primeiro website ainda existe e está no ar, podendo ser acessado por [aqui](http://info.cern.ch/hypertext/WWW/TheProject.html).

Primeiro website:

![Imagem do primeiro website](https://linhadefensiva.files.wordpress.com/2013/04/primeirowww12.jpg)

Primeiro navegador (que também era um editor):

![Imagem do primeiro navegador](https://www.w3.org/History/1994/WWW/Journals/CACM/screensnap2_24c.gif)

E afinal, **o que é um website**? Um website é um conjunto de páginas disponibilizado por um servidor que pode ser acessado na Web por meio do protocolo HTTP.

Atualmente, o tamanho da web é *gigante*, sendo continuamente atualizado por meio de [estudos em tempo real](https://www.internetlivestats.com/total-number-of-websites/). Existem cerca de 1.5 bilhões de sites, a maioria deles inativos. A partir dos estudos citados, em Julho de 2022 estima-se que cerca de 200 milhões de sites estão ativos, e cada um deles pode (ou não) levar a um conjunto de páginas internas.

Agora, ao pensar nesses números, temos que ter em mente outra questão: como navegamos na web, em um espaço de 200 milhões de websites?

Assim, temos que traçar variações entre duas estratégias:

* Visitar um site conhecido

* Utilizar um serviço de busca



### Os serviços de busca

Entre os sites mais acessados da web, estão os serviços de busca, que servem como uma "porta de entrada" para todos os demais, visto que são eles em que podemos encontrar todos os outros, caso já não tenhamos conhecimento do que queremos acessar.

A partir dessa informação, vamos utilizar os pilares do pensamento computacional para entender como os serviços de busca funcionam:

+ Decomposição do problema

+ Reconhecimento de padrões recorrentes

+ Abstração de tarefas e seus dados de entrada e saída

+ Explicitar o algoritmo que resolve o problema



Considerando as dimensões da web, devemos considerar o seguinte: um usuário coloca um dado de entrada, que é a consulta, e o serviço deve respondê-la sem pesquisar a web no momento em que a consulta acontece. Qual é o motivo disso ocorrer?

+ Primeiro, temos que pensar que, se fosse esse o caso, , seria impossível dar respostas ao usuário dentro de um tempo que usuário estaria disposto a esperar, pois a Web tem cerca de 3.1 bilhões de páginas. Imagina aguardar o tempo do serviço de buscar pesquisar em todas essas páginas?

+ Além disso, cada consulta geraria um tráfego na Internet que impossibilitaria o uso da mesma, inclusive porque serviços de busca estão entre os sites mais acessados da Web.



Se os serviços de busca não pesquisam na web pela resposta do usuário no momento em que se faz a consulta, onde eles realizam a busca? É aí que entra a estrutura construída previamente armazenada e que pode ser acessada rapidamente pelos serviços de busca.

Pode-se imaginar, em um primeiro momento, que tal estrutura seja uma cópia da web. E além de realizar a pesquisa de forma rápida e eficiente, há também a questão importante da **filtragem** de conteúdo, ou seja, quais informações seriam relevantes para o usuário. Por exemplo, se um usuário faz uma consulta com a palavra-chave "hospital", provavelmente ele não quer saber a respeito do hospital mais famoso do mundo e sim qual é o hospital mais próximo de sua localização.

Assim, podemos realizar a **decomposição**, primeiro pilar do pensamento computacional, na tarefa de **responder a uma consulta do usuário em um tempo aceitável** em três subtarefas:

+ Navegação dentro da estrutura

+ Pesquisa eficiente e rápida no conteúdo

+ Filtragem deste conteúdo em itens relevantes



Agora, para **reconhecer padrões recorrentes**, podemos nos ocupar em pensar em como o serviço de busca constrói essa cópia da web que mencionamos acima. Como é possível que tal serviço consiga acessar toda a web, ou seja, 1.5 bilhões de website, e como estão conectados?

A web está estruturada dessa forma: <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Internet_map_1024_-_transparent%2C_inverted.png" title="" alt="estrutura da web conectada" data-align="center">

Um serviço de busca pode utilizar o padrão da própria web e o padrão utilizado pelos usuários para a navegação para criar a cópia da web. Assim, o serviço de busca pode usar o padrão empregado pelo usuário para navegar e, adicionalmente, garantir que navega em todas as páginas disponíves na web.

Mas, de onde começar a vasculhar para garantir que todo o conteúdo disponibilizado seria alcançado pela navegação? A resposta é: pelos endereços (links) de web. 

Endereços da Web são endereços da Internet (sim, web e internet são coisas diferentes) nos quais há um servidor Web disponível aguardando a visita de usuários.

Todo endereço tem uma atribuição em uma organização internacional, a _Autoridade para Atribuição de Números da Internet_. Essa organização e outras agências disponibilizam diretórios em que estão listados os endereços de todos os servidores da web. A partir dessa lista é que os serviços de busca poderão visitar os links existentes.

Agora, para podermos abstrair a tarefa de **como os serviços de busca utilizam a cópia da web**, precisamos ponderar o seguinte: de qual maneira os serviços de busca fazem consultas que sejam relevantes para o usuário? é feito de uma a uma em bilhões de páginas? Já sabemos que esse tipo de pesquisa é contraproducente por diversas razões, mas então, como será que os serviços de busca operam?

Para responder a questão, vamos refletir com um outro exemplo prático da vida cotidiana: quando uma pessoa quer fazer uma busca específica de conteúdo em um livro, ela vai buscar esse conteúdo através do 1) sumário, ou 2) índice remissivo. Tanto um quanto o outro tem o objetivo de fazer encontrar conteúdos ou palavras-chaves em uma vasta paginação.

Essa é a imagem de um sumário comum, seguindo as normas descritas na ABNT:

<img src="file:///C:/Users/calix/AppData/Roaming/marktext/images/2022-10-16-23-04-04-image.png" title="" alt="" data-align="center">

Já, esse é um índice remissivo, que trabalha com o uso de termos e palavras-chave:

<img src="file:///C:/Users/calix/AppData/Roaming/marktext/images/2022-10-16-23-05-50-image.png" title="" alt="" data-align="center">

Agora que já ilustramos por meio de outro exemplo, vamos retornar aos serviços de busca! Utilizando sua cópia da web, um serviço de busca pode analisar as páginas presentes na web e gerar índices como o mencionado acima. 

Quando o usuário faz uma consulta, o serviço de busca pesquisa no índice remissivo que páginas na web possuem de conteúdo associado aos **termos utilizados pelo usuário**.

Por fim, como podemos ter uma garantia de que todas as páginas de web serão visitadas?

Para isso, o serviço de busca precisa:

+ registrar todos os links disponíveis em cada página (internos e externos)

+ controlar que todos os links sejam visitados na navegação



Seguindo o **algoritmo** acima explicitado, o serviço de busca garante que todas as páginas disponíveis em um website são visitadas. O serviço de busca, ao criar o índice remissivo, cria um algoritmo neste sentido:

1.  construir uma tabela com termos, inicialmente vazia;

2. repetir, para cada página de sua cópia da web
   
   (a) identificar os termos relevantes;
   
   (b) repetir para cada termo relevante;
   
   i. se o termo não existir no índice remissivo, inserir o termo relevante no índice;
   
   ii. inserir no índice remissivo a informação de que o termo está contido na página.

Agora, o algoritmo está finalizado. Percebe-se como o algoritmo se forma e há uma sequência de passos finitos nele para executar uma tarefa ou solucionar um problema que, nesse caso, foi verificar como criar um índice remissivo de serviço de buscas para fazer uma consulta na web. 



### Links úteis para aprofundar no assunto!

Agora que passamos por compreender aspectos básicos em navegação, pesquisa e filtragem, vamos aprofundar um pouco mais nosso conhecimento além do repositório?

Abaixo, recomendo alguns artigos interessantes, sites e livros para quem se interessou pelo assunto. 

+ [Computacional Thinking benefits society, de Jeannette M. Wing](http://socialissues.cs.toronto.edu/index.html%3Fp%3D279.html)

+ [História da World Wide Web](https://pt.wikipedia.org/wiki/Hist%C3%B3ria_da_World_Wide_Web)

+ [A short history of the Web | CERN](https://home.cern/science/computing/birth-web/short-history-web)

+ [Projeto Cidadão na Rede](https://cidadaonarede.nic.br/pt/)



**Bons estudos e até o próximo módulo! Acompanhe o próximo com a função de watch e  deixe sua :star: para apoiá-lo!**

### Agradecimentos :clap:

Gostaria de agradecer à Prof. Dra. Maria da Graça C. Pimentel (USP/Univesp) e o Prof. Douglas Maioli que me ensinaram muito durante o curso de Pensamento Computacional que tive no primeiro semestre do curso de Tecnologia da Informação da Univesp. Sem os professores e a educação, nada desse conhecimento seria possível! 








