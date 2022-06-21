# ListaDeContatosVue

# Requisitos Funcionais:
 Botão de adicionar novo contato (escrito adicionar ou simbolo “+”)
 Modal de Criação - (Caixa de Diálogo) para adicionar o novo contato.
◦ Necessário possuir 2 campos, sendo eles “nome” e “telefone”
◦ Os campos deverão atender os seguintes critérios.
▪ O campo “telefone” deverá atender aos seguintes critérios:
 Possuir a máscara (xx) xxxx-xxxx.
 Deverá ser obrigatório.
 Caso não preenchido, não permitir salvar.
 Exibir mensagem de erro caso não tenha sido preenchido completamente.
 Não permitir letras.
▪ O campo “nome” deverá atender aos seguintes critérios:
 Deverá ser obrigatório.
 Ter no mínimo duas palavras de no mínimo 3 letras cada.
 Caso os critérios não tenham sido atendidos, exibir mensagem de erro (exibir
caixa vermelha ou algo do gênero).
 Não deverá ser permitido salvar caso algum critério não tenha sido contemplado.
Modal - (Caixa de Diálogo) para adicionar o novo contato.
 Modal de Edição – Deverá ser similar ao Modal de Criação, porém servirá para editar
contatos.
 Data-Table na tela principal, listando todos os contatos
◦ Deverá ter 3 colunas – (nome, telefone) sendo a terceira uma coluna sem nome, para
botões de ações
◦ Deverá possuir 2 - botão de editar e excluir contatos (na última coluna)
◦ Caso a linha do Data-Table possua DDD (11), a linha deverá ser azul.

# Tecnologias utilizadas:
◦ VueJS 3.x
◦ Composition API
◦ Vuetify
O projeto foi realizado em um arquivo .HTML único, e as bibliotecas são do tipo
UMD (direto de um CDN)
