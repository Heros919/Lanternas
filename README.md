# Lanternas

# 🌌 Espectro dos Lanternas (DC Comics)

Uma aplicação web interativa e temática dedicada às tropas do **Espectro Emocional** do universo da DC Comics. O projeto permite navegar por cada uma das 9 tropas, explorar os seus juramentos, heróis representantes, HQs marcantes, curiosidades e recursos multimédia.

---

## 🚀 Funcionalidades

* **Portal do Espectro:** O índice apresenta as nove tropas em um círculo de lanternas coloridas; cada lanterna abre a página dedicada àquela tropa.


* **Painel da Tropa Detalhado:**
* Informações de liderança, entidade, base de operações e emoção.


* **Juramentos e Som:** Reprodução em áudio do juramento (via ficheiro ou sintetizador de voz `SpeechSynthesis`).


* **Efeitos Sonoros:** Efeito sonoro do anel gerado em tempo real com a Web Audio API.


* Ficha completa do herói representante de cada tropa.




* **HQs Marcantes & Vídeos:** Galeria de capas históricas e links para vídeos/conteúdos explicativos.


* **Tabela Comparativa:** Visualização lado a lado de todas as tropas com atalho para abrir cada página.


* **Linha do Tempo:** Cronologia com os eventos e estreias mais importantes da franquia (1940–2010).


* **Quiz Interativo:** Questionário rápido para descobrir qual tropa combina com a personalidade do utilizador.


* **Glossário & Lore:** Conceitos fundamentais sobre Oa, Bateria Central, Guardiões do Universo e o funcionamento dos anéis.


* **Suporte a Tema Claro / Escuro:** Alternância de tema com persistência no `localStorage`.



---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível.


* **CSS3:** Variáveis CSS (`custom properties`), CSS Grid, Flexbox e `color-mix()` para transições de cor dinâmicas.


* **JavaScript (Vanilla):** Manipulação do DOM, gestão de estado simples, suporte a sintetizador de voz e Web Audio API.


* **Google Fonts:** Utilização das fontes *Big Shoulders Display*, *Barlow* e *IBM Plex Mono*.



---

## 📂 Estrutura de Pastas

```text
.
├── index.html           # Portal circular para escolher uma tropa
├── verde.html           # Página dos Lanternas Verdes
├── amarelo.html         # Página da Tropa Sinestro
├── vermelho.html        # Página dos Lanternas Vermelhos
├── azul.html            # Página dos Lanternas Azuis
├── indigo.html          # Página da Tribo Índigo
├── laranja.html         # Página do Lanterna Laranja
├── violeta.html         # Página das Safiras Estelares
├── branco.html          # Página do Lanterna Branco
├── preto.html           # Página dos Lanternas Negros
├── styles.css           # Estilização, layout e variáveis do tema
├── script.js            # Lógica, dados das tropas, quiz e áudio
├── img/                # Retratos dos heróis e capas de HQs
└── audio/              # Ficheiros de áudio dos juramentos (opcional)
```[cite: 3, 4, 5]

---

## 📦 Como Executar o Projeto

1. Faça o clone ou o download do repositório para o seu computador.
2. Certifique-se de que a estrutura de ficheiros e as pastas de media (`img/`, `audio/`) estão na mesma diretoria do `index.html`[cite: 4, 5].
3. Abra o ficheiro `index.html` em qualquer navegador web moderno.

> **Dica:** Para evitar bloqueios de segurança do navegador em ficheiros de áudio ou sintetizador de voz, recomenda-se abrir o projeto através de um servidor local (ex.: extensão **Live Server** no VS Code ou executando `python -m http.server` no terminal).

---

## 📜 Licença e Avisos

Site desenvolvido por fãs, sem vínculo comercial com a **DC Comics**[cite: 5]. Todas as imagens, personagens, nomes e marcas pertencem aos seus respetivos criadores e à DC Comics[cite: 5].

```