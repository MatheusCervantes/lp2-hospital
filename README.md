# Projeto de Sistema Hospitalar em Java com SQLite

## Descrição

Este projeto é um sistema hospitalar desenvolvido em Java, utilizando o banco de dados SQLite. O sistema possui funcionalidades essenciais para a gestão de informações em um ambiente hospitalar, incluindo operações CRUD (Create, Read, Update, Delete) para quatro entidades principais, relatórios, backup de dados, sistema de banco de dados SQLite e criptografia SHA-256 para garantir a segurança das informações.

## Funcionalidades

### 1. Operações CRUD

O sistema oferece quatro operações CRUD para as seguintes entidades:

- **Pacientes:** Cadastro, consulta, atualização e exclusão de informações de pacientes.
- **Médicos:** Gerenciamento de dados dos médicos, incluindo adição, consulta, atualização e remoção de registros.
- **Funcionários:** Operações CRUD para funcionários do hospital, permitindo a gestão eficiente de dados de colaboradores.
- **Consultas:** Possibilidade de registrar, visualizar, atualizar e excluir informações relacionadas a consultas médicas.

### 2. Relatórios

O sistema permite a geração de relatórios para fornecer insights sobre diversas métricas e dados do hospital. Esses relatórios podem incluir estatísticas de atendimento, ocupação de leitos, entre outros aspectos relevantes para a gestão hospitalar.

### 3. Backup de Dados

Implementa um mecanismo de backup para garantir a integridade e disponibilidade dos dados. Os backups podem ser programados automaticamente ou realizados manualmente para evitar a perda de informações cruciais.

### 4. Banco de Dados SQLite

Utiliza o banco de dados SQLite para armazenar e recuperar informações. O SQLite é uma opção leve e incorporada que simplifica a implementação e distribuição do sistema.

### 5. Criptografia SHA-256

Para garantir a segurança dos dados sensíveis, o sistema implementa o algoritmo de criptografia SHA-256. Isso assegura que as informações armazenadas, especialmente aquelas relacionadas a senhas de usuários, permaneçam protegidas contra acesso não autorizado.

### 6. Sistema de Login

O sistema incorpora um sistema de login seguro, onde usuários devem autenticar-se antes de acessar as funcionalidades do sistema. A combinação de login e senha é protegida pela criptografia SHA-256 para garantir a confidencialidade das credenciais dos usuários.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
