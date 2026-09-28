# ⚡ ESCALAS.MUSICAIS — Sistema Cósmico de Aprendizado Musical

Uma aplicação web interativa, futurista e responsiva voltada para o estudo de escalas musicais, cálculo de intervalos e visualização do braço (fretboard) em múltiplos instrumentos de cordas, equipada com síntese sonora em tempo real via **Web Audio API**.

---

## 🌟 Destaques e Funcionalidades

- 🎸 **Múltiplos Instrumentos de Cordas**:
  - **Contrabaixo** (4 cordas: E, A, D, G)
  - **Violão** (6 cordas: E, A, D, G, B, E)
  - **Ukulele** (4 cordas: G, C, E, A)
  - **Cavaquinho** (4 cordas: D, G, B, E)

- 🎵 **10 Escalas Essenciais**:
  1. **Maior (Jônica)** — Som alegre e estruturado.
  2. **Menor Natural (Eólia)** — Som melancólico e introspectivo.
  3. **Pentatônica Menor** — Clássico do rock, blues e metal.
  4. **Pentatônica Maior** — Som fluido, leve e pop-rock.
  5. **Dórica** — Tom jazzy e sofisticado.
  6. **Frígia** — Sotaque exótico, espanhol/oriental.
  7. **Lídio** — Som etéreo, mágico e levitante.
  8. **Mixolídio** — O modo maior para rock e blues.
  9. **Menor Harmônica** — Drama neoclássico e cinematográfico.
  10. **Blues Menor** — Com a marcante *blue note* (5ª diminuída/4ª aumentada).

- 🔊 **Síntese Sonora via Web Audio API**:
  - Som em tempo real ao clicar em qualquer casa do braço do instrumento, corda solta, botão de nota ou sequência de exercícios.
  - Botão de alternância de áudio (🔊 Som ON / 🔇 Som OFF) no cabeçalho.
  - 100% nativo no navegador — sem dependência de carregamento de arquivos áudio externos.

- 📏 **Calculadora de Intervalos**:
  - Clique em 2 notas no braço do instrumento para calcular instantaneamente o intervalo (Semitom, 3ª Menor, 5ª Justa, Trítono, etc.) e ler sua explicação teórica e contexto harmônico.

- 🎯 **Gerador de Exercícios & Improviso**:
  - **Sequência Aleatória**: Gera sequências de notas dentro da escala para treino de solo e percepção.
  - **Cordas Soltas Primeiro**: Exercício gradual para ganho de confiança.

- 🎧 **Exemplos de Bandas & Tons**:
  - Associação prática entre escalas e estilos/bandas famosas (*Blink-182, Nirvana, Deftones, Dream Theater, System of a Down, Alice in Chains, Yngwie Malmsteen*, etc.).

- ⚡ **Design Cyberpunk & Responsivo**:
  - Estética futurista inspirada em ficção científica, com efeito *Matrix rain* na tela de abertura, tipografia neon (`Orbitron`), efeitos de *scanline* e suporte perfeito para dispositivos móveis e desktops.

---

## 🚀 Como Executar

Não é necessária nenhuma instalação ou compilação de dependências.

### 1. Abrir diretamente no navegador
Basta dar um duplo clique ou abrir o arquivo `index.html` (ou `escalas.html`) em qualquer navegador moderno (*Google Chrome, Mozilla Firefox, Microsoft Edge, Safari*).

### 2. Servidor local (opcional)
Se preferir rodar através de um servidor HTTP local:

**Usando Python:**
```bash
python3 -m http.server 8000
```
Acesse no navegador: `http://localhost:8000`

**Usando Node.js / npx:**
```bash
npx serve .
```

---

## 💻 Tecnologias Utilizadas

- **HTML5**: Estruturação semântica da aplicação.
- **CSS3**: CSS Grid, Flexbox, animações customizadas (`matrix-fall`, `neon-flicker`, `scan-lines`), temas com variáveis CSS.
- **JavaScript (ES6+)**: Lógica harmônica, cálculo de escalas/intervalos e manipulação do DOM.
- **Web Audio API**: Geração e manipulação de osciladores para síntese sonora de alta performance.

---

## 📂 Estrutura do Repositório

```
escalas-musicais/
├── index.html        # Ponto de entrada principal (symlink/cópia de escalas.html)
├── escalas.html      # Aplicação web completa (HTML, CSS e JS)
├── LICENSE           # Licença de código aberto (MIT)
└── README.md         # Documentação do projeto
```

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE). Sinta-se livre para usar, modificar e distribuir.