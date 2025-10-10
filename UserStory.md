# User Story (RF)

<div align="center">
  
| Título: Cadastrar (RF01)   \|   Prioridade: Essencial   \|   Estimativa: 5 pontos                                                                                                                                                                                                                                |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** Me cadastrar no sistema utilizando meus dados<br><br>**Para:** Poder logar em minha conta.                                                                                                                                                                                 |
| **Critério de Aceitação:**<br><br>O sistema deve solicitar: nome, e-mail e senha.<br>O sistema deve verificar se o email já está cadastrado.<br>A senha deve ter, no mínimo, 8 caracteres incluindo pelo menos uma maiúscula.<br>Após o cadastro, o sistema deve alertar ao usuário que o cadastro foi realizado. |

Tabela 1 - User Story de Cadastro.

---

| Título: Logar (RF02)   \|   Prioridade: Essencial   \|   Estimativa: 3 pontos                                                                                                                                                                                                                             |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** logar em minha conta utilizando meus dados.<br><br>**Para:** Poder acessar mais funcionalidades.                                                                                                                                                                    |
| **Critério de Aceitação:**<br><br>O sistema deve solicitar: email e senha.<br>O sistema deve verificar se o email é cadastrado e se a senha está correta.<br>O sistema deve logar o usuário em sua conta.<br>Tendo logado o usuário em sua conta, o sistema deve mandar o usuário para a página principal. |

Tabela 2 - User Story de Logar.

---

| Título: Enviar Vídeos (RF03)   \|   Prioridade: Essencial   \|   Estimativa: 8 pontos                                                                                                                                                                                                                                                                                                                                 |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** Enviar um vídeo<br><br>**Para:** Compartilhar o vídeo com outros usuários                                                                                                                                                                                                                                                                                                       |
| **Critério de Aceitação:**<br><br>O sistema deve solicitar do usuário o arquivo em vídeo, o título e a descrição dele.<br>O sistema deve verificar se o título não está vazio.<br>Se o título estiver vazio, o sistema deve alertar ao usuário.<br>Registrar o vídeo, bem como seu título e descrição, no banco de dados.<br>Apos registrar o vídeo, o sistema deve alertar ao usuário que o vídeo está na plataforma. |

Tabela 3 - User Story de Envio de Vídeos.

---

| Título: Assitir Vídeos (RF04)   \|   Prioridade: Essencial   \|   Estimativa: 2 pontos                                                                                                                                                                                                                                                                                                                                                                          |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** Achar um vídeo para assistir<br><br>**Para:** Me entreter ou aprender com o vídeo                                                                                                                                                                                                                                                                                                                                         |
| **Critério de Aceitação:**<br><br>Após o usuário ter clicado em um vídeo, o sistema deve carregar para o usuário o vídeo, o título e a descrição.<br>O sistema deve continuar exibindo o vídeo, até que o usuário saia dele ou o vídeo termine.<br>Depois que o vídeo terminar, o sistema deve pausar o vídeo, como um indicativo de que ele terminou.<br>O sistema deve registrar o vídeo em estado de "Assistido" depois de 5 segundos que o usuário assistiu. |

Tabela 4 - User Story de Assistir Vídeos.

---

| Título: Adicionar Vídeos a uma Playlist (RF05)   \|   Prioridade: Importante   \|   Estimativa: 4 pontos                                                                                                                                                                                                                                                                                          |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** Adicionar um vídeo a uma playlist<br><br>**Para:** Guardá-lo para mais tarde                                                                                                                                                                                                                                                                               |
| **Critério de Aceitação:**<br><br>O sistema deve solicitar do usuário qual playlist ele quer que o vídeo selecionado seja guardado.<br>O sistema deve pegar o id do vídeo e colocá-lo na playlist (no banco de dados)<br>O sistema deve atualizar o contador de vídeos da playlist com +1.<br>Depois de atualizar o contador, o sistema deve retirar o usuário da tela de requisição de playlist. |

Tabela 5 - User Story de Adição de Vídeos a uma Playlist.

---
| Título: Curtir Vídeos (RF06)   \|   Prioridade: Essencial   \|   Estimativa: 1 pontos                                                                                                                                                                                                                                                                                                          |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Como:** Usuário<br><br>**Eu quero:** "Curtir" um vídeo<br><br>**Para:** Expressar minha opinião sobre aquele vídeo                                                                                                                                                                                                                                                                            |
| **Critério de Aceitação:**<br><br>Após o usuário ter clicado no botão de curtidas, o botão deve mudar para uma cor azul.<br>O sistema deve atualizar o contador de curtidas com +1.<br>Se o usuário clicar no botão de curtidas mesmo já tendo clicado antes, o sistema deve retirar a cor azul e voltar o botão ao estado original.<br>O sistema deve atualizar o contador de curtidas com -1. |

Tabela 6 - User Story de Curtir Vídeos.
</div>
