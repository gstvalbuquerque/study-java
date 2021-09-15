

## **JAVA**

Repositório focado no estudo de Java, abordando os principais conceitos. 

**Índice** 

 - [O que é Java?](#what-is-java)
 - [Javac](#what-is-javac)
 - [Como funciona a independência de plataforma?](#independence)
 - [JDK](#jdk)
 - [JRE](#jre)
 - [JAVA SE](#javase)
 - [JAVA EE](#javaee)
 - [Princípios da orientação a objetos](#oo)


**<a name="what-is-java"></a>O que é Java?**
**Java** é uma linguagem de programação segura de alto nível orientada a objetos e atualmente é uma das linguagens mais utilizadas do mundo. 
Algumas de suas principais características são:

 - Orientação à Objetos (Não totalmente);
 - Funcionamento independente de plataforma;
 - Tipagem forte;
 - Imperativa.

**<a name="what-is-javac"></a>Javac**

**Javac** é o compilador padrão do **Java** e faz parte do **JDK**. É ele quem cria o **bytecode** que vai ser utilizado pela **JVM**.

**<a name="independence"></a>Como funciona a independência de plataforma?**

Através de um emulador conhecido como a **Máquina Virtual Java (JVM)** , o Java consegue ter a independência de plataforma. 
Além de interpretar o código, a **JVM** também é responsável pela execução de pilhas, threads, gerenciamento de memória e etc.  
O que acontece é que o **ByteCode** que é gerado pelo compilador Java (javac) é traduzido pela Virtual Machine para cada máquina em questão. 

![Esquema de Funcionamento da JVM](https://arquivo.devmedia.com.br/artigos/Allan_Romanato/JavaVirtualMachine/JavaVirtualMachine2.jpg)

 **<a name="jdk"></a> JDK**
 
**Java Development Kit (JDK)** é um pacote disponibilizado pela Oracle que nos permite desenvolver uma aplicação Java.

**<a name="jre"></a> JRE**

o **Java Runtime Environment (JRE)** é o que possibilita que um programa Java seja executado em qualquer sistema operacional sem modificação.

**<a name="javase"></a>JAVA SE**

O Java Standard Edition (Java SE) é o requisito mínimo para rodar uma aplicação Java. Ele engloba coisas como todos os fundamentos do Java e a API de desenvolvimento desktop.

**<a name="javaee"></a>JAVA EE**

O Java Enterprise Edition (Java EE) foi criado para estender o Java SE através da inserção de especificações que definem  os recursos comumente usados ​​por aplicativos corporativos.

**<a name="oo"></a>Princípios da Orientação a Objetos**

É um paradigma de programação baseado em interações entre unidades de software (objetos), tentando aproximar-se do mundo real. Abstração, encapsulamento, herança e polimorfismo são os princípios da orientação a objeto.
 
 - **Abstração**
 
	 É o que nós esperamos que um objeto irá realizar dentro de nosso sistema. Nessa abstração devemos levar em conta três pontos.
	 O primeiro ponto é darmos uma identidade única ao objeto que iremos criar. 
	 O segundo ponto diz respeito as propriedades do objeto. Ou seja, quais são as suas características.
	 O ultimo ponto refere-se às ações que nosso objeto irá executar. Essas ações, ou eventos, são chamados métodos.
 - **Encapsulamento**
 
	 Adiciona segurança à aplicação pelo fato de esconder as propriedades, criando algo como uma caixa preta.
	 A maior parte das linguagens orientadas a objetos implementam o encapsulamento baseado em propriedades privadas, ligadas a métodos especiais chamados _getters_ e _setters_, que irão retornar e setar o valor da propriedade, respectivamente.
	  
 - **Herança**
 
 Facilita muito o reuso de código, otimizando a produção da aplicação em tempo e linhas de código. A herança permite criar uma classe a partir de uma já existente. A sua principal vantagem é a capacidade para definir novos atributos e métodos para a subclasse, que somam com os atributos e métodos herdados.
 
 - **Polimorfismo**
 
 O polimorfismo consiste na alteração do funcionamento interno de um método herdado de um objeto pai. Com isto, os mesmos atributos e objetos podem ser utilizados em objetos distintos, porém, com implementações lógicas diferentes.



**Fontes:**

 - https://www.coisadeprogramador.com.br/10-perguntas-comuns-em-uma-entrevista-de-programador/
  
 - https://www.zup.com.br/blog/java
 - https://www.devmedia.com.br/introducao-ao-java-virtual-machine-jvm/27624
 - https://www.ibm.com/br-pt/cloud/learn/jre
 - https://auth0.com/blog/java-platform-and-java-community-process-overview/#Java-Standard-Edition--Java-SE-
 - https://www.devmedia.com.br/os-4-pilares-da-programacao-orientada-a-objetos/9264
 - https://br.ccm.net/contents/414-poo-heranca
