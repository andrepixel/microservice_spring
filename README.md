<p align="center">
<img src="https://github.com/andrepixel/microservice_spring/blob/main/javakotlin.png" border="10"/>
</p>

> Esse projeto visa um estudo profundo de Microservice usando Spring com Java e Kotlin, usando Design Patterns, e melhoria continua.

### Arquitetura

<p align="center">
<img src="https://github.com/andrepixel/microservice_spring/blob/main/Diagram_project_microservice_spring.drawio.svg" border="10"/>
</p>

### Problema

  Vamos supor que tivessemos trabalhando em uma empresa que trabalha com tickets para cinemas. Trabalhamos em uma equipe "X" onde fazemos parte de um pequeno fluxo, dentre vários na arquitetura da empresa. 

### Solução

  O nosso fluxo tem como premissa, puxar todos ticket que estão em uma fila do **Kafka(all_tickets)**, puxar todos eles e fazer pequenas validações, e salvar eles em um banco de dados, que por ter um fluxo gigante de informações foi escolhido o **MongoDB**. Feito devidas validações iniciais dos **Tickets**, teremos 3 projetos que são **Workers**, que irão fazer um tratamento especial para cada **Ticket** correspondente para cada cinema, e enviar para outras filas do **Kafka**.

> Essa arquitetura contém 6 projetos; todos eles são microservice. Estamos simulando um fluxo onde temos o **Primeiro Projeto** como um microservice que não temos conhecimento, que algo normal em uma empresa, não conhecermos tudo da arquitetura. Esse **Primeiro Projeto**, é necessário a sua criação para fazer sentido na representação dos outros.

#### [Primeiro Projeto](https://github.com/andrepixel/microservice_spring_project_1)

 consiste

--------------------------------------------------------------------------------------------------------------------

#### Segundo Projeto

  consiste

--------------------------------------------------------------------------------------------------------------------

#### [Terceiro Projeto]() 

  consiste

--------------------------------------------------------------------------------------------------------------------

#### Quarto Projeto 

  consiste

--------------------------------------------------------------------------------------------------------------------

#### Quinto Projeto

  consiste

--------------------------------------------------------------------------------------------------------------------

#### Sexto Projeto

  consiste

--------------------------------------------------------------------------------------------------------------------
