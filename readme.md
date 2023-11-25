<!-- p align="center">
  <img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=Netlify&message=deploy&color=blue&style=for-the-badge&logo=netlify"/>
  <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
  <img src="http://img.shields.io/static/v1?label=Ruby&message=2.6.3&color=red&style=for-the-badge&logo=ruby"/>
  <img src="http://img.shields.io/static/v1?label=Ruby%20On%20Rails%20&message=6.0.2.2&color=red&style=for-the-badge&logo=ruby"/>
  <img src="http://img.shields.io/static/v1?label=TESTES&message=%3E100&color=GREEN&style=for-the-badge"/>
   <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
   <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
</p -->



# AlunoTracker 🚍📲
Um Sistema de Gerenciamento de Viagem

> Status do Projeto: :warning: (em desenvolvimento)
<!-- :heavy_check_mark: -->

### Tópicos 

:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)

:small_blue_diamond: [Funcionalidades](#funcionalidades)

:small_blue_diamond: [Deploy da Aplicação](#deploy-da-aplicação-dash)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](./docs/run/como-executar-projeto.md)

:small_blue_diamond: [Design da aplicação](https://www.figma.com/file/Vs6Dtv9BBJxLRJQp3KMt5Y/AlunoTracker?type=design&node-id=116%3A2486&mode=design&t=plOQToclYhJQsgof-1)
... 


## Descrição do projeto 

<p align="justify">
  O AlunoTracker é uma plataforma de gerenciamento de viagens que oferece suporte abrangente para planejar, organizar e gerenciar viagens com grupos de pessoas (focado no público do <a href="https://www.ifs.edu.br">IFS</a>). Seja para excursões escolares, viagens de lazer ou qualquer outra aventura em grupo, nosso sistema simplifica o processo de coordenação e oferece uma experiência de viagem mais agradável e organizada.
</p>

## Requisitos

### **✅ Requisitos Funcionais**

- **Cadastro de Usuários:** Os usuários devem poder se registrar e criar contas para acessar o sistema.

- **Gerenciamento de Eventos:** Os usuários devem poder criar, visualizar, atualizar e excluir eventos de viagem.

- **Gerenciamento de Passeios do Roteiro:** Cada evento deve permitir a adição, edição e exclusão de passeios ou paradas no itinerário da viagem.

- **Gerenciamento de Participantes:** Os organizadores devem poder adicionar, remover e atualizar informações de participantes, atribuir funções ou tarefas a eles.

- **Calendário de Eventos:** Deve haver uma visualização de calendário que mostre os eventos programados.

- **Notificações:** Os participantes e organizadores devem receber notificações sobre atualizações de eventos e informações importantes.

</br>

### **✅ Requisitos Não Funcionais**

- **Segurança:** Garantir a segurança dos dados pessoais dos participantes e a integridade das informações do evento.

- **Desempenho:** O sistema deve ser capaz de lidar com múltiplos eventos e participantes sem degradação significativa de desempenho.

- **Usabilidade:** O sistema deve ser fácil de usar, com uma interface intuitiva.

- **Escalabilidade:** Deve ser possível dimensionar o sistema para acomodar um grande número de eventos e participantes.

- **Compatibilidade:** O sistema deve ser compatível com diferentes navegadores e dispositivos.

- **Manutenção:** Garantir que o sistema seja de fácil manutenção e atualização.

</br>


## Funcionalidades

- **Gerenciamento do [evento](./docs/evento.md) e passeios do roteiro;**

<p align="justify">
Essa funcionalidade permite aos usuários criar e gerenciar eventos de viagem, bem como os passeios do roteiro dentro de cada evento. Isso inclui a definição de datas, horários, locais e descrições para cada parada no itinerário da viagem.
</p>

- **Gerenciamento de [Participantes](./docs/participantes.md)**

<p align="justify">
Esta funcionalidade permite aos organizadores da viagem controlar a lista de participantes. Eles podem adicionar ou remover participantes, atribuir tarefas ou funções específicas e manter as informações de contato de cada participante atualizadas.
</p>

- **[Calendário de Eventos](./docs/calendario.md)**

<p align="justify">
O calendário de eventos é uma visualização visual de todos os eventos programados e seus respectivos passeios. Ele permite que os usuários vejam rapidamente a programação de viagens e eventos em um determinado período.
</p>

- **[Comunicação Integrada](./docs/notificacoes.md)**

- **Verificação e [Tarefas]**

- Veja a [lista completa de funcionalidades](./docs/funcionalidades_extras.md)

  </br>
  

## Descrição das Telas 📱

**1️⃣ - TELA DE CADASTRO DE USUÁRIO** 
<p align="justify">Caso o usuário ainda não possua cadastro, basta informar os campos que existem na tela, são eles: nome completo, CPF, Data de Nascimento, Curso, Período, Matrícula do curso, senha contendo letras e números, e repetir a mesma senha para confirmar. Após preencher todos os campos, clicar no botão "Tô dentro" para se cadastrar. Após o cadastro, o usuário é redirecionado para a página inicial do sistema.</p>


**2️⃣ - TELA DE LOGIN DE USUÁRIO**
<p align="justify">Nessa tela temos o campo de CPF e senha de usuário, devendo ser informados os respectivos campos para completar o login, o CPF só deve ser preenchido com números, e a senha deve ser a mesma cadastrada anteriormente no sistema. Após o preenchimento dos campos, clicar no botão "Entrar" e o usuário será redirecionado para tela Inicial do sistema. Se o usuário ainda não tiver cadastro, poderá se cadastrar clicando no botão "Cadastre-se" onde será redirecionado para a tela de cadastro no sistema.</p>


**3️⃣ - TELA INICIAL (ALUNO)**
<p align="justify">No cabeçalho da página ao lado esquerdo temos um ícone de barras que ao ser clicado exibe um menu lateral com as opções de "Atualizar dados" e "Sair". No lado direito do cabeçalho temos um ícone de notificações que ao ser clicado exibe um menu lateral mostrando as notificações recebidas, podendo ser excluídas no ícone de X, ou marcadas como lidas no ícone de check, ao lado do nome notificações.</p>

<p align="justify">Nessa tela inicial temos uma foto do usuário (aluno) juntamente com o seu nome, logo abaixo é mostrado os "Convites" que o aluno recebeu de um professor, mostrando as informações do evento, nome do responsável, e dois botões, "Inscrever-se" que ao ser clicado verifica se o usuário possui 18 anos ou mais e automaticamente aceita o convite do evento, caso ele não cumpra o requisito da idade, será solicitado um termo de autorização dos responsáveis por ele, devendo ser anexado ao sistema, e o botão "Recusar" que recusa e exclui o convite.</p>

<p align="justify">Após mostrar os convites, abaixo temos a lista de "Inscrições", onde mostra os eventos em que o aluno está inscrito. Podendo também cancelar a ida ao evento, clicando no botão "Cancelar". E ao clicar no cartão do evento o usuário é redirecionado para a tela onde mostra mais informações do evento.</p>


**4️⃣- TELA INICIAL (RESPONSÁVEL)**
<p align="justify">No cabeçalho da página ao lado esquerdo temos um ícone de barras que ao ser clicado exibe um menu lateral com as opções de "Cadastrar Evento", "Atualizar dados" e "Sair". No lado direito do cabeçalho temos um ícone de notificações que ao ser clicado exibe um menu lateral mostrando as notificações recebidas, podendo ser excluídas no ícone de X, ou marcadas como lidas no ícone de check, ao lado do nome notificações. Caso o usuário clique em "Cadastrar evento" ele será direcionado a tela de Cadastro de Eventos onde irá preencher todas as informações do evento.</p>

<p align="justify">Nessa tela inicial temos uma foto do usuário (aluno) juntamente com o seu nome, logo abaixo é mostrado cards com os "Eventos Ativos", nesse card tem o título do evento, data de saída e volta, e os botões "Editar" onde é possível editar informações do evento, e o botão "Convidar" onde é feito o convite para o evento.</p>

<p align="justify">Logo abaixo dos "Eventos ativos" é mostrado os eventos "Em andamento", que contém as informações necessárias para o gerenciamento do evento.</p>


**5️⃣- TELA DE CADASTRO DE EVENTOS**
<p align="justify">No cabeçalho da página ao lado esquerdo temos um ícone de barras que ao ser clicado exibe um menu lateral com as opções de "Cadastrar Evento", "Atualizar dados" e "Sair". No lado direito do cabeçalho temos um ícone de notificações que ao ser clicado exibe um menu lateral mostrando as notificações recebidas, podendo ser excluídas no ícone de X, ou marcadas como lidas no ícone de check, ao lado do nome notificações. Caso o usuário clique em "Cadastrar evento" ele será direcionado a essa tela de Cadastro de Eventos onde irá preencher todas as informações do evento.</p>

<p align="justify">As informações necessárias para o cadastro de um evento são: nome do evento, descrição do evento, data e hora de início, data e hora de fim, data e hora limite para a inscrição, o tipo de evento e um arquivo para o roteiro, este podendo ser visualizado a partir de um botão ver.</p>

<p>Logo abaixo dos campos, temos dois botões, "Cancelar" que ao ser clicado retorna a página inicial do responsável, e "Criar Evento" que ao ser clicado cria o evento e direciona para a página de Convidar Alunos.</p>


**6️⃣- TELA DE CONVIDAR ALUNOS**
<p align="justify">No cabeçalho da página ao lado esquerdo temos um ícone de barras que ao ser clicado exibe um menu lateral com as opções de "Cadastrar Evento", "Atualizar dados" e "Sair". No lado direito do cabeçalho temos um ícone de notificações que ao ser clicado exibe um menu lateral mostrando as notificações recebidas, podendo ser excluídas no ícone de X, ou marcadas como lidas no ícone de check, ao lado do nome notificações. Caso o usuário clique em "Cadastrar evento" ele será direcionado a tela de Cadastro de Eventos onde irá preencher todas as informações do evento.</p>

<p align="justify">Nessa tela o responsável terá que preencher os seguintes campos para convidar os alunos: curso, período, matrícula, nome do aluno.</p>

<p align="justify">Após o preenchimento aparecerá uma lista contendo os alunos conforme os campos preenchidos, podendo assim o responsável clicar em cada nome de aluno e clicar no botão "Enviar Convites" para que cada aluno receba o convite do evento e aceite ou não.</p>

**7️⃣- TELA DE LISTA DE PRESENÇA**
<p align="justify">No cabeçalho da página ao lado esquerdo temos um ícone de barras que ao ser clicado exibe um menu lateral com as opções de "Cadastrar Evento", "Atualizar dados" e "Sair". No lado direito do cabeçalho temos um ícone de notificações que ao ser clicado exibe um menu lateral mostrando as notificações recebidas, podendo ser excluídas no ícone de X, ou marcadas como lidas no ícone de check, ao lado do nome notificações. Caso o usuário clique em "Cadastrar evento" ele será direcionado a tela de Cadastro de Eventos onde irá preencher todas as informações do evento.</p>

<p align="justify">Logo abaixo é mostrada uma lista com todos os alunos que estão cadastrados nos eventos em ordem alfabética, e ao lado de cada nome existem dois ícones, o ícone de "Check" que ao ser clicado confirma a presença do aluno, e o ícone de "X" que ao ser clicado informa a ausência do aluno, e abaixo da lista temos o botão "OK" que ao ser clicado salva a lista de presença e retorna a tela anterior.</p>

**8️⃣- TELA DE VISUALIZAÇÃO DE EVENTO**
<p align="justify">Para visualizar o evento no aplicativo, é necessário clicar no card do evento na tela início, para ser levado à tela de visualização de evento, onde no cabeçalho possui um botão de voltar e as notificações. Logo no início do corpo da tela existe o mesmo card que o do início, ainda com as mesmas funcionalidades de inscrever-se, recusar, ou cancelar, dependendo, se ele é um convite ou inscrição. Após essa seção é trazida a descrição do evento, depois o roteiro dele, onde, pode ser baixado como arquivo a partir do botão “Baixar roteiro” e também, quando a inserção de roteiro for implementada, as paradas do evento poderão ser visualizadas com data e hora.</p>


## Layout ou Deploy da Aplicação :dash:

> Ver mais detalhes [aqui](./docs/how-to/buildAndDeploy.md) 



## Desenvolvedores/Contribuintes 👨🏽‍💻

Liste o time responsável pelo desenvolvimento do projeto

| [<img src="https://avatars.githubusercontent.com/u/366076?v=4" width=115><br><sub>Francisco Rodrigues</sub>](https://github.com/frchico) | [<img src="https://avatars.githubusercontent.com/u/88515518?s=400&u=a003f8ae2f501d0f3487662f0e4095e67fbb6a07&v=4" width=115><br><sub>Bruno Rafael </sub>](https://github.com/DevBrunoRafael) | [<img src="https://avatars.githubusercontent.com/u/86673289?v=4" width=115><br><sub>Marcus Furtuoso</sub>](https://github.com/MarcusFurtuoso) | [<img src="https://avatars.githubusercontent.com/u/37937697?v=4" width=115><br><sub>Carlos Eduardo</sub>](https://github.com/c4rls) | [<img src="https://avatars.githubusercontent.com/u/93016311?v=4" width=115><br><sub>Reinan Oliveira</sub>](https://github.com/ReinanTI) | [<img src="https://instagram.faju7-1.fna.fbcdn.net/v/t51.2885-19/371736907_278178344964556_8009323327070019570_n.jpg?stp=dst-jpg_s150x150&_nc_ht=instagram.faju7-1.fna.fbcdn.net&_nc_cat=104&_nc_ohc=PivKOpfzjOkAX9P52EX&edm=AEF8tYYBAAAA&ccb=7-5&oh=00_AfAz53IoMLglbgE9Fh7ZtJuW3mw22XB5Q10xikvENiwr0A&oe=65537291&_nc_sid=1e20d2" width=115><br><sub>Luis Fernando</sub>](https://github.com/luisSancho1234) |
| :---: | :---: | :---: | :---: | :---: | :---:

| [<img src="https://st3.depositphotos.com/4111759/13425/v/450/depositphotos_134255588-stock-illustration-empty-photo-of-male-profile.jpg" width=115><br><sub>Gustavo Quirino</sub>](https://github.com/CBSIIFSLagarto/alunotracker) | [<img src="https://avatars.githubusercontent.com/u/78385080?v=4" width=115><br><sub>Cassio Leonardo</sub>](https://github.com/LeoOliva0) | [<img src="https://media.licdn.com/dms/image/C4E03AQHjUu_l8GNHAQ/profile-displayphoto-shrink_100_100/0/1626285652818?e=1704931200&v=beta&t=XyAyiO0A8rMA-uK9_zJmDuO0r2INVFTkpydXrmhezbg" width=115><br><sub>Ronivon</sub>](https://github.com/CBSIIFSLagarto/alunotracker) | [<img src="https://st3.depositphotos.com/4111759/13425/v/450/depositphotos_134255588-stock-illustration-empty-photo-of-male-profile.jpg" width=115><br><sub>Ronald Ruan</sub>](https://github.com/ronaldferraz) | [<img src="https://st3.depositphotos.com/4111759/13425/v/450/depositphotos_134255588-stock-illustration-empty-photo-of-male-profile.jpg" width=115><br><sub>Igor Rafael</sub>](https://github.com/CBSIIFSLagarto/alunotracker) | [<img src="https://st3.depositphotos.com/4111759/13425/v/450/depositphotos_134255588-stock-illustration-empty-photo-of-male-profile.jpg" width=115><br><sub>Ulisses</sub>](https://github.com/CBSIIFSLagarto/alunotracker) | 
| :---: | :---: | :---: | :---: | :---: | :---: 


## Agradecimentos

- [Diana Regina](https://github.com/Diana-ops): Pelo [layout base](https://gist.github.com/reginadiana/e044fe93ed81aa04a10361cb841c0409#descri%C3%A7%C3%A3o-do-projeto) para o readme.md do projeto.

## Licença 📝

> O modelo de licenciamento ainda está sob análise.

Copyright :copyright: 2023 - Aluno Tracker
