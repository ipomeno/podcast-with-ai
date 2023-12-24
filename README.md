# Projeto Podcast Gerado por I.A.s

Projeto com o objetivo de gerar um podcast utilizando ferramentas de IA. Não elaborei muito o projeto, pois atualmente não tenho interesse em trabalhar criando podcast. Meu foco agora é redes sociais, mas gostei de conhecer e experimentar as ferramentas de IA mostradas no curso. Serve como boa introdução para um trabalho inicial.

## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [MidJourney](https://www.midjourney.com/app/)
- [ElevenLabs](https://beta.elevenlabs.io/)
- [Capcut](https://www.capcut.com/pt-br/)

## Prompts usados no GPT

### Para criar o roteiro

Nada além de algumas modificações no prompt mostrado em aula.

```
Você é um roteirista de podcast, e vamos criar um podcast de tecnologia, focado em back-end e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos para um podcast de front end feito por nerds, e que tenha algum trocadilho nerd no nome.

O podcast vai falar sobre dicas e novidades sobre o mundo do back-end, como referência de código e técnicas javascript como padrões de projeto, escolha de nomes de variáveis, execução de código paralelo, trheads, alívio de pressão e etc.

{REGRAS}

- O nome deve ser enxuto, um nome e um subtítulo
- O nome deve ter referências ao mundo medieval, como magos, elfos, piratas como Cronicas de Nárnia, A aventura cósmica de C. S. Lewis ou algo semelhante
- O nome deve conter alguma palavra forte que remeta ao back-end

{REGRAS NEGATIVAS}

- Não quero que o título contenha palavras em inglês
- Não quero que utilize nenhuma das palavras nessa lista: Javascript, programador
- Não utilize a palavra back-end no nome nem qualquer variação dela
```

### Criação do texto para podcast

Também com pequenas modificações.

```
Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de tecnologia, focado em frontend cujo o nome é "Druidas Binários - Alquimia em Servidor" e tem foco em back-end,  com o público alvo de desenvolvedores iniciantes.

o formato do roteiro deve ser
[INTRODUÇÃO]
[CURIOSIDADE 1]
[CURIOSIDADE 2]
[FINALIZAÇÃO]

{REGRAS}

- no bloco [INTRODUÇÃO] substitua por uma introdução iguais as introduções dos vídeos do canal 'linhagem nerd', e uma linguagem figurada e humorística como Olavo de Carvalho, como se fossem escritos por eles.
- no bloco [CURIOSIDADE 1] substitua por uma curiosidade de NodeJs
- no bloco [CURIOSIDADE 2] sobre uma ferramenta para back-end
- no bloco [FINALIZAÇÃO] substitua por uma despedida nerd com o final 'Eu sou DB, o Druida Binário, e essa foi a Alquimia em servidor dessa semana'
- use termos de fácil explicação
- O podcast vai ser apresentado somente por uma pessoa, chamada DB (Druida Binário)
- O podcast deve ser curto

{REGRAS NEGATIVAS}

- Não use muitos termos técnicos
- Não ultrapasse 5 minutos de duração
```

## Áudio gerado no EventLabs

Segue o link
[Áudio do Event Labs](https://github.com/ipomeno/podcast-with-ai/blob/master/ElevenLabs_2023-12-24T15_58_01_Bill_pre_s50_sb75_se0_b_m2.mp3)

## Imagem de capa

A imagem foi tirada do Lexica.art, mas poderia ser gerada pelo MidJourney sem problema algum. Fui apenas para o mais rápido e prático.

[Imagem de Capa](https://lexica.art/prompt/701f46c6-166a-4d72-a30e-8d744b33caa9)
