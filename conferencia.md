---
title: 'caminho = input("Insira o caminho para História Digital: ")'
subtitle: "Conferência de abertura"
author: Eric Brasil
abstract: "História Digital e História Digital da Educação: Caminhos Cruzados. Instituto de Estudos Avançados da Universidade de São Paulo."
keywords: ['História Digital', 'História da Educação', 'Metodologia']
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

- Meus caminhos pessoais: do analógico ao digital à programação
- Breve história do uso da computação na História: de Busa ao Programming historian
- História Digital existe? (Comunidade de práticas? Virada laboratorial?)
- Humano ante do digital

## A técnica afetando a epistemologia

- A mediação das plataformas e motores de busca
- Um caso emblemático: a HDB, seus vieses e potencialidades

## Afinal, como pesquisamos e o que demandamos?

- Caso dos docentes das IES da Bahia

## Futuro e presente

- Formação técnica
- Reflexões epistemológicas
- Colaboração, transparência, ciência aberta
- Financiamento, políticas públicas
