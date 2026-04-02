

<h1 align="center">🕹️ Projeto Conta Bancária</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-concluído-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-17+-purple?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white" />
</p>

##

## 📚 Sobre o Projeto

O Projeto Conta Bancária é uma aplicação Java que simula as principais operações de um sistema bancário, implementada utilizando a arquitetura MVC (Model-View-Controller). O projeto serve para praticar conceitos de Programação Orientada a Objetos, separação de responsabilidades e organização de código em camadas.

##

## ⚙️ Funcionalidades

- Cadastro e gerenciamento de contas bancárias;  
- Depósitos, saques e transferências; 
- Consulta de saldo;  
- Tratamento de exceções para operações inválidas;  

##

## 🛠️ Tecnologias Utilizadas

- Java;
- Eclipse IDE;  
- Arquitetura MVC (Model-View-Controller);  
- Programação Orientada a Objetos (POO);  

##

## 📁 Estrutura do Projeto 
```
Projeto_Conta_Bancaria/
├── src/
│ └── br.com.banco/
│ ├── model/ 
│ │ ├── Conta.java
│ │ ├── Cliente.java
│ │ ├── ContaCorrente.java
│ │ ├── ContaPoupanca.java
│ │ └── excecoes/ 
│ ├── view/
│ │ └── Menu.java 
│ ├── controller/ 
│ │ ├── ContaController.java
│ │ └── ClienteController.java
│ └── Main.java 
├── bin/ 
├── .settings/ 
├── .classpath 
└── .project 
```

### 📄 Descrição das Camadas

- **Model:** Representa os dados do sistema e as regras de negócio, como as classes `Conta`, `Cliente` e suas variações. Também contém exceções específicas para validar operações.  
- **View:** Responsável pela interação com o usuário. Neste projeto, é uma interface via console que apresenta menus e recebe entradas.  
- **Controller:** Faz a mediação entre Model e View. Controla o fluxo da aplicação, manipula dados e atualiza a interface conforme necessário.  

##

## 🚀 Como Executar o Projeto

1. Clone o repositório:  
   ```
   git clone https://github.com/CahTarine/Conta-Bancaria.git
   ```
2. Abra o Eclipse IDE.

3. Importe o projeto:

- File > Import > Existing Projects into Workspace

- Selecione a pasta do projeto clonado

4. Compile e execute a classe Main para iniciar o programa.

##

## 👩🏻‍💻 Desenvolvedora

Feito com 💜 por Camille Tarine!  
