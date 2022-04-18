# TRABALHO TIAW

`Tema`

Desconhecimento Sobre Primeiros Socorros

`Curso`

Primeiro Período - Ciência da Computação PUC Minas

## Participantes

Os membros do grupo são: 
- André Lucas Pardinho Ferreira Ferraz
- Gabriel Vargas Bento de Souza
- Gabriela Colem Castelo Borges
- Stefani da Silva Honório 

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
    - [Objetivo Geral](#objetivo-geral)
    - [Objetivos Específicos](#objetivos-especificos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

  Pode-se definir primeiros socorros como sendo os cuidados imediatos que devem ser prestados rapidamente a uma pessoa, a vítima de acidentes ou de mal súbito, com o fim de manter as funções vitais e de evitar o agravamento de suas condições, aplicando medidas e procedimentos até a chegada de assistência qualificada. Entretanto, é notório que a maioria da população brasileira não apresenta os conhecimentos básicos para prestar tal ajuda, o que pode agravar o estado clínico do paciente. Esse desconhecimento tem como causa a falta e a dificuldade de acesso à informação, a negligência e o medo populacional. Logo, é um problema evidente que necessita de soluções práticas e inovadoras.

## Objetivos

### Objetivo Geral

  Tem-se o objetivo de desenvolver um software capaz de ampliar o conhecimento e a divulgação sobre os cuidados e as práticas relacionados aos Primeiros Socorros.

### Objetivos especificos

- Exemplificar e identificar as formas de acidentes mais presentes;
- Minimizar as possíveis vítimas de acidentes em casa;
- Colaborar com a área da saúde e da medicina, no que tange ao atendimento de urgência;
- Disponibilizar, no site, o conhecimento, utilizando videoaulas e tutoriais;
- Sanar dúvidas sobre a prática do rápido salvamento em casos de acidentes;
- Divulgar sites, vídeos e textos relacionados a Primeiros Socorros;
- Maximizar o conhecimento sobre Primeiros Socorros;
- Combinar praticidade, rapidez e simplicidade durante a criação do software;
- Planejar e solucionar a falta de divulgação acerca dos Primeiros Socorros;
- Proporcionar uma área virtual de acesso a uma grande parcela populacional;
- Quebrar o paradigma de ser difícil, demorado e complexo o estudo sobre Primeiros Socorros;
- Demonstrar o quão válido e necessário é o aprendizado nesta área;
- Mediar o conhecimento entre o atendimento médico de urgência e as vítimas;
- Capacitar uma maior parte da população para saber lidar com acidentes domésticos.

## Justificativa

  O que impulsionou a realização deste trabalho foi a percepção de que desinformação, em grande escala, acerca dos primeiros socorros, sendo perceptível, inclusive, no cotidiano. Assim, tendo como base a necessidade de uma ampliação dos meios de divulgação, a escolha de um recorte temático para o tema acidentes com idosos e com crianças foi feita, visando a acidentes recorrentes e que, em muitos casos, não há uma atitude correta de auxílio e de socorro.


## Público-Alvo

  O público alvo do projeto compreende tanto empresas que, em parceria com o site, seriam beneficiadas de um material interativo com os usuários do serviço, facilitando na aprendizagem de manobras e de procedimentos corretos a serem realizados em situações emergenciais. Quanto quem convive com a parcela populacional idosa e infantil, podendo adquirir conhecimentos prévios e seres capacitados a lidar com situações de urgência, no que se tange à área da saúde. 

 
# Especificações do Projeto

  Durante o processo de entendimento e de consolidação das ideias, foram criadas três personas, com seus respectivos mapas de empatia, representado um válido mecanismo de compreensão do problema, bem como uma forma de tornar a ideia mais palpável. Os aspectos mais relevantes, favoráveis ou não à resolução do desafio levantado, foram articulados na parte de histórias de usuários e, em seguida, elucidados na área de requisitos e de restrições.

## Personas e Mapas de Empatia

**Fabiana**

![image](https://user-images.githubusercontent.com/103389529/163735359-86c1d960-c8c6-4b8a-ae42-da08f6e04b61.png)          
Figura 1 - Persona Fabiana

Ela tem 38 anos e trabalha como médica em uma Casa de Idosos, pois gosta de mudar o mundo e de fazer diferença na vida das pessoas. Pretende, sempre que possível, disponibilizar um maior conhecimento aos colegas de profissão e aos parentes de seus pacientes. Entretanto, ela se sente triste por não conseguir divulgar o suficiente sobre Primeiros Socorros para além dos muros de seu trabalho, o que dificulta o salvamento de vidas. Embora tenha perdido conhecidos devido à falta de tratamento correto, é motivada, diariamente, pela felicidade de quem ela trata com o devido suporte. Acreditando, então, que um site possa facilitar em todo esse processo.

**Lucas:**

![image](https://user-images.githubusercontent.com/103389529/163735762-dcccfee9-9916-481f-8f0f-04b071a0625c.png)
Figura 2 - Persona Lucas

Ele é um jovem de 18 anos, que, mesmo ainda na faculdade, sonha em trabalhar ensinando futebol às crianças. Durante o tempo livre, adora ir à academia para relaxar e para desestresar. Faz trabalhos voluntários quando pode e sente enorme prazer e realização nessa atividade, pois, durante a infância, sentiu falta desse carinho. Ele pensa que, além de ele aprender os primeiros socorros para utilizar em sua futura profissão, uma vez que é um ambiente propicio a situações de emergência, ele vai utilizar o site caso aconteça algum acidente enquanto ele faz trabalho voluntário em asilos ou em creches. Sendo, assim, um excelente mecanismo de divulgação de conhecimento.

**Helena:** 

![image](https://user-images.githubusercontent.com/103389529/163735867-064435c9-5b21-43b4-800a-d2884ef5c6de.png)
Figura 3 - Persona Helena

Ela é uma jovem de 18 anos de idade e estuda psicologia. Amante de livros de romance e de estudos sobre a mente humana, Helena mora com a avó, já idosa, e com seus pais. Embora, com muita dificuldade, procure saber sobre Primeiros Socorros para a sua avó, sente-se extremamente despreparada para prestar o socorro necessário em caso de acidente, o que a deixa com muito medo. Ela vê que o seu ciclo familiar apresenta o mesmo sentimento, mas que adoraria estar mais apta para prestar ajuda de emergência. Acredita, então, que um software será de grande valor para ganhar confiança e, também, segurança para realizar o tratamento.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`  |PARA ... `MOTIVO/VALOR`                           |
|--------------------|-------------------------------------|--------------------------------------------------|
| Fabiana            | um site mais divulgado              | conseguir salvar mais pacientes                  | 
| Fabiana            | informações corretas e comprovadas  | evitar que medidas erradas sejam tomadas         |
| Fabiana            | uma plataforma online               | poder recomendar aos pacientes e a parentes deles|
| Fabiana            | videoaulas com médicos              | mostrar procedimentos válidos                    |
| Fabiana            | canal de comunicação com emergência | possibilitar um socorro rápido                   |
| Fabiana            | hiperlinks com mais informações     | ampliar o leque de conhecimento                  |
| Fabiana            | poder fazer comentários             | disponível a outros usuários/pacientes           |
| Fabiana            | cadastro diferencial a médicos      | compartilhar em reuniões da Casa de Idosos       |
| Lucas              | incluir informações sobre esporte   | que alunos e colegas de profissão acessem        |
| Lucas              | software disponível para celular    | poder acessar mais facilmente em campo           |
| Lucas              | falas de especialistas              | conseguir passar segurança aos colegas           |
| Lucas              | parceria com uma empresa de esporte | possibilitar um engajamento dos jogadores        |
| Helena             | acesso rápido e simplificado        | saber cuidar da sua avó                          |
| Helena             | site simples e acessível            | que parentes e familiares possam usar           |
| Helena             | explicação simples e eficaz         | sua avó poder abrir caso precise                 |
| Helena             |demonstração de cada tipo de acidente| se sentir preparada em variadas situações        |
| Helena             | poder abrir no celular              |ser prática, pois computador pode demorar         |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                         | Prioridade |
|------|--------------------------------------------------------------------------------|------------|
|RF-001| O site deve possibilitar o compartilhamento de links para divulgação           | ALTA       | 
|RF-002| O site deve possibilitar canal de comunicação direta com canais de emergência  | ALTA       |
|RF-003| O site deve exemplificar os tipos de acidentes mais comuns                     | ALTA       |
|RF-004| O site deve proporcionar videoaulas informativas e verdadeiras sobre prevenção | ALTA       |
|RF-005| O site deve disponibilizar o tipo de socorro preciso às situações comuns       | ALTA       |
|RF-006| O site deve permitir o cadastro de usuário                                     | MÉDIA      |
|RF-007| O site deve permitir o cadastro de médicos                                     | MÉDIA      |
|RF-008| O site deve ter área exclusiva para discussão no esporte                       | BAIXA      |
|RF-009| O site deve exibir comentários de médicos sobre as aulas                       | BAIXA      |

### Requisitos não Funcionais

|ID     | Descrição do Requisito                                                         | Prioridade |
|-------|--------------------------------------------------------------------------------|------------|
|RNF-001| O site deve ser responsivo para rodar em dispositivos móveis                   | ALTA       | 
|RNF-002| O site deve ser de acesso fácil, fluido e simplicado                           | ALTA       |
|RNF-003| O site deve possuir compatibilidade com maior parte dos navegadores            | ALTA       |
|RNF-004| O site deve apresentar um layout clean e intuitivo                             | ALTA       | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                               |
|--|-------------------------------------------------------------------------|
|01| O projeto final deverá ser entregue até o final do semestre (03 / 07)   |
|02| Não pode ser desenvolvido um módulo de backend                          |
|03| O site deve ser feito exclusivamente pelos estudantes do curso          |

# Projeto de Interface

  Após um maior entendimento e esclarecimento sobre a ideia, utilizando as personas, as histórias de usuários e os requisitos, percebe-se que o ponto diferencial do projeto deverá ser um site que proporcione fluidez e agilidade durante o uso, uma vez que, por se tratar de Primeiros Socorros, o tempo é, sem dúvida, um elemento de extremo valor. Ademais, um layout clean é importante para não confundir o usuário durante a utilização. Tendo isso em vista, desenhou-se a seguinte interface:

## User Flow

  O User Flow, representado pela Figura 4, mostra, de forma simplificada, a interação que será proporcionada entre o usuário e o software. Cada processo de telas está devidamente legendado.

![image](https://user-images.githubusercontent.com/103389529/163689900-6276575f-4e65-476a-802a-38c64a66715c.png)

Figura 4 - Fluxo de telas do Usuário

## Wireframes

Os Wireframes, baseados no User Flow e retratados nas figuras 5 a 9, apresentam sistemas de telas com interações simples, rápidas e práticas, visando, sempre, a um acesso facilitado pelo usuário, de modo a plataforma servir como um facilitador, e não um dificultador no processo dos Primeiros Socorros.

![image](https://user-images.githubusercontent.com/103389529/163690252-46ea4453-285e-497e-8bbd-2deed2e219ee.png)

Figura 5 - Página Inicial

![image](https://user-images.githubusercontent.com/103389529/163690528-8fbb7ef9-44a6-41e7-8b1a-78795f5a372a.png)

Figura 6 - Página Inicial (alternativa)

![image](https://user-images.githubusercontent.com/103389529/163690267-f3f104bc-22af-4631-b525-c82b782d532d.png)

Figura 7 - Página de Pesquisa

![image](https://user-images.githubusercontent.com/103389529/163690475-dcd426d6-f784-4558-91d2-f63a211f3d26.png)

Figura 8 - Página Principal

![image](https://user-images.githubusercontent.com/103389529/163690465-4e08ba60-dc68-4ca0-b9aa-fb5919c3078a.png)

Figura 9 - Página de Comentários

# Metodologia

  A metodologia utilizada compreende os mecanismos utilizados para que o projeto fosse concluído de uma maneira prática e suave. Em especial, tomou-se como base o Design Thinking. Para tanto, inicialmente, realizou-se um brainstore no Miro, visando à obtenção de ideias e de pensamentos, de forma a startar o trabalho. Em seguida, foi feito um Google Forms com as perguntas direcionadoras de ideias e, em seguida, uma análise completa dos resultados. Dessa forma, foi possível perceber as demandas dos futuros usuários do software e compreender profundamente os tipos de perfis e as possíveis personas. 
  Assim, foi possível aprimorar e lapidar as ideias tidas no início do trabalho e, com elas, iniciar a parte de requisitos funcionais e não funcionais. Logo, foram realizados o User Flow e o Wireframe, com o Figma, tendo sempre em vista as determinações dos usuários do serviço.

## Divisão de Papéis

  O trabalho precisou, sem dúvidas, ser dividido entre os quatro integrantes para que fosse completado com sucesso.
  
  Foi utilizado, então, o Miro para ser feito um controle de entrada das tarefas do trabalho. Cada um dos elementos do Sprint 1 foi separado entre a equipe, de modo que, ao mesmo tempo que todos tenham conhecimento sobre as partes do projeto, não há uma sobrecarga a um único integrante apenas. Subdividiu-se as partes, e cada um liderou uma parte do trabalho específica, contribuindo para a organização dos outros. 
  
- Gabriel -> dirigiu o documento 
- Stephanie e André -> organizaram a parte de User Flow e Wireframe
- Gabriela -> responsabilizou-se pela apresentação

## Ferramentas

| Ambiente                   | Plataforma        |Link de Acesso                                                                                 |
|----------------------------|-------------------|-----------------------------------------------------------------------------------------------|
|Processo de Design Thinkgin | Miro              | https://miro.com/app/board/uXjVOB68uOY=/                                                      |
|Repositório de código       | GitHub            | https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-t3-g2-primeiros-socorros-3     | 
|User Flow                   | Figma             | https://www.figma.com/file/gfqgNdxjHh7YSI8eMX13BK/User-flow--Primeiros-socorros?node-id=0%3A1 | 
|Wireframes                  | Figma             | https://www.figma.com/file/KxY5qxhoxyo6xGYenlH0Rg/Wireframe-Primeiros-Socorros?node-id=8%3A372|
|Apresentação                | Canva             | https://www.canva.com/design/DAE-EYoqQd0/Q5qoWJlzMyKO4IEzne_oDg/view?utm_content=DAE-EYoqQd0&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink|

As ferramentas empregadas no projeto são:

- Processo de Design Thinkgin: Miro
O site é um quadro branco onlide e foi escolhido, pois possibilita, em equipe, um compartilhamento de ideias instantâneo e interativo. Além disso, ele apresenta algumas funcionalidades, como uso de post-it, checklists e fluxogramas.

- Repositório de código: GitHub
Embora o principal motivo de utilização tenha sido a disponibilização pela PUC, é uma ferramenta incrível, pois permite a criação de pastas e de documentos, bem como a utilização por toda a equipe.

- User Flow e Wireframes: Figma
O software Figma é uma ferramenta excelente para a criação de protótipos relacionados à criação dos sites, pois tem um layout fácil e prático e, também, permite que o grupo trabalhe junto.

- Apresentação: Canva
A ferramenta online permite, dentre muitas funcionalidades, a criação de apresentação de slides simplificados e bem estruturados, de modo a tornar a apresentação mais clara e atrativa.

- Editor de código: Visual Studio Code"
Após experiências nas matérias de Algoritmos e Estruturas de Dados e de Desenvolvimento de Interfaces Web, acredita-se que o aplicativo seja a melhor ferramenta para a edição dos códigos do software

"Ainda não foi utilizado

## Controle de Versão

  Não ocorreu, ainda, o início da criação do software para, assim, poder ocorrer a adoção dos mecanismos e das ferramentas de controle de versão. 

  Entretando, espera-se o uso da ferramenta de controle de versão como sendo o [Git](https://git-scm.com/) e, também, o [Github](https://github.com) para hospedagem do repositório `upstream`.

  Pra facilitar, a utilização dos seguintes mecanismos pode ser útil:
  
  O projeto seguir a seguinte convenção para o nome de branchs:
 
- `master`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software

  Quanto à gerência de issues, o projeto adotar a seguinte convenção para etiquetas:

- `bugfix`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
