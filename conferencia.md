---
title: 'caminho = input("Insira o caminho para História Digital: ")'
subtitle: "Conferência de abertura"
author: Eric Brasil
institution: "História Digital e História Digital da Educação: Caminhos Cruzados. Instituto de Estudos Avançados da Universidade de São Paulo."
keywords: [História Digital, História da Educação, Metodologia]
date: "17 de outubro de 2023"
mainfont: firacode
titlepage-color: "24273A"
titlepage-text-color: "C6A0F6"
titlepage-rule-color: "ED8796"
---

## historia_digital.py

Quando estamos programando, é comum precisarmos passar o caminho de um arquivo para o programa que estamos criando. Se quisermos ler uma fonte, abrir uma imagem, analisar dados de uma planilha ou fazer o download de um pdf para uma pasta específica, temos que informar ao computador qual o seu caminho. 

Ele necessariamente deve ser preciso: explícito e completo, desde sua pasta raiz até o nome do arquivo com sua respectiva extensão.

Por exemplo, para ler um arquivo Python (`.py`) chamado historia_digital, eu passaria o seguinte comando com Python em execução: 

```python
>>> open('historia_digital.py', 'r').read()
```

O retorno seria o conteúdo do arquivo `historia_digital.py` impresso em minha tela.

Porém, caso o caminho para esse arquivo não esteja correto, o comando não terá sucesso e um receberemos um aviso de erro.

Mas calma, essa conferência não vai ser um tutorial de Python, não precisam se desesperar! É apenas o bom e velho recurso à metáfora para iniciar a fala.

Pretendo, hoje fazer uma reflexão coletiva com vocês sobre aspectos, que na minha avaliação, são urgentes para nossa disciplina: a construção metodológica de pesquisas com dados e ferramentas digitais e sua relação com a construção do conhecimento histórico e o próprio caráter científico da disciplina.

Para isso, farei um breve histórico do uso da computação na pesquisa histórica, antes e depois do termo História Digital; apontarei questões gerais envolvendo as práticas de pesquisa atuais, com o exemplo da hemeroteca digital brasileira e como seus aspectos técnicos e vieses de seu acervo impactam epistemologicamente na História; e por fim refletir sobre demandas e caminhos possíveis e necessários.

Mas antes, justificando minhas escolhas para hoje, voltemos à metáfora.

### `Arquivo ou pasta não existe: 'historia_digital.py'`

Ao executar o comando anterior, recebi o seguinte erro:

```python
>>> FileNotFoundError: [Errno 2] No such file or directory:
'historia_digital.py'
```

O Python não foi capaz de encontrar o arquivo. Portanto, não pode executar suas tarefas, pois o caminho que eu passei não aponta de forma exata para o local onde o arquivo está armazenado em meu computador. Imaginando que o mesmo estivesse salvo na pasta `USP` que por sua vez está armazenada na pasta `Documentos`, o caminho correto desse arquivo seria: `~/Documentos/USP/historia_digital.py`. Agora o python será capaz de encontrá-lo e executar as tarefas desejadas.

```python
>>> open('~/Documentos/USP/historia_digital.py', 'r').read()
>>> 'print("Olá, História Digital!")'
```

E o que isso tem a ver conosco?

Assim como no exemplo do python, nossas pesquisas, cada vez mais mediadas, viabilizadas e mesmo engendradas por ferramentas, métodos e dados digitais, demandam precisão metodológica mais cuidadosa e desta precisão, e do seu respectivo registro, depende a própria possibilidade de execução da pesquisa. 

Em outras palavras, o desenvolvimento e aplicação de metodologias documentadas e precisas são fundamentais para a produção do conhecimento. Isso parece óbvio, porém o que percebemos, e nisso eu me incluo e imagino que falo pela maioria de nós, é que as pesquisas mediadas e baseadas em dados digitais têm, no melhor dos cenários, apenas emulado padrões metodológicos analógicos sobre um universo de recursos digitais que gera resultados comumente inverificáveis, não-reproduzíveis, e dificilmente escrutináveis.

Uma pesquisa que se utiliza de buscas digitais em repositórios, como a HDB, não pode prescindir do registro detalhado dos parâmetros utilizados e da publicização tanto das escolhas feitas como dos resultados obtidos. Caso contrário, o conhecimento histórico produzido estará sempre subordinado aos vieses e direcionamentos de conjuntos de decisões técnicas e políticas que forma as páginas de buscas que utilizamos.

Como numa linguagem de programação, sem o registro preciso do caminho que leva desde a raiz até o arquivo final, nossa pesquisa em História está sujeita ao constante `erro` do caminho não encontrado. 

## Quais caminhos até chegar aqui?

Há um emaranhado de caminhos trilhados e outros tantos abandonados para eu chegar aqui, sentado nessa mesa tão importante, usando um blazer pra fingir que eu sou sério. Caminhos da própria relação entre história e o digital, entre nosso fazer historiográfico e a computação, mas também dos meus caminhos pessoais. 

Mais do que uma *ego-história* ou a realização da ilusão biográfica, alertada por Bourdieu, vou falar brevemente dessa trajetória individual, pois possibilita refletir sobre mudanças que de alguma forma afetam a todos e todas.

###  Meus caminhos pessoais: do analógico ao digital à programação

A minha formação foi toda em História, na Universidade Federal Fluminense, lá em Niterói, no Rio de Janeiro. Os meus estudos iniciais foram bastante ligados à história social da cultura. Eu trabalho, sobretudo, com pesquisas que buscam compreender as experiências sociais das pessoas que faziam o carnaval no fim do século 19 e no início do século 20, inicialmente no Rio de Janeiro, mas as pesquisas avançaram pelas afro-américas. Acabei pesquisando sobre experiências similares às das associações carnavalescas do Rio de Janeiro, comparando às de Trinidad e Tobago no Caribe. A minha pesquisa é muito ancorada numa história social thompsoniana buscando olhar para cultura e as relações materiais por trás daquilo que possibilita a atuação pública dessas pessoas. O meu estudo era, até bem recentemente, bastante “clássico” por trabalhar com fontes impressas e com jornais, sobretudo, mas também com muita documentação policial, pois nós que estudamos cultura popular e as pessoas que não detém os meios de produção, trabalhamos muito com documentação policial, com relatos de jornal produzido por aqueles que queriam perseguir e que queriam reprimir essas pessoas, as suas formas de experiências e escolhas na disputa pelo espaço público. 

O doutorado foi um momento em que me desperta uma reflexão metodológica, a partir de um conjunto de dados digitais e ferramentas digitais que eu comecei a utilizar de forma intuitiva e pouco criteriosa - e eu acho que isso é uma coisa comum para a grande maioria dos pesquisadores contemporâneos, que estão hoje na ativa. 

Após a defesa do doutorado, em 2016, eu eu me tornei professor da UNILAB - Universidade da Integração Internacional da Lusofonia Afro-brasileira, no Campus dos Malês, aqui na Bahia onde sou professor de História da América até hoje. E aí eu acabei me aprofundando nesse debate, sobretudo com o professor Leonardo Nascimento, que era professor de metodologia da UNILAB àquela altura, e que depois passou para UFBA, onde montou o Laboratório de Humanidades Digitais do qual eu também sou membro. E eu não tenho dúvida que foi ali com os debates, diretamente com ele, que é especialista já há muito tempo em Sociologia Digital que eu percebi que muitas daquelas questões que eu estava levantando não eram novas, necessariamente, e já havia uma literatura importante por trás, mas que a gente, partindo das nossas experiências, do Brasil, das pesquisas de história social, tinha muito a contribuir. Então a partir daí que eu entrei de vez em 2017-18 na pesquisa de História Digital, entendendo o que eram as Humanidades Digitais. E estou aí, há uns cinco anos, pesquisando isso. Tanto que quase não me chamam mais para falar de carnaval. Agora só querem me chamar para falar de humanidades digitais. Eu gosto também, mas de vez em quando eu fico com saudade de falar  sobre carnaval (risos). 

### Breve história do uso da computação na História: de Busa ao Programming historian

Eu acho que todo mundo que inicia, ou se depara pela primeira vez com um debate sobre Humanidades Digitais, tende a entender, ou achar, que ele é muito novo, porque nós estamos mergulhados nessa transformação social profunda que é a centralidade do digital nas relações sociais. E aí quando a gente vai estudar um pouco a gente percebe que ela também tem uma história longa. O termo Humanidades Digitais é recente para a história, porque ele vai surgir já no século 21 e vai se popularizar muito na década de 2010, principalmente com uma série de seminários e eventos e também com Manifesto das Humanidades Digitais que eu não vou arriscar a datar aqui para eu não errar, mas ele é um termo recente nesse sentido. Porém há uma longa história do uso dos computadores nas pesquisas em humanidades, e isso remonta lá aos anos 1950, com famoso e sempre citado projeto do padre Busa, em parceria com a IBM e que só finaliza nos anos 1970, se eu não me engano, uma codificação da produção do São Tomás de Aquino. Isso começa com um trabalho gigante de criação daqueles cartões perfurados para você programar os computadores. Hoje esse é um trabalho reconhecido como pioneiro e tinha um grande aporte tecnológico da IBM, - e que durante muito tempo, também silenciou o trabalho das mulheres que estavam lá fazendo os cartões e todo o crédito vai cair só na conta do Padre Busa. 

Além disso, tem muitos outros caminhos de utilização dos computadores na História e nas Humanidades. Nos anos 1960, mesmo nos avanço das pesquisas de História serial e dos Annales dos anos 60-70, e tem uma série de trabalhos de Cliometria, nos anos 1960. Tem uma série de estudos e revistas sobre computação e História até os anos 1980. A gente encontra muito referências a computação em história computing in History, e tem muitos trabalhos assim; mas o que vai catalisar esse movimento vão ser os trabalhos de linguística, e o Boom das digitalizações dos anos 1990. 

É uma virada importante nos anos 1990, com os grandes projetos de digitalização em massa de fontes, de livros. Isso vai começar a dar uma outra força para esse movimento e que vai, inclusive, possibilitar pesquisas linguísticas de longa duração, os estudos de que eles chamam de ngrams, as palavras repetidas e a história desses conceitos ao longo do tempo. Isso começa a crescer e ganhar muita força nos anos 1990. E nos anos 2000 a gente tem essa virada, sobretudo com a web 2.0, de essa internet mais interativa, a ampliação das interfaces gráficas para usuários e depois o surgimemnto das redes sociais. 

Tudo isso faz com que você tenha uma explosão das pesquisas e que vai desembocar no que a gente chama de Humanidades Digitais. É interessante perceber que há estudos que mostram uma a queda no uso do termo Computação e História e o crescimento de Humanidades Digitais e História Digital, em livros, seminários, congressos. Há uma mudança nesse campo. E aí, sim, a gente pode falar de um campo que está se constituindo, mas essa constituição começa no fim do século 20, em muitos centros importantes.

Adam Crymble que chama  Technology & the Historian, que fala que a gente precisa, mais do que definir a história digital, (e eu acho que isso serve para as Humanidades como um todo), a gente precisa fazer as suas histórias. Eu acho que, talvez, no Brasil, a gente esteja no momento de precisar fazer essas histórias dos usos da tecnologia na historiografia e isso serve para as outras áreas. 

Você vê trabalhos, desde os anos 1980, que utilizam o computador, que vão lidar com bancos de dados. E aí falando sobre história da escravidão: os inventários, as  digitalizações dos livros de paróquia e todo um trabalho da história oral que foi feito durante décadas, o trabalho do Tiago Gil lá na UnB que já tem um tempo longo. Então há uma história que precisa ser feita, mas a gente tem visto muitos trabalhos surgindo com esse desejo da novidade, o que me parecer normal num campo em disputa, mas que precisa ser mais sustentado por uma história dessa historiografia.

O campo das Humanidades Digitais é, hoje, bem consolidado no mundo, sobretudo no mundo do capitalismo dominante.  Se a gente pensar nos Estados Unidos e a Europa ocidental, a gente tem uma rede bem estabelecida, projetos de longa duração, laboratórios muito consolidados que têm produção de  ferramentas e que tem cargos de engenheiro de projetos e coisas assim. Essas são perspectivas que a gente ainda não está discutindo. E não tem financiamento para isso, não tem recurso para isso, não tem uma política pública ainda. Existem algumas iniciativas aqui, mas a gente não pode pensar em Humanidades Digitais sem pensar em desigualdades globais de acúmulo de capital e de poder. 

### História Digital existe? (Comunidade de práticas? Virada laboratorial?)

#### Uma volta aos números?

Destacar a crítica do Tiago Gil: Humano antes do digital + história digital vista de baixo. Ou História Digital Social (Brasil, Eric, e Leonardo Nascimento. “Por uma História Social Digital: o uso do CAQDAS na pesquisa e escrita da História”. Em **História digital: A historiografia diante dos recursos e demandas de um novo tempo**, organizado por José D’Assunção Barros, 228–52. Petrópolis, RJ: Editora Vozes, 2022.)

#### Prática e Teoria?

Pensar no conceito de comunidade de práticas e a virada laboratorial:

Daniel Alves.

Exemplos de laboratórios: Tem uma série de laboratórios sendo criados, e a gente tem o Laboratório de Humanidades digitais da UFBA, que atualmente tem uma pesquisa reconhecida internacionalmente sobre os grupos de extrema direita no Telegram. E isso tem sido um carro chefe do laboratório, possibilitando a interação com diversos outros grupos internacionais e nacionais. O laboratório tem parceria com laboratório da Universidade Nova de Lisboa, com a FGV no Rio, que tem um laboratório importante; tem um laboratório da PUC  no Rio. Enfim, eu vou acabar esquecendo vários, mas tem um o Centro de Humanidade Digital da Unicamp. E acabou de ser criado um laboratório de ensino e história digital na universidade de Roraima.  Enfim, eu percebo que há um movimento em expansão. Tem os cursos tradicionais de metodologia lá em Minas e tem um monte de iniciativas. Talvez, a iniciativa mais importante seja um mestrado de Humanidades Digitais na Universidade Federal do Rio de Janeiro. E é recente e formou as primeiras turmas agora, se eu não me engano. E aí, sim, é um mestrado específico voltado para as Humanidades Digitais que é profundamente multidisciplinar e interdisciplinar. E tem o IBICT com o LARHUD - Laboratório em Rede de Humanidades Digitais,   sob a liderança do Ricardo Pimenta. Enfim, eu acho que falta, talvez, mais a conexão entre esses espaços e uma política pública mais eficiente. Recentemente, liderado pelo IBICT,  foi criada a rede de Humanidade Digitais com o LAB- HD e tem o pessoal de Natal,  da UFBA,  do Paraná,  da UnB, do Rio e é uma rede que tem o intuito de mapear e compreender esse movimento para  pautar a políticas públicas. Eles lançaram o Manifesto de  Pirenópolis, com o pessoal da Unicamp,  do laboratório do Leonardo Nascimento com essa preocupação de construir essa rede que possibilite,  com financiamento público,  com o apoio do governo federal, possibilitar, compreender em que pé que a gente está e avançar.

Avançar com a ideia de *Digital Hermeneutics*[^dig-herm]

Relação com a comunidade de práticas e a virada laboratorial

>combination of critical digital skills with a self-re exive approach is called digital hermeneutics (Fickers, Andreas 2020, Tatarinov, Fickers 2022, DTU 2021 ): making explicit how the production of historical knowledge by means of digital tools and technologies is the result of a complex process of human-machine interaction, of co-construction of the “epistemic object” of historical inquiry and investigation ( Rheinberger 2010, Spencer 2019).

Precisamos avançar nas reflexões epistemológicas

[^dig-herm]: Fickers, Andreas, e Frédéric Clavert. “On Pyramids, Prisms, and Scalable Reading”. *Journal of Digital History*, nº jdh001 (18 de outubro de 2021). https://doi.org/10.1515/JDH-2021-1008?locatt=label:JDHFULL.
Fickers, Andreas, e Juliane Tatarinov, orgs. **Digital History and Hermeneutics: Between Theory and Practice**. De Gruyter, 2022. https://doi.org/10.1515/9783110723991.


## A técnica afetando a epistemologia

### A mediação das plataformas e motores de busca

Sem conhecimento técnico não teremos como fazer nosso trabalho!

Um caso emblemático: a HDB, seus vieses e potencialidades

## Afinal, como pesquisamos e o que demandamos?

- Caso dos docentes das IES da Bahia

## Futuro e presente

- Formação técnica
- Reflexões epistemológicas
- Colaboração, transparência, ciência aberta
- Financiamento, políticas públicas
