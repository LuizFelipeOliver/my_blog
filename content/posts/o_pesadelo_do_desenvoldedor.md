+++
title = 'O nosso maior medo 🧑‍💻 🐛'
date = "2024-10-29T22:47:19-03:00"
author = "Luiz Oliveira"
authorTwitter = "" #do not include @
cover = "img/o_pesadelo_do_desenvoldedor.png"
coverCaption = ""
tags = ["halloween", "sazonal"]
keywords = ["halloween", "sazonal", "especial"]
description = "É comemoração ao Halloween, quem nunca sentiu este medo no dia a dia de um programador ?"
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++

Sim, todos nós temos medo disso: fazer um deploy e quebrar um site é uma experiência que qualquer profissional da web já sentiu ou ainda vai sentir. Eu mesmo já passei por isso: 😬 o time preocupado, clientes ligando para saber o que aconteceu 📞, e você tentando identificar, o mais rápido possível, o que deu errado. No fim, é sempre aquele pequeno detalhe que foi esquecido (já conferiu a linha 32? 😉).

Certamente existem formas de prevenir esses problemas, e uma delas é o bom e velho teste ✅. Existem várias maneiras de fazer isso, mas hoje quero falar de algo mais assustador 🎃, muito mais perigoso ⚠️, algo que pode custar seu emprego ou pior. Estou falando de: **Software de Sistemas Críticos** 💻.

Sistemas críticos são aqueles cujo mau funcionamento pode trazer consequências graves, incluindo danos monetários 💸, riscos à vida humana ❤️, danos a propriedades 🏠 ou ao meio ambiente 🌍. Exemplo disso são sistemas que controlam usinas nucleares ☢️, o sistema de voo de aeronaves ✈️ ou as operações bancárias 💳 (já pensou em trabalhar em um banco?). Já parou para pensar se o código que você escreve estaria preparado para isso? É uma responsabilidade e tanto, não? Imagine programar um marca-passo ❤️‍🩹, onde o seu código literalmente cuida da vida de alguém – ou, pior, descobrir que há um bug 🐛 que, sem atualizações ou hotfix, permanecerá lá para sempre 🔒.

Isso tudo me faz refletir sobre como nossa profissão envolve deveres de segurança no código que escrevemos 🔐, não só para nós, mas para quem o utiliza. Escrever código seguro e confiável é crucial para nós e para os outros 🧑‍💻.

---

Bem, saindo um pouco dessa parte assustadora 🕸️, você sabia que existem normas específicas para esses tipos de software? Por exemplo:

### DO-178C ✈️

Essa norma é voltada para software em sistemas aéreos e define diretrizes de segurança 🛠️, dividindo-se em cinco níveis de criticidade: *A*, *B*, *C*, *D* e *E*.

1. **Nível A**: Representa o maior risco ⚠️ e é considerado crítico para o voo, estando associado a consequências catastróficas em caso de falha. Exemplos:
   - Controle de voo 🛫
   - Piloto automático 🧑‍✈️
   - Controle de motor 🔧

2. **Nível B**: Ainda é considerado grave, mas não tanto quanto o nível A. Pode resultar numa redução significativa nas margens de segurança ou na funcionalidade ⚙️. Exemplos:
   - Sistemas de navegação 🧭
   - Certos subsistemas aviônicos 📡

3. **Nível C**: Associado a falhas que podem causar um impacto considerável na segurança das aeronaves, mas que não são catastróficas. Esses erros podem causar ferimentos leves ou reduzir a segurança ✋. Exemplos:
   - Sistemas de comunicação 📞

4. **Nível D**: As falhas neste nível têm um impacto limitado na segurança de passageiros e tripulação, com recuperação possível 🚸. Exemplos:
   - Sistemas de entretenimento de passageiros 🎬
   - Alguns sistemas de cabine 🚪

5. **Nível E**: É o nível mais baixo de criticidade e falhas aqui não têm impacto na segurança da aeronave ✈️, geralmente relacionados a conforto e conveniência. Exemplos:
   - Entretenimento a bordo 📺
   - Iluminação da cabine 💡

---

Outro exemplo importante é a:

### ISO 26262 🚗

Essa ISO trata da segurança funcional de sistemas elétricos e eletrônicos em veículos 🚘, abrangendo o ciclo de vida do desenvolvimento, da concepção à operação 🔄. Ela define níveis de Integridade de Segurança Automotiva (ASIL - Automotive Safety Integrity Level) que vão de ASIL A (menor rigor) até ASIL D (maior rigor) 🏆. O ASIL é determinado com base em três fatores:

- **Gravidade** 🩸
- **Exposição** 🌦️
- **Controlabilidade** 🛑

**_Gravidade_** avalia o potencial de dano pessoal ou material em caso de falha:
   - S3: De risco de vida a fatal ⚰️
   - S2: Lesões graves a risco de vida 🚑
   - S1: Lesões leves a moderadas 🩹
   - S0: Sem ferimentos 😊

**_Exposição_** mede a probabilidade de uma falha resultar em um risco de segurança:
   - E4: Alta probabilidade 🚨
   - E3: Probabilidade moderada 🔄
   - E2: Baixa probabilidade ❔
   - E1: Muito baixa 👌
   - E0: Muito improvável 😌

**_Controlabilidade_** mede a probabilidade de evitar o dano quando ocorre uma situação perigosa:
   - C3: Difícil ou impossível de controlar ❌
   - C2: Normal, com a maioria das ações do motorista evitando lesões 🚗
   - C1: Simplesmente controlável 👌
   - C0: Facilmente controlável ✅

Combinando esses fatores, é possível determinar o nível ASIL do sistema 📊.

---

Esses são apenas exemplos de algumas normas existentes para sistemas críticos 📝. Poderia escrever horas sobre outras, mas isso é apenas um post de Halloween 🎃 (não que eu não possa me aprofundar mais no futuro!). No final, isso tudo serve para lembrar o quanto a nossa profissão é uma responsabilidade. E aí, ainda pensa em fazer aquele deploy na sexta-feira? 😉

