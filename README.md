# Instalação JAVA IDEs
Guia de instalação de IDEs JAVA

<!-- 
## Links úteis
[Sintaxe básica Markdown] (https://www.youtube.com/watch?v=grk4QUDveFw) -->


<!-- !toc (minlevel=2 omit="Table of Contents") -->

<!-- * [O que é um IDE?](#O que é um IDE?)
* [Pré-requisitos](#pré-requisitos)
* [Linux](#linux)
* [Windows](#windows) -->


<!-- toc! -->


<div align="center">
  <h2> :octocat: Contribua se gostar do conteúdo! ⚠️ </h2>
	Este conteúdo foi criado para ajudar pessoas então, se possível, contribua também: <br><br>
  ⭐ Curta o repositório clicando na estrela. <br>
  🔱 Dê Fork no repositório para ter uma cópia dele. <br>
  🔗 Compartilhe com quem precisa ver esse conteúdo. <br>
  🛑 Envie uma mensagem se encontrar algum problema. <br>
</div>


</center>
  
## :pushpin: O que é um IDE?

IDE, Integrated Development Environment ou Ambiente de Desenvolvimento Integrado, é um software que reúne ferramentas para desenvolvimento de software em uma única GUI (Graphical User Interface ou Interface Gráfica de Usuário) com o objetivo de facilitar e agilizar a criação de software.




## :pushpin: Pré-requisitos
  
- [x] Computador com sistema operacional Windows e/ou Linux

- [x] Conta no GitHub




## LINUX

⚠️ EM CONSTRUÇÃO!!! 🚧




## WINDOWS

<details>
	<summary> ⬜ 1. Abra o cmd e verifique se o Java está instalado e, caso esteja, a versão do Java. </summary>
<p>

🔹 1.1. Na barra de pesquisa digite "cmd" e aperte Enter. / Ou aperte Tecla Windows + R, digite "cmd" e aperte OK.
  
📍 Isso abrirá o terminal do Windows na sua pasta de usuário: C:\Users\seu-usuario

🔹 1.2. Digite "java --version" e aperte Enter.

📍 Caso o Java não esteja instalado, aparecerá uma mensagem de erro. E caso esteja instalado, aparecerá a versão instalada.

---
	
</p>
</details>

<details>
	<summary> ⬜ 2. Faça download do JDK (Java Development Kit ou Kit de Desenvolvimento Java) da Azul. </summary>
<p>

🔹 2.1. Entre no site da <a href="https://www.azul.com/downloads/?package=jdk" target="_blank"><strong>Azul</strong></a>

🔹 2.2. Clique em "Choose your download" na página inicial.

🔹 2.3. Procure por "Java 11 (LTS)" para Windows de acordo com seu sistema operacional ("x86 32-bit ou x86 64-bit).

⚠️ [Mas como saber se é 32 ou 64bits?]

🔹 2.4. Faça download do arquivo .zip do JDK 11 (LTS).
	
---

</p>
</details>

<details>
	<summary> ⬜ 3. Crie a pasta "Java" caso não exista. </summary>
<p>

🔹 3.1. Abra o Explorador de Arquivos do Windows e vá até a pasta C:\Arquivos de Programas ou C:\Program Files

🔹 3.2. Se não houver a pasta "Java" nesse diretório, crie (Botão direito do mouse > Novo > Pasta).

🔹 3.3. 
	
---

</p>
</details>

<details>
	<summary> ⬜ 4. Descompacte o arquivo na pasta correta. </summary>
<p>

🔹 4.1. No Explorador de Arquivos, vá até a pasta de downloads em: Este Computador > Downloads
  
🔹 4.2. Clique com o botão direito sobre o arquivo baixado do JDK Zulu e clique em "Extrair tudo" (ou "Extract files").
  
🔹 4.3. Ache a pasta "Java" que está em "Arquivos de Programas" (C:\Program Files\Java) e descompacte o arquivo .zip do JDK Zulu 11 dentro dela.
	
🔹 4.4. Entre na pasta em que você descompactou o JDK (C:\Program Files\Java\zulu11...) e copie o endereço dela.

---
	
</p>
</details>

<details>
	<summary> ⬜ 5. Configure as variáveis de ambiente do sistema. </summary>
<p>

🔹 5.1. Na barra de pesquisa digite "var" e aperte Enter ou clique em "Editar as variáveis de ambiente do sistema".
  
📍 Isso abrirá a janela de Propriedades do Sistema.

🔹 5.2. Na aba "Avançado", clique em "Variáveis de Ambiente".
	
📍 Isso abrirá a janela de Variáveis de Ambiente.

🔹 5.3. Na janela "Variáveis de Ambiente", em "Variáveis do sistema", clique em "Novo".

📍 Isso abrirá a janela de Nova Variável do Sistema.
  
🔹 5.4. Na janela de Nova Variável do Sistema, em "Nome da variável" digite "JAVA_HOME" e em "Valor da variável" cole o endereço da pasta que você copiou (no passo 4.4) e aperte OK.

🔹 5.5. Na janela "Variáveis de Ambiente", em "Variáveis do sistema", clique em "Path" > Editar.

📍 Isso abrirá a janela de Editar a variável de ambiente.
	
🔹 5.6. Clique em "Novo", cole o endereço que você copiou no passo 4.4 e acrescente no final dele "\bin".
	
📍 Ficará algo como C:\Program Files\Java\zulu11.52.13-ca-jdk11.0.13-win_x64\bin
	
Depois clique em "Mover para cima" até que chegue no topo e clique em OK.
	
---
	
</p>
</details>

<details>
	<summary> ⬜ 6. Repita o passo 1 para verificar se o Java foi instalado corretamente. </summary>
<p>

	📍 Caso tenha sido instalado corretamente, ao digitar o comando "java --version" no cmd,
	deve aparecer algo como:
	
	C:\Users\ASUS>java --version
	openjdk 11.0.13 2021-10-19 LTS
	OpenJDK Runtime Environment Zulu11.52+13-CA (build 11.0.13+8-LTS)
	OpenJDK 64-Bit Server VM Zulu11.52+13-CA (build 11.0.13+8-LTS, mixed mode)

---
	
</p>
</details>







<details>
	<summary> ⬜ 6. Repita o passo 1 para verificar se o Java foi instalado corretamente. </summary>
<p>

🔹 5.1. Na barra de pesquisa digite "var" e aperte Enter ou clique em "Editar as variáveis de ambiente do sistema".
  
📍 Isso abrirá a janela de Propriedades do Sistema.


Microsoft Windows [versão 10.0.19043.1288]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\ASUS>java --version
openjdk 11.0.13 2021-10-19 LTS
OpenJDK Runtime Environment Zulu11.52+13-CA (build 11.0.13+8-LTS)
OpenJDK 64-Bit Server VM Zulu11.52+13-CA (build 11.0.13+8-LTS, mixed mode)

C:\Users\ASUS>

---
	
</p>
</details>

⬜ 

🔹 
  
🔹 
  
	📍 

	🔹 

	📍 


⬜ 

🔹 Clique na barra de endereço da pasta e copie o caminho dela (C:\Program Files\Java).

🔹 

🔹 

🔹 

🔹 

🔹 

⬜ 

🔹 

🔹 

🔹 

🔹 

🔹 

🔹 <strong>3.</strong> Vá no drive C://Arquivo de Programas

🔹 <strong>4.</strong> Caso não tenha um diretório com o nome Java, crie

🔹 <strong>5.</strong>  Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

🔹 <strong>6.</strong> Vamos configurar o ambiente JAVA_HOME:

<h1>Dominando IDEs Java </h1>

<div align="center">	
▶️ <a href="https://www.youtube.com/watch?v=wcIm916zk9w&lc=UgwDmJkoCf5M9Pf66ll4AaABAg">Como criar um Access Token para se conectar com o GitHub</a></div>
	
<h2> 🚦 Guia </h2>

IDEs mais conhecidas para desenvolvimento Java: Eclipse IDE e IntelliJ IDEA IDE <br>




------------

Feito com 💟 e ☕ por [Patrícia Vitor](https://www.linkedin.com/in/patriciacvitor/).
