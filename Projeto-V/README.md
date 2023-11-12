<h1 align="center">5º Semestre (2023.2)</h1>

<br id="topo">

<p align="center">
  <a href="#about">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#demo">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#requirements">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tech">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#dev">Contribuições pessoais</a>
</p>

<div id="about">

## Sobre o projeto

<p align="justify">O projeto teve como objetivo o desenvolvimento de um aplicativo mobile que permitisse o gerenciamento (online e offline) de equipamentos públicos em campo (denominados ativos) para a empresa Imagem Geosistemas. 
A partir desse aplicativo, a empresa poderia fazer a gestão desses equipamentos (consultar, atualizar, desativar e cadastrar), permitindo a conexão com sensores e comunicação a serviços externos e 
exibindo esses equipamentos em tempo real nos mapas (conforme a posição geográfica do usuário em um raio de 10km).
<br><br>
Para alcançar esse resultado, a equipe utilizou a metodologia Scrum, conhecido framework ágil utilizado na gestão de projetos baseado em conceitos como ciclos de feedback, melhoria contínua e empirismo. 
A equipe também teve a oportunidade de aplicar tecnologias atuais e em alta no mercado profissional, como o React Native, o JavaScript e o TypeScript.
<br><br>
As funcionalidades implementadas nesse aplicativo refletem as atividades comumente realizadas nas áreas de engenharia de empresas de Saneamento, Elétrica, Telecomunicações e outros tipos de negócios nos quais são realizadas obras e manutenção de equipamentos em campo. 
Isso porque esse tipo de negócio utiliza amplamente processos de manobras, nos quais um equipamento precisa ser desativado para que seja realizada uma manutenção. Durante esta etapa de manutenção parte da rede de serviços pode ser afetada, e por sua vez afetar os clientes conectados a ela, 
e ter o cadastro destes ativos atualizados em campo em tempo real é primordial para que a qualidade dos serviços prestados para os consumidores.
</p>

→ [Voltar ao topo](#topo)

</div>

<div id="demo">

## Resultado final

[Em breve]

</div>

<div id="requirements">

## Requisitos

a) Funcionais

* Cadastro de equipamentos (Ativos), incluindo foto;
* Ativação e desativação de equipamentos;
* Visualização geográfica dos equipamentos cadastrados (tanto os ativos quanto os inativos);
* Visualização detalhada dos equipamentos disponíveis no raio de ação do App;
* Filtros de busca de equipamentos (baseado no seu tipo);
* Cadastro de usuários, incluindo foto;
* Liberação de usuários mediante processo de autenticação;
* Recuperação de senha por meio de código (6 dígitos);
* Criptografia de senhas;
* Busca de equipamentos cadastrados (raio de 10km) de acordo com posição geográfica do App;
* Sincronização de dados online em até 30 segundos após uso offline da aplicação;

b) Não funcionais

* Aplicação de dois fatores para autenticação em cada acesso (A2F);
* Implementação de persistência poliglota;
* Condições de iluminação de tela adaptáveis à necessidade do usuário;
* Segurança das informações em caso de perda do dispositivo móvel;
* Validação dos dados inseridos na aplicação (equipamentos e usuários);
* Banco de dados mobile para armazenamento dos dados atualizados dos equipamentos durante estado offline do App.

→ [Voltar ao topo](#topo)

</div>

<div id="tech">

## Tecnologias utilizadas

Para desenvolver este projeto foram utilizadas as seguintes ferramentas:

| Tecnologia | Aplicação |
|:--------:|:-----------:|
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/> | HTML é uma linguagem de marcação que foi aplicada na estruturação e exibição do conteúdo na web. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>  | CSS é uma linguagem de estilo utilizada para controlar a apresentação e o layout de documentos HTML. Foi utilizado para a estilização do sistema. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" /> | JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma. A partir dela, foi possível criar conteúdo com atualização dinâmica, múltimídias, imagens animadas, entre outros. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" /> | React Native é uma biblioteca front-end JavaScript criada pelo Facebook amplamente usada para desenvolver aplicativos para os sistemas Android e iOS de forma nativa. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" /> | TypeScript é uma linguagem de programação que adiciona recursos avançados ao JavaScript, como a tipagem estática e interfaces. Com ela, fica mais fácil detectar e prevenir erros durante a fase de desenvolvimento. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" /> | O Node JS é um ambiente de execução do código JavaScript para servidor (server side) que permite criar aplicações standalone (autossuficientes) em uma máquina servidora, sem a necessidade do navegador. Foi utilizado para desenvolver o Back-end da aplicação. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" /> | Flask é um framework web escrito em Python e foi utilizado no roteamento de URL e nas renderização das páginas. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" /> | Git é um sistema de controle de versão de código aberto que foi empregado para controlar o histórico de alterações de arquivos do projeto. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" /> | GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão que usa o Git. Foi utilizado para a hospedagem do código e para colaboração entre os integrantes da equipe durante o desenvolvimento da aplicação. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" /> | Figma é um editor gráfico de vetor e foi utilizado para prototipagem das telas que compõem o projeto. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" /> | Canva é uma plataforma de design gráfico que foi utilizada para criar as apresentações e demais conteúdos visuais necessários ao longo do desenvolvimento no projeto.|
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" /> | Visual Studio Code é um editor de código aberto altamente extensível. Foi ultilizado para o desenvolvimento do código-fonte. |
| <img width="50 rem" src ="../Imagens/expo.png" /> | Expo é uma plataforma open-source que foi utilizada no desenvolvimento mobile com React Native. Ela é conhecida por permitir fácil acesso às API’s nativas do dispositivo sem precisar instalar qualquer dependência ou alterar código nativo. |
| <img width="50 rem" src="../Imagens/typeorm.png" /> | O TypeORM é um framework de mapeamento objeto-relacional que aproxima o paradigma de desenvolvimento de aplicações orientadas a objetos ao paradigma do banco de dados relacional. Foi utilizado para definir como os dados são mapeados entre os ambientes e como são acessados e gravados. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-plain.svg" /> | PostgreSQL é um sistema de gerenciamento de banco de dados (SGBD) que utiliza a linguagem SQL como interface. A partir dele, foi possível registrar, armazenar e tratar todos os dados necessários para o bom funcionamento da aplicação. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" /> | MongoDB é um programa de banco de dados NoSQL, que usa documentos semelhantes à JSON com esquemas. Foi aplicado no armazenamento e tratamento de dados do projeto. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" /> | Azure é uma plataforma de computação em nuvem da Microsoft, que oferece acesso, gerenciamento e desenvolvimento de aplicativos e serviços por meio de data centers globais. Essa ferramenta foi utilizada para hospedar os bancos de dados. |
| <img width="50 rem" src="../Projeto-II/Images/azure-devops.png" /> | O Azure DevOps é um servidor da Microsoft que fornece as ferramentas necessárias para fazer o controle de versão, a geração de relatórios, o gerenciamento de requisitos e de projetos, as compilações automatizadas e os testes necessários no desenvolvimento de softwares. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/slack/slack-original.svg" /> | O Slack é um software de comunicação de equipes com suporte a canais, conversas privadas e integração com serviços externos que foi utilizado para comunicação com o cliente. |
| <img width="50 rem" src="../Imagens/microsoft-teams.png" /> | O Microsoft Teams é uma plataforma unificada que conta com ferramentas de bate-papo, videoconferências, armazenamento de arquivos e integração de aplicativos no local de trabalho. Foi utilizada para comunicação e colaboração entre os membros da equipe. |


→ [Voltar ao topo](#topo)

</div>

<div id="dev">

## Contribuições pessoais

<p align="justify"></p>

#### Hard Skills

1. **Programação em TypeScript:** Sei fazer com ajuda;

2. **Desenvolvimento Mobile em React Native:** Sei fazer com ajuda;

3. **Uso de tags HTML:** Sei fazer com autonomia;

4. **Aplicação de recursos CSS:** Sei fazer com auxílio de consultas;

5. **Desenvolvimento back-end com NodeJS:** Sei fazer com ajuda;

6. **Controle de Versão (Git/GitHub):** Sei fazer com autonomia;

7. **Gerenciamento de Banco de Dados SQL (PostgreSQL):** Sei fazer com auxílio de consultas;

8. **Gerenciamento de Banco de Dados NoSQL (MongoDB):** Sei fazer com ajuda;

9. **Criação de Protótipos Navegáveis (Figma):** Sei fazer com autonomia;

10. **Conceitos de arquitetura de software:** Sei fazer com ajuda;

11. **Conceitos aplicados de UX Designer:** Sei fazer com autonomia;

12. **Hospedagem de banco de dados em cloud (Azure):** Sei fazer com ajuda;

13. **Conteinerização (Docker):** Sei fazer com ajuda;

14. **Roteamento de URL e renderização de página (Flask):** Sei fazer com ajuda;

15. **Desenvolvimento back-end com Python:** Sei fazer com ajuda.

#### Soft Skills  

[Em breve]

→ [Voltar ao topo](#topo)

</div>



