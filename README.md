# intro-wemos_D1
<h3>Introdução para a placa wemos D1 R2</h3>  
  
A WeMos D1 é uma placa compátivel com o arduino uno. Ela utiliza o SoC (system on chip) ESP8266EX. <br/>
Esta placa conta com wi-fi integrado, sendo uma opção acessível para IoT (internet of things).  <br/>
<img width="50%" src="https://user-images.githubusercontent.com/53026536/69000547-24082000-08b0-11ea-93b5-ef82466e5f68.jpg"> <br/>
<a href="https://wiki.wemos.cc/_media/products:d1:d1_v2.0.0.pdf">Datasheet da placa</a> <br/> <br/>
<strong>Especificações:</strong>
<ul>
<li>Baseada no ESP8266EX</li>  
<li>11 pinos de entrada e saída (com pwm)</li>  
<li>1 entrada analógica (entrada máxima de 3,3V)</li>  
<li>Conexão micro USB</li>  
<li>Aceita alimentação externa entre 9 e 24V.</li>  
<li>Saída de 5V 1A</li>  
<li>Compatível com Arduino</li>  
<li>Compatível com nodemcu</li>  
<li>Armazenamento de 4Mb em flash</li>  
</ul> <br/> 

Fonte: <a href="https://wiki.wemos.cc/products:d1:d1">wiki.wemos.cc</a> <br/> 

<br/> 
<p>Esta placa é visualmente similar ao arduino e pode ser programada na IDE do arduino usando a programação padrão, o C++. <p/>

<p>Ela tem como base o arduino uno, e funciona de forma similar. Porém com uma conexão a rede wifi inclusa. 
Seu custo varia entre 20 e 30 reais em sites chineses como o aliexpress. No brasil você encontra facilmente por volta de 50 reais. <p/>

<p>Adquiri a minha aqui: <a href="https://pt.aliexpress.com/item/32758176555.html">https://pt.aliexpress.com/item/32758176555.html</a>
<p/>

>Custou R$25 e o frete saiu grátis

<h1>Guia de uso</h1>
<p>Para programar a placa utilizando a IDE do arduino você precisa adicionar o suporte para o esp8266.</p>
<h4>1° passo</h4>
<p>Abra a ide do arduino.</p>

>Se não ainda tiver instalado, clique <a href="https://www.arduino.cc/en/main/software">AQUI</a>
>e escolha o sistema operacional de seu computador.

<p>Abra o menu e vá em File>Preferences</p>
<p>Procure por "Additional Boards Manager URLs", e insirira esse URL: </p>
<code>http://arduino.esp8266.com/stable/package_esp8266com_index.json</code>
<p>Este campo pode ser preenchido com várias urls, basta separá-las por vírgulas <br/>
 Clique em OK para fechar essa aba</p>

<h4>2° passo</h4>
<p>Abra o menu novamente e vá em "Tools>Board>Board Manager"</p>
<p>Logo após procure por esp8266 e clique em instalar. Aguarde o processo de instalação</p>

<h4>3° passo</h4>
<p>Com a placa instalada, basta seleciona-lá em "boards"</p>
<p>Procure por Wemos D1 e selecione</p>
<p>Sua placa estará pronta para uso :)</p>


