# RPG0018 - Por que não paralelizar

Implementação de sistema servidor/cliente com Java Sockets, utilizando comunicação síncrona e assíncrona com Threads, acesso ao banco de dados via JPA e manipulação paralela de conexões.

---

## 🎯 Objetivo da Prática

- Criar servidores Java com base em Sockets
- Criar clientes síncronos para servidores com base em Sockets
- Criar clientes assíncronos para servidores com base em Sockets
- Utilizar Threads para implementar processos paralelos no servidor
- Integrar o servidor a um banco de dados utilizando JPA
- Garantir o isolamento de acesso ao banco, mantendo a lógica somente no servidor

---

## 📍 Contexto

A prática foi desenvolvida individualmente como parte do Nível 5 do Mundo Atual, focando no uso de Threads e comunicação em rede.

---

## 💻 Tecnologias e Materiais Utilizados

- Java JDK
- IDE NetBeans
- SQL Server com banco de dados da prática anterior (loja)
- SQL Server Management Studio
- JPA (Java Persistence API)
- Navegador (para testes de conectividade e acesso à documentação)
- Threads Java
- Socket API (ServerSocket, Socket)

---

## 📦 Execução

- Criação de servidor com ServerSocket e Threads para atender múltiplos clientes simultaneamente
- Cliente síncrono: comunicação bloqueante com o servidor
- Cliente assíncrono: utilização de Thread para envio e recebimento paralelo
- Transmissão de dados entre cliente e servidor usando ObjectInputStream e ObjectOutputStream
- Persistência dos dados com entidades JPA no servidor
- Isolamento do acesso ao banco de dados — clientes não têm acesso direto
- Operações implementadas: Listagem, Entrada e Saída de produtos (com base em IDs e quantidade)

---

## 📊 Resultados

Foram validadas as seguintes funcionalidades:

- Comunicação via Socket entre cliente e servidor funcionando corretamente
- Cliente síncrono recebendo e enviando comandos de forma sequencial
- Cliente assíncrono utilizando Threads para resposta paralela
- Threads no servidor permitindo múltiplas conexões simultâneas
- Manipulação de dados do banco com sucesso via JPA
- Interface via terminal clara e funcional para inserção e listagem de dados

---

## ✅ Autor

Pedro Henrique Marques Medeiros Pinho
