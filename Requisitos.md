# Requisitos Funcionais (RF)

| ID | Descrição | Pré-Condição | Pós-Condição | Invariante | Testável | Verificável | Escopo | Prioridade |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **RF01** | O sistema deve permitir o acesso do usuário por meio de **login**. | O usuário precisa estar cadastrado. | O usuário agora pode interagir com funcionalidades que ele não poderia antes. | O usuário não pode estar logado em duas coisas ao mesmo tempo | Sim | Sim | Específico | Essencial |
| **RF02** | O sistema deve permitir ao usuário **cadastrar** a sua conta. | O usuário precisa adicionar seu email e senha. | O usuário agora está cadastrado e poderá fazer login. | O usuário não pode cadastrar duas contas com mesmo email. | Sim | Sim | Específico | Essencial |
| **RF03** | O sistema deve permitir o envio de vídeos por usuários. | O usuário precisa estar logado. | O vídeo agora está **público** para qualquer pessoa ver. | O vídeo precisa ter um título. | Sim | Sim | Específico | Essencial |
| **RF04** | O sistema deve permitir que usuário assistam qualquer vídeo publicado por outros usuários. | O usuário precisa ter uma conexão estável com a internet. | O vídeo está em estado de "assitido". | O usuário não pode assitir dois vídeos ao mesmo tempo. | Sim | Sim | Específico | Essencial |
| **RF05** | O sistema deve permitir que o usuário adicione um vídeo em uma **playlist**. | O usuário deve estar **logado** em sua conta antes de adicionar. | O vídeo deve ser adicionado à playlist. O contador de quantos vídeos a playlist tem deve ser **atualizado**. | A playlist deve sempre ter **um ou mais vídeos**. | Sim | Sim | Geral | Importante |
| **RF06** | O sistema deve permitir que o usuário dê **curtidas** em vídeos. | O usuário não pode já ter dado uma curtida. O usuário precisa estar **cadastrado**. | O contador de curtidas deve **aumentar em + 1**. | O botão de curtida pode ter **dois estados**: curtido, não curtido. | Sim | Sim | Geral | Essencial |

# Requisitos Não Funcionais (RNF)

| **Identificador** | **Descrição**                                                                | Categoria   | Testável | Verificável | Escopo | Prioridade | 
|---------------|---------------------------------------------------------------------------|-------------|--------|------------|-----------|-----------|
| **RNF01**       | O vídeo deve começar a ser reproduzido em no máximo 2 segundos após o usuário clicar no play, em uma conexão de banda larga de 5 Mbps. O carregamento da página inicial e dos resultados de busca não deve levar mais que 1.5 segundos. | Desempenho   | Geral  | Essencial  |
| **RNF02**         |  O sistema deve ser totalmente funcional nos dois navegadores mais populares do mercado (Chrome, Safari) em suas duas últimas versões estáveis, e nos sistemas operacionais móveis Android e iOS                                               |Compatibilidade  | Geral  | Importante |
| **RNF03**         | O sistema deve oferecer tema escuro opcional para melhor experiência do usuário. | Usabilidade | Geral  | Desejável  |


# Regra de Negócio (RN)
