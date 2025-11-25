# HTML
Minha jornada como fullstack... 
Comecando por HTML

## O que é Markup Language
É um tipo de linguagem computacional, assim como _Programming Language_ também é. 
Ex.: 
- HTML 
- XML 
- XHTML 
- SVG 
- markdown

## Ferramentas básicas para um FrontEnd Developer
### HTML
Extends for HyperText Markup Language. É a linguagem utilizaada para fazer a estrutura de uma pagina web, por exemplo. HTML é estático e usado para mostrar o conteudo/corpo da pagina.

### CSS 
Extends for Cascade Styling Sheets. É utilizada para estilizar a pagina web, pois sem o CSS o HTML é mbem rústico, apenas uma pagina preto e branco. Com o CSS é possivel mudar as cores, introduzir animações ao passar o mouse por cima de elementos, alterar tamanho de fontes e diversas outras coisas.

### JavaScript
EcmaScript6 ou JavaScript popularmente conhecido, esta é uma linguagem de programação, é o que traz a interatividade para webpages, é com ele que um site fica responsivo e dinamico.

## Como a Internet funciona
A internet é um composto de _networks_. 
_Network_ é um composto de aparelhos conectados, por exemplo em uma casa temos celulares, TVs, computadores e qualquer outra coisa que possa ter conexão a internet faz parte de uma Network local.

### O que é HTTP
HTTP extends for _HyperText Transfer Protocol_ (Protocolo de Transferência de Hiper Texto), é o que permite um navegador web fazer requests do cliente para o servidor e mandar respostas do servidor para o cliente. Existem protocolos como GET, POST, DELETE ... Também existem tipos diferentes de HTTP, como o HTTPS (Protocolo mais seguro que evita que requests sejam interceptados no meio do caminho), HTTP/2 (Versão mais usada atualmente) é uma atualização do muito utilizado HTTP/1.1 e também surgiu o HTTP/3 que ainda vem ganhando popularidade (preciso procurar saber melhor sobre este).

### Domain name
Nome do domínio, um exemplo google.com, onde ao invés de usar um ip onde só são numeros e pontos a gente usa um nome mais amigavel, facil de memorizar. Os DNS traduzem os nomes para endereços de IP, o que ajuda na acessibilidade. Por isso não precisamos buscar sites usando 197.124.122.244.

### Hosting
Hospedagem, existem algumas maneiras de hospedagem são:
#### VPS
Extends for _Virtual Private Server_ Com uma VPS você tem melhor flexibilidade de alocação de recursos. Aqui é possível aumentar ou reduzir o processamento para determinados momentos do dia, ou da semana, ou um período em especial como por exemplo Black Friday, onde muitos sites precisam de mais processamento devido ao grande tráfego online.

#### Servidor compartilhado
Neste tipo de servidor sua aplicação web está dividindo os recursos de um servidor com outras aplicações webs. O ideal é usar este tipo de servidor apenas para pequenos projetos onde não haverá grande volume de acessos, como: blog pessoal, projeto pessoal pequeno... Pois como mencionado anteriormente por ser um servidor compartilhado ele pode ter mais instabilidades caso aconteça de um dos web apps hosteados nesse server tenha um volume maior que os outros ele pode consumir mais processamento que deveria e assim limitando ainda mais os outros que ali estão. Também caso aconteça um DDOS, um ataque Hacker em algum desses apps que estão nesse mesmo server sua aplicação ficará instável também, podendo ficar offline por conta de outras aplicações...

#### Servidor dedicado
Este é o que grandes empresas necessitam para manter suas aplicações online, pois normalmente elas terão grande fluxo de dados sendo enviado, o que vai consumir muito processamento, também o fato de não querer ter instabilidade por motivos de terceiros faz desta uma boa opção para quem não pode deixar suas aplicações offline.

### DNS
Extends for Domain Name System (Sistema de Nomes de Domínios). Traduz dominios de sites como github.com para 192.30.252.0/22 por exemplo, ou seja, o usuário digita o nome do site o web browser "pergunta" ao DNS que endereço é esse o DNS então traduz e manda o endereço de IP que aponta para esse Domain Name. 

### Browsers
Navegadores, são eles:
- Chrome
- Safari
- Opera
- Firefox
Estes que processam os arquivos HTML, CSS, JavaScript (engine V8) e mostram para o usuario.

### SEO
Search Engine Optimization (Otimização de mecanismos de procura), é a prática de melhorar sua página web para que mecanismos de busca a encontrem mais facilmente, por exemplo uma pagina bem estruturada com as devidas tags e com um conteudo interessante é essencial para ficar nas primeiras paginas dos sites de pesquisa. Por isso é importante trabalhar bem SEO para que sua webpage se saia bem.

#### TAGS HTML
### ```<head>```
A tag ```<head>``` é onde ficam os metadados da pagina web, é onde se colocam tags como ```<link>``` que pode linkar ao _CSS_ da pagina, ao _JS_, etc. Também pode 
