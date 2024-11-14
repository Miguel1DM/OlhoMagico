# Olho Mágico - Sistema de Gerenciamento de Condomínio

**Olho Mágico** é um sistema de gerenciamento de condomínio focado na comunicação eficiente entre o prédio e os moradores. Ao invés de priorizar a interação entre os próprios moradores, o aplicativo oferece funcionalidades voltadas para a gestão de processos administrativos, controle de visitantes e encomendas, agendamento de espaços comuns, entre outras funções essenciais para a administração de um condomínio.

## 📋 Funcionalidades

O sistema **Olho Mágico** possui diferentes tipos de usuários, cada um com permissões específicas:

### 🚪 **Porteiro**
- Registrar e gerenciar encomendas.
- Verificar e autorizar a entrada de visitantes na portaria.

### 🏢 **Síndico**
- Aprovar ou negar agendamentos feitos pelos moradores.
- Criar e gerenciar avisos internos, reformas, reuniões e outros comunicados.
- Cadastrar documentos oficiais do edifício.
- Aprovar ou negar anúncios internos criados pelos moradores.
- Gerenciar vendas internas e outros processos administrativos.
- Registrar emails de moradores e associá-los aos apartamentos e blocos para acesso ao sistema.

### 🏠 **Morador**
- Agendar espaços comuns, como salões de festas e churrasqueiras.
- Criar e publicar anúncios (necessitam da aprovação do síndico).
- Visualizar e retirar encomendas utilizando um código de retirada.
- Acessar avisos criados pelo síndico.
- Registrar visitantes e prestadores de serviços, incluindo habilitar ou desabilitar a entrada deles.
- Registrar veículos para controle de entrada e saída.

### 🌐 Acesso Online

Você pode testar o sistema diretamente na versão hospedada:

- **Link para o sistema hospedado:** [Acesse o Olho Mágico](http://link-da-pagina-hospedada.com)

### 👤 Logins Globais

Para testar o sistema com diferentes tipos de usuários, você pode usar os logins globais a seguir. Todos eles têm permissões específicas para o tipo de usuário que representam:

- **Porteiro:**
  - **Email:** porteiro@olhomagico.com
  - **Senha:** porteiro123

- **Síndico:**
  - **Email:** sindico@olhomagico.com
  - **Senha:** sindico123

- **Morador:**
  - **Email:** morador@olhomagico.com
  - **Senha:** morador123

Esses logins permitem que você acesse o sistema e explore as funcionalidades disponíveis para cada tipo de usuário.

## 🚀 Tecnologias

- [Node.js](https://nodejs.org/) (Back-end)
- [MySQL](https://www.mysql.com/) (para banco de dados)
- [Npm](https://www.npmjs.com/) (gerenciador de pacotes)
- **Firebase Cloud Messaging (FCM)** (Push Notifications)
- [Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) (Hospedagem de toda a infraestrutura do projeto)
