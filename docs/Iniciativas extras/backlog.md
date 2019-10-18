# Backlog do produto

#### Histórico de revisões
|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|25/09/2019|0.1| Iniciando o documento e adicionando histórias de usuário|André Lucas|
| 25/09/2019 | 0.2 | Adicionando histórias de usuário do EP02 | Weiller Fernandes |
| 25/09/2019 | 0.3 | Adicionando histórias de usuário do EP03 | Caio César Beleza |
| 25/09/2019 | 0.4 | Adicionando histórias de usuário do EP03 | João Gabriel |
| 25/09/2019 | 0.5 | Adicionando histórias de usuário do EP02 | Victor Rodrigues |
| 25/09/2019 | 0.6 | Adicionando histórias de usuário do EP01 e EP04 | Lucas Gomes e André Lucas |
| 26/09/2019 | 0.7 | Aplicando correções e adicionando coluna de pontuação | Weiller Fernandes |
| 11/10/2019 | 0.8 | Adicionando tabela de USs adicionadas | Weiller Fernandes |

## 1. Introdução

Construimos um backlog completo para o produto com base nos requisitos elicitados. Além de, com o backlog construído e todas as histórias de usuário devidamente descritas com critérios de aceitação, simular o que seria desenvolvido em cada Sprint. Sendo que o backlog ficou dividido nos seguinte níveis de granularidade: Épico, histórias de usuário.

## 2. Backlog

### 2.1 EP01 - Perfis

| ID | Eu, como | Gostaria de | Para poder | Priorização | Pontuação Back-end | Pontuação Front-end |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| US01 | Usuário | Alterar minha senha | Melhorar a segurança da minha conta  | Must | | |
| US02 | Usuário | Recuperar minha senha | Continuar tendo acesso ao meu perfil  | Must | | |
| US03 | Usuário | Acessar o painel de anunciante | Gerenciar os dados do anúncio publicado | Must | | |
| US04 | Usuário | Acessar dados do perfil | Visualizar e alterar os dados pessoais (Nome, sexo, whatsapp/telefone, data de nascimento, foto de perfil, redes sociais, nacionalidade) | Must | 3 | * |
| US05 | Usuário | Alterar as preferências do aplicativo | Adequar o aplicativo para minhas necessidades | Must | | |
| US06 | Usuário | Deletar minha conta | Retirar meus dados do servidor do aplicativo  | Must | 2 | * |
| US07 | Usuário | Deslogar da minha conta | Acessar o aplicativo com outra conta existente ou criar uma nova | Must | 2 | * |
| US08 | Usuário | Entrar em contato com o anunciante | Conversar sobre o anúncio  | Must | | |
| US09 | Usuário | Avaliar um anunciante | Mostrar meu nível de satisfação em relação ao anunciante e ao cafofo alugado | Must | | |

 ** * US04, US06 e US07 ** são USs que compõem a página de perfil e valem somadas 3 pontos.

### 2.2 EP02 - Anúncio

| ID | Eu, como | Gostaria de | Para poder | Priorização | Pontuação Back-end | Pontuação Front-end |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| US10 | Visitante/Usuário | Visualizar os detalhes sobre um anúncio | Verificar as informações interessantes para mim | Must | | |
| US11 | Usuário | Criar um anúncio de um cafofo | Achar pessoa interessada em alugá-lo | Must | | |
| US12 | Usuário | Adicionar dados ao anúncio (Descrição, título, preço, localização, itens inclusos, despesas, comodidades, contato) | Fornecer mais detalhes sobre o local anunciado | Must | | |
| US13 | Usuário | Adicionar políticas ao anúncio (se é permitido animais, se é permitido fumar, etc) | Fornecer mais detalhes sobre o local anunciado | Must | | |
| US14 | Usuário | Adicionar sexo alvo para o anúncio (masculino e/ou feminino) | Facilitar a busca e filtragem para os interessados | Must | | |
| US15 | Usuário | Alterar os dados do anúncio (Descrição, título, preço, localização, itens inclusos, despesas, comodidades, contato, status, sexo alvo, políticas) | Editar alguma informação que esteja errada ou desatualizada | Must | | |
| US16 | Usuário | Adicionar fotos ao anúncio | Mostrar como é o ambiente do cafofo que desejo alugar | Should | | |
| US17 | Usuário | Excluir fotos do anúncio | Deixar de exibir uma determinada imagem no anúncio | Should | | |
| US18 | Visitante/Usuário | Compartilhar um anúncio | Mostrar um determinado anúncio para outras pessoas | Could | | |
| US19 | Usuário | Favoritar um anúncio | Ter uma lista de anúncios que gostei e poder vê-los depois sem precisar buscar novamente | Could | | |
| US20 | Usuário | Desfavoritar um anúncio | Deixar de visualizar aquele anúncio na minha lista de favoritos | Could | | |
| US21 | Usuário | Denunciar um anúncio | Possivelmente retirar anúncios enganosos | Should | | |
| US22 | Usuário | Excluir anúncios feitos por mim | Evitar interesse em anúncios não disponíveis | Must | | |
| US23 | Visitante/Usuário | Visualizar a avaliação do anunciante dentro dos detalhes do anúncio | Saber se o anunciante possui boa reputação ou não | Must | | |


### 2.3 EP03 - Pesquisa

| ID | Eu, como | Gostaria de | Para poder | Priorização | Pontuação Back-end | Pontuação Front-end |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| US24 | Visitante/Usuário | Pesquisar anúncios por localização | Achar um cafofo mais perto da universidade | Must | | |
| US25 | Visitante/Usuário | Filtrar anúncios por preço | Achar um cafofo compatível com o meu orçamento | Must | | |
| US26 | Visitante/Usuário | Filtrar anúncios por gênero de hóspedes | Saber se o cafofo oferece vagas apenas para homens, mulheres, ou se é misto  | Should | | |
| US27 | Visitante/Usuário | Filtrar anúncios por avaliação | Saber se é um cafofo bem avaliado pelos antigos residentes | Should | | |
| US28 | Visitante/Usuário | Filtrar anúncios por contas inclusas | Saber o valor total das contas extras do cafofo | Could | | |
| US29 | Visitante/Usuário | Filtrar  por itens que acompanham o Cafofo | Saber se possui WiFi, cama, ar-condicionado, armário, escrivaninha e outras comodidades disponíveis| Could | | |
| US30 | Visitante/Usuário | Filtar anúncios por número de pessoas que compartilham o local| Saber por quantas pessoas as despesas serão divididas |Could | | |
| US31 | Visitante/Usuário | Filtrar anúncios por presença de animais de estimação | Saber se existe ou se é permitido cachorro, gato ou outro animal morando no cafofo | Would | | |
| US32 | Visitante/Usuário | Filtrar anúncios por possibilidade de fumar no local | Saber se pode fumar ou não no Cafofo | Would| | |



### 2.4 EP04 Autenticação

| ID | Eu, como | Gostaria de | Para poder | Priorização | Pontuação Back-end | Pontuação Front-end |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| US33 | Visitante/Usuário | Me cadastrar na aplicação | Ter acesso às funcionalidades do Cafofo | Must | 3 | 3 |
| US34 | Visitante/Usuário | Me cadastrar através do Facebook | Ter acesso às funcionalidades do Cafofo de forma prática | Should | | |
| US35 | Visitante/Usuário | Me cadastrar através do Google | Ter acesso às funcionalidades do Cafofo de forma prática | Should | | |
| US36 | Usuário | Realizar o login na aplicação | Acessar os recursos da aplicação | Must | 2 | 3 |
| US37 | Usuário | Realizar o login na aplicação pelo Facebook | Acessar os recursos da aplicação com integração à conta do facebook | Should | | |
| US38 | Usuário | Realizar o login na aplicação pelo Google | Acessar os recursos da aplicação com integração à conta do Google | Should | | |

### 2.5 USs Adicionadas

Abaixo estão listadas as User Stories que foram identificadas e adicionadas após o início do projeto, uma coluna de épico foi incluída para associar a US á um dos quatro épicos descritos anteriormente.

| ID | Épico | Eu, como | Gostaria de | Para poder | Priorização | Pontuação Back-end | Pontuação Front-end |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| US39 | - | Visitante/Usuário | visualizar a página principal | Começar a utilizar as funcionalidades do site | Must |  | 3 |