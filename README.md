# ⚡ ESCALAS.MUSICAIS — Sistema Cósmico de Aprendizado Musical

Uma aplicação web interativa, futurista e totalmente responsiva voltada para o estudo de escalas musicais, harmonia e visualização do braço (fretboard) em múltiplos instrumentos de cordas, equipada com síntese sonora em tempo real via **Web Audio API**.

---

## 🌟 Destaques e Funcionalidades

- 🎸 **Múltiplos Instrumentos de Cordas**:
  - **Contrabaixo** (4 cordas: E, A, D, G)
  - **Violão** (6 cordas: E, A, D, G, B, E)
  - **Ukulele** (4 cordas: G, C, E, A)
  - **Cavaquinho** (4 cordas: D, G, B, E)

- 🎵 **10 Escalas Essenciais**:
  1. **Maior (Jônica)** — Som alegre e estruturado.
  2. **Menor (Eólia)** — Som melancólico e introspectivo.
  3. **Pentatônica Menor** — Clássico do rock, blues e metal.
  4. **Pentatônica Maior** — Som fluido, leve e pop-rock.
  5. **Dórica** — Tom jazzy e sofisticado.
  6. **Frígia** — Sotaque exótico, espanhol/oriental.
  7. **Lídio** — Som etéreo, mágico e levitante.
  8. **Mixolídio** — O modo maior para rock e blues.
  9. **Menor Harmônica** — Drama neoclássico e cinematográfico.
  10. **Blues Menor** — Com a marcante *blue note* (5ª diminuída/4ª aumentada).

- 🔊 **Síntese Sonora via Web Audio API**:
  - Som em tempo real ao tocar em qualquer casa do braço, corda solta, botão de tônica ou notas da escala.
  - Efeito visual de *flash* ao tocar nas casas do instrumento.
  - Botão de alternância de áudio (🔊 Som ON / 🔇 Som OFF) no cabeçalho.
  - 100% nativo no navegador — sem dependência de carregamento de arquivos áudio externos.

- 🎛️ **Seletor de Escalas Dinâmico & Fluido**:
  - Grid de botões diretos de escala com indicação instantânea da escala ativa e resumo prático (descrição e modo de uso).

- 🎯 **Gerador de Exercícios & Improvisação**:
  - **Sequência Aleatória**: Gera sequências de notas dentro da escala para treino de solos e agilidade.
  - **Cordas Soltas Primeiro**: Exercício gradual para ganho de confiança no braço.

- 🎧 **Exemplos de Bandas & Tons**:
  - Associação prática entre escalas e estilos/bandas famosas (*Blink-182, Nirvana, Deftones, Dream Theater, System of a Down, Alice in Chains, Yngwie Malmsteen*, etc.).

- 📱 **Design Cyberpunk & Otimizado para Mobile**:
  - Alta legibilidade em dispositivos móveis e desktop com texto claro e alto contraste.
  - Tela inicial (*splash screen*) com rolagem completa em telas pequenas e animação *Matrix rain*.

---

## 🚀 Como Executar

Não é necessária nenhuma instalação ou compilação de dependências.

### 1. Abrir diretamente no navegador
Basta abrir o arquivo `index.html` (ou `escalas.html`) em qualquer navegador moderno (*Google Chrome, Mozilla Firefox, Microsoft Edge, Safari*).

### 2. Servidor local (opcional)
**Usando Python:**
```bash
python3 -m http.server 8000
```
Acesse no navegador: `http://localhost:8000`

---

## 💻 Tecnologias Utilizadas

- **HTML5**: Estruturação semântica e acessível.
- **CSS3**: CSS Grid, Flexbox, animações customizadas e variáveis CSS com alto contraste.
- **JavaScript (ES6+)**: Lógica harmônica, cálculo de escalas e manipulação do DOM.
- **Web Audio API**: Geração de osciladores para síntese sonora instantânea.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).