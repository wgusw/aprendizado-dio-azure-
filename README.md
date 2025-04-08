Explorando os Recursos do Microsoft Azure
Este repositório contém um resumo dos principais conceitos e serviços do Microsoft Azure abordados no curso da DIO, com ênfase em Storage Account, SQL Database, Collation e Tags.

📚 Conteúdos Aprendidos
1. Storage Account
Definição: Recurso do Azure utilizado para armazenar dados como blobs (arquivos), filas, tabelas e discos.​

Redundância: Mecanismos que garantem a replicação dos dados para assegurar alta disponibilidade e durabilidade.​

Segurança: Implementação de autenticação, controle de acesso e criptografia para proteger os dados armazenados.​
DIO

Rede: Configurações que controlam o acesso à Storage Account, incluindo firewalls, regras de IP e integrações com redes virtuais.​

Performance - Blob Storage: Otimização do armazenamento de objetos com diferentes camadas de acesso (Hot, Cool, Archive) e opções de desempenho (Standard, Premium).​

Criptografia (Encryption): Proteção dos dados em repouso e em trânsito utilizando criptografia, com possibilidade de gerenciamento de chaves pelo cliente.​

2. SQL Database
Definição: Banco de dados relacional gerenciado na nuvem, baseado no SQL Server, oferecendo alta disponibilidade e escalabilidade.​

Redundância: Backups automáticos e réplicas geográficas para recuperação de desastres e continuidade dos negócios.​

Segurança: Autenticação via Azure AD, firewalls, auditoria e criptografia para proteger os dados e controlar o acesso.​

Rede: Configurações de acesso seguro através de endpoints públicos ou privados e integração com redes virtuais.​

Performance: Modelos de compra baseados em DTU ou vCore, com opções de bancos isolados ou pools elásticos para otimização de recursos.​

Criptografia (Encryption): Criptografia transparente de dados em repouso e suporte a chaves gerenciadas pelo cliente.​

3. Collation
Definição: Determina as regras para ordenação e comparação de dados de texto no banco de dados.​

Importância: Deve ser definida corretamente no momento da criação do banco, pois não pode ser alterada posteriormente.​

Padrão: O collation padrão é SQL_Latin1_General_CP1_CI_AS, que é case-insensitive e accent-sensitive.​

4. Tags
Definição: Chaves e valores atribuídos aos recursos do Azure para categorização e organização.​

Aplicações: Facilitam a gestão de custos, manutenção e governança dos recursos na nuvem.​
DIO
+3
DIO
+3
DIO
+3

Exemplos: Ambiente: Produção, Departamento: TI, Projeto: Alpha.​

🛠️ Recursos Práticos
Scripts de Criação e Configuração: Exemplos de scripts para criar e configurar Storage Accounts e SQL Databases com as melhores práticas.​

Exemplos de Uso de Tags: Demonstrações de como aplicar tags aos recursos e utilizar essas informações para relatórios e gestão.​

📖 Referências
Documentação Oficial do Azure

Artigos Relacionados na DIO

📌 Observações
Este repositório serve como material de estudo complementar ao curso "Explorando os Recursos do Azure" da DIO. Para aprofundamento, recomenda-se consultar a documentação oficial e realizar práticas no portal do Azure.
