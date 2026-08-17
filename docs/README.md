
``
██╗  ██╗██╗██████╗ ███████╗██████╗ ███╗   ███╗███████╗██████╗  ██████╗ █████╗ ██████╗  ██████╗ ███████╗██╗
██║  ██║██║██╔══██╗██╔════╝██╔══██╗████╗ ████║██╔════╝██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔═══██╗██╔════╝██║
███████║██║██████╔╝█████╗  ██████╔╝██╔████╔██║█████╗  ██████╔╝██║     ███████║██║  ██║██║   ██║███████╗██║
██╔══██║██║██╔═══╝ ██╔══╝  ██╔══██╗██║╚██╔╝██║██╔══╝  ██╔══██╗██║     ██╔══██║██║  ██║██║   ██║╚════██║██║
██║  ██║██║██║     ███████╗██║  ██║██║ ╚═╝ ██║███████╗██║  ██║╚██████╗██║  ██║██████╔╝╚██████╔╝███████║██║
╚═╝  ╚═╝╚═╝╚═╝     ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚══════╝╚═╝
```


📦 SISTEMA DE CONTROLE DE ESTOQUE
│
├── 🟣 EPIC — Gerenciamento de Produtos
│   │
│   ├── 👤 Cadastrar produtos junto ao fornecedor
│   │   ├── Criar entidade Fornecedor
│   │   ├── Modelar entidade Produto
│   │   ├── Modelar entidade Fornecedor
│   │   ├── Criar relacionamento Produto–Fornecedor
│   │   ├── Criar tabela Produto
│   │   ├── Criar tabela Fornecedor
│   │   ├── Criar formulário de cadastro
│   │   └── Implementar cadastro
│   │
│   ├── 👤 Editar produtos
│   │   ├── Criar formulário de edição
│   │   └── Implementar alteração
│   │
│   ├── 👤 Excluir produtos
│   │   ├── Implementar exclusão
│   │   └── Implementar confirmação
│   │
│   ├── 👤 Consultar produtos
│   │   └── Criar tela de listagem
│   │
│   └── 👤 Integrar produtos ao banco
│       ├── Criar conexão
│       └── Implementar persistência
│
├── 🟣 EPIC — Autenticação e Controle de Acesso
│   │
│   ├── 👤 Realizar login
│   │   ├── Criar entidade Usuario
│   │   ├── Criar formulário de login
│   │   ├── Criptografar senha
│   │   └── Implementar autenticação
│   │
│   ├── 👤 Controlar acesso por permissão
│   │   ├── Criar entidade Permissão
│   │   ├── Modelar níveis de acesso
│   │   └── Implementar controle de acesso
│   │
│   └── 👤 Administrar permissões
│       ├── Modelar acesso do administrador
│       └── Modelar permissões do gestor
│
├── 🟣 EPIC — Integridade e Monitoramento dos Dados
│   │
│   ├── 👤 Registrar operações
│   │   ├── Criar arquivo de log
│   │   ├── Criar método EscreverSaida
│   │   ├── Registrar CRUD
│   │   └── Registrar sessões
│   │
│   ├── 👤 Registrar saída de produtos
│   │   ├── Implementar saída
│   │   ├── Atualizar estoque
│   │   └── Registrar saída no log
│   │
│   ├── 👤 Receber alertas de estoque mínimo
│   │   ├── Criar método Alerta
│   │   ├── Verificar quantidade
│   │   └── Notificar usuários
│   │
│   └── 👤 Gerar relatórios
│       ├── Criar método GerarRelatorios
│       ├── Ordenar dados
│       ├── Filtrar por período
│       └── Gerar relatórios automaticamente
│
├── 🟣 EPIC — Painel e Visualização
│   │
│   └── 👤 Visualizar painel
│       ├── Criar estrutura do painel
│       ├── Exibir informações do estoque
│       └── Exibir alertas e movimentações
│
└── 🟣 EPIC — Qualidade, Segurança e Infraestrutura
    │
    ├── Performance
    ├── Disponibilidade
    ├── Backup
    ├── Acesso simultâneo
    ├── Recuperação após falhas
    ├── Segurança
    ├── Compatibilidade
    └── Documentação
