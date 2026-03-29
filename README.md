# ViToPaMoS - Visualizador e Tocador de Partituras para Moodle e Sites

**ViToPaMoS** é uma ferramenta pedagógica e profissional desenvolvida para transformar arquivos **MusicXML** em players de partitura interativos e responsivos, ideais para serem embutidos no **Moodle** ou em sites institucionais.

## 🎵 O que o ViToPaMoS faz?

- **Visualização de Partituras**: Renderização de alta fidelidade usando a biblioteca **OpenSheetMusicDisplay (OSMD)**.
- **Reprodução de Áudio MIDI**: Toca a música diretamente no navegador com timbres de piano e outros instrumentos de alta qualidade via **Soundfont-player**.
- **Controle Total**: Ajuste de **BPM**, **Transposição**, **Oitava**, **Reverb** e **Metrônomo**.
- **Mixagem de Instrumentos**: Painel para controlar **Mute** e **Solo** de cada parte/instrumento da partitura em tempo real.
- **Edição de Metadados**: Permite alterar o título, compositor e direitos autorais da peça antes da exportação.
- **Exportação "Moodle-Safe"**: Gera um código HTML único, autodependente (usando CDNs confiáveis) e com CSS defensivo para garantir que o visual não seja corrompido pelos estilos globais do Moodle.
- **Tema Híbrido**: Interface principal com modos Diurno e Noturno (ajustado para conforto visual).

## 🚀 Como usar

1.  **Carregar**: Clique em "Carregar Partitura (MusicXML)" e escolha seu arquivo `.xml`, `.musicxml` ou `.mxl`.
2.  **Configurar**: Ajuste o andamento (BPM), instrumentos e outros parâmetros no painel superior.
3.  **Tocar**: Use os botões de controle ou atalhos:
    - **Clique**: Play / Pause.
    - **Duplo Clique**: Parar.
    - **Triplo Clique**: Reiniciar do início.
4.  **Personalizar**: Abra o painel "Editar Metadados" para ajustar as informações da peça.
5.  **Exportar**: 
    - Use **"Copiar HTML para o Moodle"** para obter o código e colar diretamente no editor de páginas do Moodle (visão de código).
    - Use **"Baixar HTML do Player"** para salvar um arquivo `.html` independente com a partitura embutida.

## 🛠 Tecnologias utilizadas

- **OSMD (OpenSheetMusicDisplay)**: Renderização vetorial de partituras.
- **Soundfont-player**: Motor de som MIDI baseado em samples.
- **Vanilla JS & CSS**: Performance otimizada sem frameworks pesados.
- **Lucide Icons (SVG)**: Ícones profissionais integrados.

## 👨‍🏫 Créditos

Desenvolvido pelo professor **Glauber Santiago** (DAC/UFSCar).

---
*ViToPaMoS — Transformando partituras digitais em ferramentas de ensino acessíveis.*
