# Prompt — Landing Page Speak'App (Beta Launch)

---

## Contexto

Crie uma **landing page completa em HTML/CSS/JS (single file)** para o app **Speak'App** — um aplicativo de aprendizado de inglês conversacional para brasileiros. A página é voltada para os **10 primeiros beta testers**, com lançamento previsto para **31 de março de 2025**.

---

## Identidade do produto

- **Nome:** Speak'App
- **Proposta:** App de inglês focado em conversação real, para quem quer sair do A1/A2 e chegar no B1 falando de verdade — sem decorar gramática, sem aula chata.
- **Público:** Brasileiros adultos, 25–45 anos, que precisam de inglês no trabalho ou viagem mas nunca conseguiram "engatar" de vez.
- **Tom:** Direto, motivador, sem frescura. Fala como amigo, não como professor.

---

## Estrutura da página

### 1. Hero Section
- Headline impactante em português (ex: *"Inglês de verdade. Na conversa, não na teoria."*)
- Subheadline de 1–2 linhas explicando o app
- **Contador regressivo GIGANTE** para o dia **31 de março de 2025** (dias, horas, minutos, segundos) — o contador deve ser o elemento visual dominante da seção
- Badge ou etiqueta visual: **"Apenas 10 vagas · Beta exclusivo"**
- Botão CTA: **"Quero ser beta tester"** (âncora para formulário no final)

### 2. Como vai funcionar (para os beta testers)
Cards ou seção explicando o processo em etapas simples:
1. **Você se inscreve** — Preenche um breve formulário com seu nível atual de inglês
2. **Recebe acesso antecipado** — No dia 31/03, link exclusivo direto no seu e-mail
3. **Usa o app por 30 dias grátis** — Acesso total a todas as funcionalidades
4. **Nos dá feedback** — Uma conversa de 20min por vídeo ao fim do período (opcional mas muito valorizado)
5. **Continua com desconto vitalício** — Beta testers ganham 50% off para sempre

### 3. O que o app faz
Explicação breve (3–4 bullets ou cards) sobre as features principais:
- Conversas guiadas com IA em inglês, adaptadas ao seu nível
- Correção em tempo real da sua pronúncia e gramática
- Sessões curtas de 1–3 minutos, perfeitas para o dia a dia
- Progresso visível: do silêncio ao B1 conversacional

### 4. Quem está construindo isso
Tom pessoal e humano. Algo como:
> "Sou dev brasileiro, aprendi inglês na marra, e sei exatamente onde o processo trava. Construí o Speak'App pra resolver isso de um jeito que funcionou pra mim — e que pode funcionar pra você."
*(Sem foto, pode usar um avatar ilustrado ou ícone)*

### 5. Formulário de inscrição (CTA final)
Campos simples:
- Nome
- E-mail
- Nível atual de inglês (select: Básico / Intermediário / Nunca estudei)
- Botão: **"Garantir minha vaga"**

Abaixo do botão: *"Vagas restantes: 10 de 10"* (pode ser mockup estático por enquanto)

---

## Direção estética

- **Tema:** Dark mode — fundo quase preto (#0d0d0d ou similar), texto branco/off-white
- **Acento de cor:** Verde-limão vibrante (#AAFF00 ou similar) — para CTAs, destaques, bordas do contador
- **Tipografia:** Display font bold e moderna para headlines (ex: Syne, Clash Display, ou similar via Google Fonts). Body legível (ex: DM Sans, Outfit).
- **Atmosfera:** Energia de startup brasileira — não é corporativo, não é "escola de idiomas". É produto tech, mas com calor humano.
- **Contador:** Deve ter estilo de "relógio de lançamento de foguete" — blocos grandes, numéricos, com separadores animados. É o coração visual da página.
- **Animações:** Entrada suave dos elementos no scroll. O contador deve pulsar ou ter um brilho sutil a cada segundo que passa.
- **Mobile-first:** A página deve funcionar perfeitamente no celular.

---

## Requisitos técnicos

- **Single HTML file** (CSS e JS inline/embedded — sem dependências externas exceto Google Fonts e fontes de CDN pública)
- Contador em JavaScript calculando a diferença entre `Date.now()` e `new Date('2025-03-31T00:00:00')` em tempo real
- Formulário **não precisa ter backend** — ao submeter, exibe uma mensagem de confirmação na tela (ex: *"Inscrição recebida! Você vai receber nosso e-mail até 31/03."*)
- Sem frameworks (React, Vue etc.) — HTML/CSS/JS puro

---

## Entregável

Um arquivo `index.html` completo, funcional, pronto para subir em qualquer hosting estático (Vercel, Netlify, GitHub Pages).
