#Requisitos 

Cadastrar Produtos com Fornecedor
Editar Produtos
Excluir Produtos

Gerenciamento Produtos:
Criar entidade fornecedor
Modelar entidade produto e fornecedor
Criar relacionamento Produto Fornecedor
Criar tabela Produto
Criar tela de listagem
Criar formulário de cadastro
Criar formulário de edição
Implementar exclusão com confirmação

Público Alvo:

O sistema destina-se a empresas de médio e grande porte que necessitam integrar a gerência de seus produtos entre todos funcionários. Os principais usuários são estoquistas, operadores de caixa, supervisores de estoque.

Requisitos Funcionais
1- Cadastrar Produtos junto ao Fornecedor
2- Editar Produtos
3- Excluir Produtos
4- Integração com Banco de Dados
5- Registrar Saída
6- Consultar Produtos
7- Emitir Alertas por Piso Mínimo
8- Registrar Log
9- Permitir Login
10- Permitir Controle de Acesso
11- Registrar Relatórios Semanais
12- Exibir Painel

Requisitos Não Funcionais
13- Tempo de Resposta >2s
14- Disponibilidade +99%
15- Deve Integrar Login e Senha
16- Backups Díarios com Vida Útil de 2 Semanas
17- Permitir Acesso Simultâneo
18- Manter Integridade em Caso de Queda de Energia
19- Proteger Dados de Acesso Não Permitido
20- Deve Ser Compatível com Navegadores Padrão
21- Documentação Extensa Sobre o Software

Gerenciamento de Produtos (1, 2, 3, 4, 6)
- Gerenciamento de Produtos - Criar entidade Fornecedor
- Gerenciamento de Produtos - Modelar entidade produto e fornecedor
- Gerenciamento de Produtos - Criar relacionamento Produto Fornecedor
- Gerenciamento de Produtos - Criar tabela Produto
- Gerenciamento de Produtos - Criar tela de listagem
- Gerenciamento de Produtos - Criar formulário de edição
- Gerenciamento de Produtos - Implementar exclusão com confirmação

Cadastro (9, 10)
Cadastro - Criar entidade usuário
Cadastro - Criar entidade operário
Cadastro - Criar entidade administrador
Cadastro - Criar entidade gestor
Cadastro - Criar entidade permissão
Cadastro - Modelar entidades sob permissão
Cadastro - Realizar login
Cadastro - Criptografar senha
Cadastro - Modelar para administrador gerenciar o sistema todo
Cadastro - Modelar para gestor fornecer níveis de permissão inferior para outros

Integridade dos Dados (5, 7, 8, 11)
Integridade dos Dados - Criar arquivo log
Integridade dos Dados - Criar método EscreverSaida para que ele reescreva o arquivo log com quaisquer operações CRUD e sessão de usuários efetuadas no sistema sendo adicionadas
Integridade dos Dados - Criar método Alerta que verifica quantidades de produtos após cada operação de inserção e remoção, e avisa ao usuário quando ele busca produto que atingiu 40% do volume total, e avisando também todos gestores e o administrador
Integridade dos Dados - Criar método GerarRelatorios, ele irá ordenar e compilar os dados do log de acordo com a marca de tempo requerida e transformar em informações para ser acessada pelo gestor e administrador, e caso não seja requerida será criada a cada quinzena automaticamente



# Documentação

Esta pasta contém a documentação do projeto **Controle de Estoque**.

## Arquivos

- **Sprint_1.pdf** – Documento referente à Sprint 1.
- **Dailies_Sprint_1.pdf** – Registro das reuniões diárias (Daily Scrum) da Sprint 1.
