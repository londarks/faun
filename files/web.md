### Como funciona a Web?

Computadores conectados à web são chamados clientes e servidores. Um diagrama simplificado de como eles interagem pode ter essa aparência:

<img src="https://mdn.mozillademos.org/files/17297/simple-client-server.png">

<li>Clientes são os típicos dispositivos conectados à internet dos usuários da web (por exemplo, seu computador conectado ao seu Wi-Fi ou seu telefone conectado à sua rede móvel) e programas de acesso à Web disponíveis nesses dispositivos (geralmente um navegador como Firefox ou Chrome).
Servidores são computadores que armazenam páginas, sites ou aplicativos. ..]


<li>Quando o dispositivo de um cliente quer acessar uma página, uma cópia dela é baixada do servidor para a máquina do cliente para ser apresentada no navegador web do usuário.


<li>O cliente e o servidor que descrevemos acima não contam toda a história. Existem muitas outras partes envolvidas, e vamos descrevê-las abaixo.

<li>Por enquanto, vamos imaginar que a web é uma estrada. Em um extremo da estrada, temos o cliente, que é como sua casa. No extremo oposto, temos o servidor, que é como uma loja onde você quer comprar algo.

<h1 align="center">
  <img src="https://mdn.mozillademos.org/files/9749/road.jpg"/>
</h1>


Além do cliente e do servidor, também precisamos dizer oi para:


<li>Sua conexão de Internet: permite que você mande e receba dados na web. É basicamente como a rua entre sua casa e a loja.</li>
<p>
<li>TCP/IP: Protocolo de Controle de Transmissão e Protocolo de Internet (Transmission Control Protocol e Internet Protocol) são protocolos de comunicação que definem como os dados trafegam pela web. São como os mecanismos de transporte que te permitem ir ao shopping, fazer um pedido e comprar seus produtos. Em nosso exemplo, é como um carro ou uma bicicleta (ou qualquer outra coisa que você possa usar).</li>
<p>

<li>DNS: Servidor de Nome de Domínio (Domain Name Servers) são como um catálogo de endereços para sites. Quando você digita um endereço web no seu navegador, o navegador procura no servidor de DNS para localizar o endereço real do site, antes que ele possa recuperar o site. O navegador precisa encontrar em qual servidor web a página está hospedada para que ele possa mandar mensagens HTTP ao lugar certo (veja abaixo). Isso é como pesquisar o endereço da loja para que você possa entrar em contato.</li>
<p>
<li>HTTP: Protocolo de Transferência de Hypertexto (Hypertext Transfer Protocol) é um protocolo de aplicação que define uma linguagem para clientes e servidores se comunicarem entre si. É como a linguagem que você usa para encomendar seus produtos.</li>
<p>

<li>1. O navegador vai para o servidor de DNS e encontra o endereço verdadeiro de onde o site está hospedado (você encontra o endereço da loja).</li><p>

<li>2. O navegador manda uma mensagem de requisição HTTP para o servidor, pedindo que envie uma cópia do site ao cliente (você vai até a loja e pede suas mercadorias). Esta mensagem e todos os outros dados enviados entre o cliente e o servidor são enviados pela sua conexão à internet usando TCP/IP.</li><p>

<li>3. Se o servidor aprovar a requisição do cliente, o servidor enviará ao cliente uma mensagem "200 OK", que significa "Claro que você pode ver esse site! Aqui está" e então começa a enviar os arquivos do site para o navegador como uma série de pequenos pedaços chamados pacotes de dados (a loja dá a você as suas mercadorias e você as traz para sua casa).</li><p>

<li>4. O navegador monta os pequenos pedaços em um site completo e o mostra a você (as mercadorias chegam à sua porta — novas coisas brilhantes e incríveis!).</li><p>


pesquise um pouco sobre como funciona a web para que entenda o conceito e possa criar uma aplicação segura e viavel para os usuarios 