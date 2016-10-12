# Web Starter Kit

---

## Feito por Google Inc.: 

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Figura%200%20(capa).png)

---

##Resumo:

Uma ferramenta que facilite o desenvolvimento web, não sendo um framework mas sim auxiliando o desenvolvimento de software em um ambiente web, onde conseguir compreender as tarefas do servidor pode ser complexo dadas as demandas dos cliente. Com estes e outros propósitos, a ferramenta Web Starter Kit do Google permite programar de forma simples e eficiente, utilizando-se desde estilos de páginas padronizados a até atualização automática (dispensando o tradicional f5) e permitir o uso de ferramentas de compatibilidade com diversos navegadores / dispositivos.

---

##Conteúdo:

1. Descrição 
2. Principais features 
3. Objetivo 
4. Pré-requisitos 
5. Instalação 
6. Linguagens de Programação 
7. Equipe de desenvolvimento 
8. Descrição da evolução do sistema 
9. Frameworks 
10. Ferramentas 
11. Módulos 
12. Padrões de Projeto 
13. Arquitetura 
14. Referências

---

##1. Descrição:

Web Starter Kit é um ponto de partida para o desenvolvimento web multi-screen. Ela engloba recomendações para a construção de uma experiência que pode ser utilizado em vários dispositivos. 

O lançamento do Web Starter Kit do Google trouxe uma série de templates e ferramentas que focam na problemas de performance de e  desenvolvimento multi-screen. O Google, então, através dessa ferramenta, possibilita uma otimização da performance de aplicativos web. 

Como um produto do Google, a ferramenta permite simplificar processos os executados por seus usuários para obter resultados de qualidade, neste caso criar um código web de forma simples explorando funcionalidades que agregam valor ao projeto. 

O Web Starter Kit é inspirado no HTML5 Boilerplate e Yeoman, a partir da combinação de algumas funcionalidades e recursos dessas ferramentas. O Web Starter Kit vem com modelos básicos, que são otimizados tanto para velocidade quanto para múltiplos dispositivos. 

Além disso, ele engloba um conjunto de ferramentas para facilitar o desenvolvimento, incluindo ferramentas de teste sincronizado, recarregador automático de navegadores (live reloader), analisador de JavaScript, compilador de Sass, minizador CSS e um otimizador de imagens. Assim como o Yeoman, essas ferramentas vem pré-configuradas, então, podemos começar o desenvolvimento sem gastar tempo, tendo de configurá-las. 

---

##2. Principais features 

###2.1. Ferramentas 

Abaixo, algumas features são descritas, desta forma, é possível compreender melhor as funcionalidades do sistema.
Responsive Boilerplate : 

a. É uma ferramenta responsável por utilizar um poderoso template de HTML, que permite ao usuário criar interfaces de design mais avançadas. 

b. Suporte SSAS : O suporte a SSAS permite utilizar SSAS em CSS com facilidade, podendo se até criar variáveis. Para produzir se pode executar ' gulp serve' ou 'gulp' . 

c. Otimização de Desempenho : Permite reduzir e concatenar Javascript, CSS, HTML e imagens para ajudar a manter sua página enxuta, ou seja, blocos de código modularizados e de tamanho suficiente para outros desenvolvedores o compreenderem. Executar 'gulp' para criar uma versão otimizada do seu projeto (to / dist). 

d. Código Linting :  Permite ao usuário executar um programa que irá analisar o código procurando por erros em potencial. JavaScript linting código é feito usando ESLint - uma ferramenta linter conectável para identificar e relatar sobre os padrões em JavaScript. Web Starter Kit usa ESLint com eslint-config-google, que tenta seguir o guia de estilo do Google para JavaScript. 

e. ES2015 via Babel 6.0 : Suporte adicional ES2015 que utiliza Babel. É possível ativá-lo removendo a linha "only": "gulpfile.babel.js" do arquivo .babelrc. Desta forma, é possível compilar um código e gerar um outro código com suporte para ES5, o que promove o suporte a um determinado navegador. 

f. Built-in HTTP Server : É um servidor que permite visualizar seu site localmente enquanto você desenvolve, proporcionando o desenvolvimento interativo. 

g. Live Browser Reloading : Permite recarregar o navegador e visualizar modificações a qualquer momento em que o código foi editado, sem a necessidade de instalar extensões no navegador. 

h. Cross-device Synchronization : Permite recarregar automaticamente, sincronizar cliques e scrolls da forma mais adequada ao seu projeto. É necessário executar o comando 'gule server' e abrir o IP fornecido em outros dispositivos na sua rede. 

i. Suporte Offline : Utilizando sw-precache, é possível utilizar um serviço de suporte offline quando o destino é um endereço HTTPS. Esta opção facilita o acesso a suporte, tornando-o simples e eficiente. 

j. PageSpeed Insights : Permite se calcular e utilizar métricas para demonstrar como se dará a execução do site em um ambiente mobile ou desktop.


###2.2. Guia para Estilização Básica 

O Web Starter Kit provê um Guia de Estilos para auxiliar o desenvolver a começar o seu projeto, já que é construído a partir dos estilos dos elementos e componentes mais comuns, como tipografia, botões, links, tabelas, ícones e grades (grid). 

O Guia de Estilos pode ser encontrado no diretório app/styleguide e está interconectado às folhas de estilos. Dessa forma, podemos ver o Guia de Estilos evoluindo de acordo com que as folhas de estilos são atualizadas. 

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%201%20-%20%C3%8Dcones%20de%20Destaque%20no%20Guia%20de%20Estilos%20do%20Web%20Starter%20Kit.png)
> *Imagem 1 - Ícones de Destaque no Guia de Estilos do Web Starter Kit*


---

##3. Objetivo 

A ferramenta Web Starter Kit foi criada pela Google com o objetivo de proporcionar ao programador desenvolvimento de software voltado para um ambiente web de forma mais simples. O sistema é especialmente voltado a profissionais recém chegados a indústria. 

Esta ferramenta permite explorar funcionalidades presentes em diversos dispositivos e ambientes de execução, visando assim facilitar ao programador o acesso a funcionalidades que não estão disponíveis de forma trivial. 

Explorar funcionalidades de diferentes dispositivos no projeto permite aos desenvolvedores agregar valor e qualidade, sendo este um objetivo importante, permitir ao programador criar códigos legíveis e de fácil compreensão mesmo este código sendo utilizado em uma aplicação complexa. 

---

##4. Pré-requisitos 

###4.1. Ferramentas 

Para utilizar o Google Web Starter Kit é necessário baixar os arquivos do repositório do Google, mas é aconselhável que algumas ferramentas sejam instaladas, de forma a explorar melhor os recursos do mesmo. Dentre as ferramentas a serem instaladas: 

* Git : utiliza-se o github para obter o código através de uma clonagem do repositório, através do pacote Zip. Para tal, basta utilizar o comando git clone no prompt de comando, seguinte da url correspondente ao repositório. Caso o aplicativo do GitHub seja utilizado, basta apertar o botão Clone in Desktop, na página do repositório. 

* Node.js : algumas das ferramentas utilizadas no Web Starter Kit são para Node.js, como o JSLinter, sendo instaladas através do Node Package Manager (NPM). Para instalar o node, basta acessar a página oficial nodeJS.org e realizar a instalação do mesmo, em sua última versão. 

Para verificar se a ferramenta já está instalada no computador, basta digitar o seguinte comando no terminal ou cmd: 

	node -v 

Esse comando retorna a versão do node instalada no computador. Caso ela esteja atualizada com relação à última versão lançada isso já será suficiente. Caso contrário, basta instalar a nova versão através da página oficial nodeJS.org. 

* Ruby e Sass : o Web Starter Kit usa o gulp-ruby-sass para compilar o Sass em CSS, o que requer tanto o Ruby quanto o Sass para funcionar. Caso o Sistema Operacional utilizado seja o OS X ou Linux, o Ruby já deve estar instalado na máquina. Caso seja Windows, basta usar o RubyInstaller para instalar o Ruby, e, em seguida, executar o comando execute gem install sass na linha de comando para instalar o Sass. Assim como no Node.js, para verificar se a ferramenta Ruby já está instalada no computador, basta digitar o seguinte comando: 

	ruby -v 

É possível também instalar o Sass por meio de um instalador disponibilizado em seu site oficial http://sass-lang.com/install. E para verificar se a ferramenta Sass já está instalada no computador, basta digitar o seguinte comando no terminal ou cmd: 

	sass -v 

* Gulp : essa ferramenta é utilizada para lidar com algumas tarefas durante o desenvolvimento. Para instalá-lo, e tendo em vista que o Node.js já se encontra instalado na máquina, basta dar o comando npm install -g gulp.
Para instalar dependências locais do Web Starter Kit:

	cd web-starter-kit 
	npm install 

O Gulp é um executador de tarefas que as automatiza durante o desenvolvimento, tentando facilitar o desenvolvimento. Para usar o Gulp normalmente é necessário especificar e configurar suas tarefas no arquivo gulpfile.js, mas, uma vez que o Web Starter Kit já faz isso automaticamente, é possível executar as tarefas do Gulp imediatamente, sem realizar nenhuma configuração adicional. 

O comando gulp server ativará o BrowserSync que está incorporado e configurado no arquivo gulpfile.js. Essa ferramenta permite que o usuário teste sites entre diversos navegadores. Com o BrowserSync, a interação do usuário, como a rolagem, cliques e preenchimento de campos de formulário, será refletida, em tempo real, entre todos os aparelhos conectados. O BrowseSync também inclui um servidor HTTP. Ao executar esse comando, é possível ter acesso ao endereço localhost onde o site poderá ser acessado. 

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%202%20-%20P%C3%A1gina%20HTML%20com%20servidor%20HTTP.png)
> *Imagem 2 - Página HTML com servidor HTTP*


O BrowserSync também é responsável por monitorar as mudanças realizadas, incluindo HTML, folhas de estilo e imagens. Quando algum desses arquivos é modificado, o BrowserSync executa a tarefa especificada no gulpfile.js.
Depois de executar o comando gulp serve, é possível que o sistema exiba uma mensagem de que o BrowserSync não foi encontrado. Se isso ocorrer, basta instalar o arquivo manualmente, através do comando: 

	npm install browser-sync 

Para compilar o projeto: 

	gulp

E para obter um feedback sobre a velocidade de execução do projeto, usa-se o comando a seguir: 

	gulp pagespeed


![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%203%20-%20P%C3%A1gina%20de%20velocidade%20de%20execu%C3%A7%C3%A3o%20do%20projeto.png) 
> *Imagem 3 - Página de velocidade de execução do projeto*


Para publicar o site, o comando a seguir deve ser executado, sendo responsável executar as tarefas do Gulp e compilar o projeto em um pacote distribuível dentro de um diretório denominado dist/. Após seguir esses passos o site já estará pronto para ser enviado ao cliente.

	gulp deploy

###4.2 Browsers 

Atualmente o Web Starter Kit suporta as duas últimas versões de cada navegador listado a seguir. Isso significa que a ferramenta funciona melhor em cada um desses navegadores, sem garantir que em outros browsers a experiência de uso será adequada.

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 9+ 

---

##5. Instalação
Para realizar a instalação do Web Started Kit, basta utilizar clonar o repositório correspondente à ferramenta do Git Hub, através do seguinte comando: 

	git clone https://github.com/google/web-starter-kit.git

Ao entrar no diretório "web-starter-kit" gerado, encontramos os seguintes arquivos e pastas:

Arquivo / Pasta | Descrição das informações
--------- | -------
readme.md | versão resumida da documentação oficial;
license | informações sobre licença (Apache 2.0);
package.json | lista metadados e de dependências do projeto;
gulpfile.js | arquivo de automatização que contém configurações necessárias para executar as tarefas do Gulp;
app | diretório onde todos os códigos não minimizados ficarão.
>  Tabela 1 - conteúdo geral do diretório web-starter-kit 

Analisando internamente a pasta app, temos o seguinte conteúdo:

Arquivo / Pasta | Descrição das informações
--------- | ------- 
apple-touch-icon-precomposed.png
favicon.ico |  ícones de favoritos;
humans.txt | informações sobre a equipe de produção do projeto;
robots.txt | configuração para robôs de busca;
manifest.webapp | metadados do projeto;
fonts | pasta de arquivos de fontes a serem importadas via @font-face;
images | pasta de arquivos de imagens;
scripts | pasta de arquivos JavaScript;
styles | pasta de arquivos de CSS e SCSS;
styleguide | pasta de arquivos do Guia de Estilos.
> *Tabela 2 - conteúdo do diretório web-starter-kit/app*

Com relação à pasta styles, existem dois arquivos css e uma pasta de componentes, como pode ser visto a seguir: 

Arquivo / Pasta | Descrição das informações
--------- | ------- 
h5bp.css  | o CSS base do HTML5 Boilerplate com algumas normatizações;
main.css  | folha de estilos principal;
components | pasta com módulos de CSS
> *Tabela 3 - conteúdo do diretório web-starter-kit/styles*

---

##6. Linguagem de Programação
Dentre as linguagens utilizadas, podem ser citadas as seguintes:
* HTML (HyperText Markup Language) : Linguagem de marcação utilizada para produzir programas em interface web.
* CSS (Cascading Style Sheets) : Linguagem utilizada para definir o estilo de páginas escritas em uma linguagem de marcação.
* JavaScript : Uma linguagem de programação interpretada. Comumente utilizada para retratar e executar eventos complexos.

---

##7. Equipe de desenvolvimento 

Para que uma pessoa seja considerada contribuidora e desenvolvedora no projeto, ela deve criar uma “issue”, ou seja, reportar um problema encontrado por ele na página https://github.com/google/web-starter-kit/issues. Cada relatório enviado deve trazer uma justificativa sobre o porquê de se incluir determinado código/função e/ou modificar outro. O Web Starter Kit é um projeto opinativo e, como tal, os relatos enviados que adicionam suporte com opções alternativas para o que já está prescrito não são garantidos, devendo ser validados. 

Com base em razões de legalidade, todos os contribuidores devem assinar os termos de licença do contribuidores, sendo para indivíduos ou corporações, antes que o que foi proposto seja aceito. 

Desde o dia 6 de abril de 2014, até o dia 2 de outubro de 2016, a ferramenta teve a colaboração de 70 membros para auxiliar no desenvolvimento. O gráfico abaixo mostra a quantidade de contribuições por tempo.

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%204%20-%20quantidade%20de%20membros%20colaboradores%20por%20tempo.png)
> *Imagem 4 - quantidade de membros colaboradores por tempo* 


Com relação aos membros desenvolvedores, os dois principais, com respectivamente 234 e 90 contribuições, foram os usuários Addy Osmani e Sindre Sorhus. Os outros 68 contribuidores contribuíram variando entre 1 e 18 relatos para adição ou modificação da ferramenta.

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%205%20-%20contribui%C3%A7%C3%A3o%20x%20tempo%20do%20usu%C3%A1rio%20mais%20colaborativo.png)
> *Imagem 5 - contribuição x tempo do usuário mais colaborativo* 


![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%206%20-%20contribui%C3%A7%C3%A3o%20x%20tempo%20do%20segundo%20usu%C3%A1rio%20mais%20colaborativo.png)
> *Imagem 6 - contribuição x tempo do segundo usuário mais colaborativo* 

---

##8. Descrição da evolução do sistema 

Abaixo, uma breve descrição das principais Releases do software, sendo que a cada Release pode-se acompanhar a evolução do projeto: 
* Release 0.6.0 : Nesta release, Web Started Kit foi completamente refatorado e repensado para utilizar o material Design Lite. O modelo padronizado é o modelo apenas textual, que acompanha o material Design Spec e é testado para integração a diversos dispositivos. Você pode utilizar números dos templates MDL ou customizar o design default para que a aplicação que está sendo desenvolvida possa atender as necessidades propostas.
* 0.6.1 : Esta release de manutenção corrige diversos erros, entre eles pode se destacar:
  * Substituição de minifiers (compressores) obsoletos com 'gulp-cssnano' e 'gulp-htmlmin'.
  * Atualização dos comandos doc para explicar as diferenças SW na configuração sw-precache.
  * Correção da localização dos arquivos main.js e main.css
  * Não utilização de importações de módulo que não são realmente utilizadas no projeto.
  * 0.6.3 : Esta release que permite o Download da ferramenta. Nesta release, vale destacar as múltiplas correções que permitem configurar a relação trabalho servidor. Outro avanço importante foi a criação de mecanismos que evitam a criação de scripts em um nível acima da raiz do projeto.
* 0.6.4 : Última release com os códigos atualizados disponíveis, permite fazer o Download da última versão estável da ferramenta.

---

##9. Frameworks 

Dentre os principais frameworks, podemos citar os seguintes: 

###9.1: Polymer:

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/imagem6_2.jpg)

O Polymer auxilia a proporcionar ao usuário experiências no que diz respeito ao potencial da plataforma web. Polymer é responsável pela criação da maioria dos componentes Web, com uma nova e poderosa funcionalidade da plataforma para estender HTML e facilitar na criação de aplicativos.

###9.2. AngularJs:

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/imagem6_1.png)

Angular.js é um plugin que permite ao desenvolvedor criar aplicações web inteligentes e dinâmicas. Ele modifica o HTML e permite estender sua sintaxe para criar componentes interativos em uma aplicação de forma simples e clara.

	<!doctype html>
	<html ng-app>
	  <head>
	    <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.8/angular.min.js"></script>
	  </head>
	  <body>
	    <div>
	      <label>Name:</label>
	      <input type="text" ng-model="yourName" placeholder="Enter a name here">
	      <hr>
	      <h1>Hello {{yourName}}!</h1>
	    </div>
	  </body>
	</html>


---

##10. Ferramentas

* Boilerplate responsivo
O Web Started Kit possui um arquivo HTML e um CSS inicial que é utilizado como base para o desenvolvimento de projetos. O HTML inclui algumas meta-tags e snippets úteis pré-prontos como Google Analytics, por exemplo.
* Guia de Estilos
O Guia de Estilos é utilizado para auxiliar na documentação dos componentes do sistema através de opções de tipografia, cores, botões, grids,  tabelas, etc.
* Recarga de dados presentes no browser em tempo real
O Web Started Kit possibilita que todo documento seja recarregado no browser automaticamente enquanto editado.
* Sincronização multi-dispositivo
Todos os seus dispositivos ficam conectados na mesma rede local, de forma que possibilite a sincronização simultânea dos navegadores, observado através de cliques, scrolls, formulários e reload. 

* Otimização de Performance
Minificação de JS, CSS, HTML e Imagens em uma ferramenta só. 
* JSHint
JSHint é uma ferramenta que analisa determinado código JavaScript para verificar possíveis problemas com sua lógica, aplicando as práticas recomendadas de codificação. A ferramenta é executada sempre que o projeto é compilado ou, se estiver executando o gulp server, sempre que uma alteração em um arquivo JavaScript é realizada.
* Suporte a SASS
Enquanto o comando serve estiver sendo executado, qualquer alteração realizada em qualquer arquivo Sass no projeto será compilada no CSS e prefixada. Depois disso, a página será recarregada com o Live Reload.

---

##11. Módulos 

O projeto possui um modularização bem definida, contendo pastas onde é possível observar a divisão e atribuição de tarefas específicas. Para demonstrar a divisão de funções a partes específicas, pode-se citar: 

* diretório base: Unidade que contém todo o projeto, possui duas sub-tarefas principais que podem ser divididas e associadas para as equipes ('app' e 'docs'). 
* docs: Diretório com os arquivos necessários para utilizar a ferramenta. Entretanto, existe um arquivo específico para cada necessidade.
* app: Pasta que contém os arquivos fonte da ferramenta. Dividido em imagens, scripts e styles. Além disto, alguns arquivos com código estão agrupados.
* styles: Arquivos que definem o layout e o estilo dos documentos são agrupados aqui.
scripts: Arquivos de processamento javascript necessários a ferramenta (possui um subdiretório sw).
* sw: Os arquivos aqui agrupados permitem fazer caching em tempo de execução (uma tarefa específica).
* images: Arquivos visuais (imagens) utilizadas pela ferramenta estão agrupados aqui.
* touch: Imagens com o propósito de ser utilizadas em alguns dispositivos como icones são agrupados aqui. 


###Árvore de Diretórios 

* diretório base
  * app
    * imagens
      * touch
    * scripts
      * sw
    * styles
  * docs

---

##12. Padrões de Projeto

Dentre as características desejáveis a Padrões de Projeto presentes no software, pode-se citar por exemplo a generalidade, que preza para que um padrão possa possibilitar usos tirando proveito de características da solução proposta. 

Além disto, a abstração dos problemas conhecidos no domínio é claramente uma preocupação. Utilizando-se funções simples com um propósito específico, é possível abstrair problemas recorrentes durante o desenvolvimento web para criar soluções de alto nível. 

O nível de detalhamento necessário para utilizar o sistema pode ser devidamente explorado. Arquivos contendo como utilizar a ferramenta de forma simples podem ser encontrados, assim como é possível compreender como a ferramenta funciona. 

--- 

##13. Arquitetura 

O Web Starter Kit utiliza a tecnologia cliente/servidor. Neste tipo de arquitetura, o processamento da informação é dividido em módulos ou processos distintos. Um processo é responsável pela manutenção da informação (servidores) e outros responsáveis pela obtenção dos dados (os clientes). 

Os processos cliente enviam pedidos para o processo servidor, e este por sua vez processa e envia os resultados dos pedidos. O servidor é composto normalmente pelos sistemas mais pesados da rede, tais como o banco de dados. Graças a possibilidade do uso de múltiplos e diferentes dispositivos para edição e acesso à páginas HTML propiciado pelo Web Starter Kit, as máquinas clientes que rodam as aplicações podem ser desktop, celulares, tablets, notebooks, entre outros. 

A imagem a seguir mostra a arquitetura simplificada da ferramenta, estando baseado em uma Camada Cliente, composta pelo desenvolvedor e usuários da aplicação, uma Camada de Aplicação, onde o Servidor WEB está localizado, e uma camada de Dados, onde todas as informações armazenadas estão localizadas. 

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%207%20-%20Arquitetura%20Cliente-Servidor.png)
> *Imagem 7 - Arquitetura Cliente-Servidor*

###13.1. Modelo de Visão 4+1: 

A arquitetura da ferramenta se baseia no Modelo de Visão 4+1, sendo elas: 

Visão Lógica: mostra as principais abstrações no sistema, como objetos ou classes de objetos. A definição de objetos com finalidades específicas (como citado na descrição) mostra a lógica com as quais a ferramenta foi desenvolvida. 

Visão de Processo: mostra em tempo de execução como o sistema é composto por processos de interação. A ferramenta se propõe a conseguir reduzir o tempo de execução mas permitindo a utilização de recursos completos. 

Visão de Desenvolvimento: mostra como o software é decomposto para o desenvolvimento. Por ser uma ferramenta bem modularizada e com usos bem definidos (como é descrito neste documento). 

Visão Física: mostra o hardware do sistema e como os componentes do software são distribuídos entre os processadores do sistema. Neste caso, parte da computação necessária é efetuada remotamente em um servidor. 

Cenários: casos de uso relacionados à aplicação. O usuário define um uso e consegue testar a ferramenta em tempo real, sem a necessidade de sequer atualizar a página. 

###13.2. Padrão de Arquitetura 

O padrão de Modelo-Visão-Controlador separa a interação dos dados do sistema. O sistema é estruturado em três componentes lógicos que interagem entre si.  

* Componente Modelo: gerencia o sistema de dados e as operações relacionadas a eles;
* Componente Visão: define e gerencia como os dados são apresentados ao usuário;
* Componente Controlador: gerencia a interação do usuário e passa essas interações para a Visão e o Modelo.

![](https://github.com/gleisonsdm/Web-Starter-Kit/blob/master/Imagem%208%20-%20A%20arquitetura%20de%20aplica%C3%A7%C3%B5es%20web%20usando%20o%20padr%C3%A3o%20MVC.png)
> *Imagem 8 - A arquitetura de aplicações web usando o padrão MVC*

---

##14. Referências
* Google Developers: 
https://developers.google.com/web/fundamentals/getting-started/web-starter-kit/?hl=pt-br 

* Git Hub - Web Starter Kit:
https://github.com/google/web-starter-kit 

* Web Design Tutplus:
https://webdesign.tutsplus.com/pt/tutorials/get-up-and-running-with-google-web-starter-kit--cms-21495 
https://webdesign.tutsplus.com/tutorials/the-command-line-for-web-design-scaffolding-new-projects--cms-23456 

* Tableless:
http://tableless.com.br/google-web-starter-kit/ 

* Wikipedia - Software Architecture:
https://en.wikipedia.org/wiki/Software_architecture 



