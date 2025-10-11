# Requisitos de Usuário (RU)

| Identificador | Descrição |
|---|---|
| **RU01** | O usuário deve poder cadastrar-se na plataforma |
| **RU02** | O usuário deve poder assistir vídeos da sua preferência |
| **RU03** | O usuário deve poder criar playlist com os vídeos |
| **RU04** | O usuário deve poder curtir e comentar nos vídeos | 
| **RU05** | O usuário deve poder enviar vídeos para a plataforma |


# Requisitos de Sistema (RS)

| **Identificador** | **Descrição** | **Requisitos Relacionados** | **Escopo** |
|-------------------|---------------|-----------------------------|------------|
| **RS01** | O sistema deve permitir o registro de novos usuários, solicitando dados como e-mail, senha e confirmação de identidade via conta Google. | RU01 | Geral |
| **RS02** | O sistema deve disponibilizar um reprodutor de vídeo com recursos de pausa, reprodução, controle de volume e recomendação baseada em histórico. | RU02 | Geral |
| **RS03** | O sistema deve permitir a criação, edição e exclusão de playlists personalizadas associadas à conta do usuário. | RU03 | Específico |
| **RS04** | O sistema deve disponibilizar funcionalidades para registrar curtidas e armazenar comentários vinculados ao vídeo e ao perfil do usuário. | RU04 | Específico |
| **RS05** | O sistema deve permitir o upload de arquivos de vídeo, com verificação de formato, tamanho e conformidade com as políticas de conteúdo. | RU05 | Específico |

---

# Requisitos de Software (RSF)

| **Identificador** | **Descrição** | **Requisitos Relacionados** |
|-------------------|---------------|-----------------------------|
| **RSW01** | O software deve implementar um módulo de cadastro que armazene os dados do usuário em uma tabela chamada “users”, validando e-mail e senha. | RS01 |
| **RSW02** | O software deve utilizar um player de vídeo HTML5 integrado ao backend, com suporte a play, pause, controle de volume e geração automática de recomendações baseadas no histórico do usuário. | RS02 | 
| **RSW03** | O software deve manter uma tabela “playlists” vinculada ao id do usuário, permitindo operações de criação, atualização e exclusão de playlists e seus itens associados. | RS03 | 
| **RSW04** | O software deve armazenar as curtidas e comentários em tabelas separadas, associando cada registro ao id do vídeo e ao id do usuário, garantindo integridade referencial no banco de dados. | RS04 | 
| **RSW05** | O software deve implementar um módulo de upload de vídeo que valide formato e tamanho do arquivo antes do envio, armazenando os metadados em uma tabela “videos” e rejeitando arquivos que violem as políticas de conteúdo. | RS05 |
