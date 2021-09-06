

## **JAVA**

Repositório focado no estudo de Java, abordando os principais conceitos. 

**Índice** 

 - [O que é Java?](#what-is-java)
 - [Javac](#what-is-javac)
 - [Como funciona a independência de plataforma?](#independence)
 - [JDK](#jdk)
 - [JRE](#jre)

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


**Fontes:**

 - https://www.coisadeprogramador.com.br/10-perguntas-comuns-em-uma-entrevista-de-programador/
  
 - https://www.zup.com.br/blog/java
 - https://www.devmedia.com.br/introducao-ao-java-virtual-machine-jvm/27624
 - https://www.ibm.com/br-pt/cloud/learn/jre
