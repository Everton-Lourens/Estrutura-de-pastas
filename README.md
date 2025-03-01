# Estrutura de Pastas para Projetos Node.js

Este repositório tem como objetivo fornecer uma estrutura organizada e escalável para projetos Node.js.

## 📌 Referência
Para mais detalhes sobre boas práticas de organização de projetos Node.js, confira este artigo:
[Como organizar e estruturar projetos com Node.js](https://medium.com/@stroklabs/como-organizar-e-estruturar-projetos-com-node-js-4845be004899)

## 📂 Estrutura do Projeto

```
📦 src
│   ├── app.js          # Classe principal do aplicativo
│   ├── server.js       # Inicialização do servidor Express
│
├── api                 # Camada de aplicação
│   ├── controllers     # Funções responsáveis pelo fluxo das rotas
│   ├── models          # Definições dos modelos do banco de dados
│   ├── services        # Regras de negócio e lógica da aplicação
│   ├── subscribers     # Manipuladores de eventos assíncronos
│   ├── repositories*   # Query builders e acesso a dados
│
├── config              # Configurações do projeto e variáveis de ambiente
├── jobs                # Tarefas agendadas e rotinas
├── loaders             # Módulos de inicialização do app
├── utils               # Funções auxiliares e pequenos trechos de código reutilizáveis
├── helpers             # Trechos de arquitetura para facilitar a organização do código
├── routes              # Definição de rotas Express
├── types               # Definições de tipos (d.ts) para TypeScript
```

## 🚀 Como Usar
=> Clone este repositório
   ```sh
   git clone https://github.com/Everton-Lourens/Estrutura-de-pastas
   ```

## 💡 Contribuição
Sinta-se à vontade para abrir issues e enviar pull requests para melhorias na estrutura ou documentação.

---

Mantenha seu projeto bem organizado e escalável! 🚀

