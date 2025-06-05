# 💰 GerFinance

<div align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow" alt="Status: Em Desenvolvimento">
  <img src="https://img.shields.io/badge/versão-1.0.0-blue" alt="Versão: 1.0.0">
  <img src="https://img.shields.io/badge/licença-MIT-green" alt="Licença: MIT">
</div>

<br>

Sistema de gerenciamento financeiro desenvolvido para controle de fichas financeiras, pagamentos e relatórios. Ideal para pequenas empresas e profissionais autônomos que precisam gerenciar seus recebimentos de forma eficiente.

## ✨ Funcionalidades

- 🔐 Autenticação de usuários com JWT
- 📊 Dashboard interativo de fichas financeiras
- 📝 Criação, edição e exclusão de fichas
- 💳 Controle de status de pagamento
- 📈 Visualização de gráficos e relatórios
- 📄 Geração de PDF das fichas
- 💵 Sistema de parcelamento com entrada
- 💰 Diferentes métodos de pagamento (PIX, Cartão, Boleto, Dinheiro)
- 📅 Cálculo automático de juros para pagamentos atrasados
- 👥 Sistema de administração com diferentes níveis de acesso
- 👤 Gerenciamento de usuários (admin/dev)
- 🌙 Tema claro/escuro
- ⏰ Auto-logout por inatividade
- 📱 Paginação eficiente para melhor navegação

## 🛠️ Tecnologias Utilizadas

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white" alt="JWT">
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron">
</div>

## 🚀 Instalação

1. Clone o repositório
   ```bash
   git clone https://github.com/seu-usuario/gerFinanceV1.git

   ```
2. Entre no diretório do aplicativo
   ```bash
      cd gerFinanceV1
   ```

3. Instale as dependências
   ```bash
   npm install
   ```

4. Inicie o aplicativo
   ```bash
   npm start
   ```

## 📁 Estrutura do Projeto

```
gerFinanceV1/
├── assets/             # Recursos estáticos (imagens, ícones)
├── backend/            # Código do servidor
│   ├── config/         # Configurações      
│   └── services/       # Serviços da API
├── docs/               # Documentação
├── frontend/           # Interface do usuário
│   ├── css/            # Estilos
│   ├── html/           # Páginas HTML
│   └── js/             # Scripts JavaScript
│       ├── dashboard/  # Scripts do dashboard
│       ├── payments/   # Scripts de pagamentos
│       └── settings/   # Scripts de configurações
├── electron.js         # Arquivo principal do Electron (servidor + interface)
├── preload.js          # Script de pré-carregamento do Electron
└── package.json        # Dependências e scripts
```

📄 Arquivos Principais
- electron.js: Arquivo principal da aplicação que integra o servidor Express com a interface Electron. Contém todas as rotas da API, configuração do banco de dados e gerenciamento de janelas.

- preload.js: Script de pré-carregamento que fornece uma ponte segura entre o processo de renderização (frontend) e o processo principal (backend) do Electron, permitindo comunicação entre os dois contextos.

📊 Fluxo de Dados
1. O usuário se autentica no sistema

2. Após autenticação, o token JWT é armazenado localmente

3. O dashboard carrega as fichas do usuário autenticado

4. O usuário pode criar, editar, visualizar e excluir fichas

5. Os pagamentos podem ser registrados e acompanhados

6. Relatórios e gráficos são gerados com base nos dados


## 👥 Níveis de Acesso

- **Desenvolvedor (dev)**: Acesso total ao sistema, incluindo todas as fichas e usuários
- **Administrador (admin)**: Pode gerenciar usuários comuns e visualizar suas fichas
- **Usuário (user)**: Acesso apenas às suas próprias fichas

## 💳 Métodos de Pagamento

- **PIX**: Permite entrada, sem parcelamento
- **Cartão**: 
  - Crédito: Permite entrada e parcelamento
  - Débito: Pagamento único
- **Boleto**: Permite entrada, sem parcelamento
- **Dinheiro**: Permite entrada, sem parcelamento

## 🆕 Melhorias Recentes

✅ Sistema de auto-logout por inatividade

✅ Paginação avançada no dashboard e página de pagamentos

✅ Correção no sistema de pagamentos parciais

✅ Melhorias na visualização de fichas com pagamentos pendentes

✅ Implementação de tema claro/escuro

✅ Sistema de notificações para pagamentos pendentes

✅ Adicionado suporte para entrada e parcelamento

✅ Implementado sistema de status de pagamento

✅ Adicionada página de visualização de pagamentos com gráficos

✅ Corrigido problema de formatação de valores monetários

✅ Implementada geração de PDF das fichas

✅ Melhorada a interface do menu de navegação



## 🔜 Melhorias Futuras

📋 Desenvolver a aba de contratos por completo

🔎 Adicionar filtros avançados

📊 Implementar relatórios personalizados

💾 Implementar sistema de backup automático

📈 Adicionar dashboard com métricas avançadas

📱 Desenvolver aplicativo móvel

🔔 Implementar sistema de lembretes para pagamentos


## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.


## 👨‍💻 Autor

Desenvolvido por Bruno Luiz - Lucas Pereira

---

<div align="center">
  <sub>Feito com ❤️ para facilitar o gerenciamento financeiro</sub>
</div>
