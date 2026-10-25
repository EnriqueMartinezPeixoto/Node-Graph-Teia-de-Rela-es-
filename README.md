# 🕸️ Node Graph | Teia de Nós

An infinite node graph canvas for organizing ideas, projects, mind maps, characters, and complex structures. It runs entirely as a single HTML file with no installation or servers required. Everything saves automatically right in your browser.
Um quadro infinito de nós (node graph) para organizar ideias, projetos, mapas mentais, personagens e estruturas complexas. Funciona em um único arquivo HTML, sem instalação e sem servidor. Tudo é salvo automaticamente direto no navegador.

## 🚀 Features | Recursos

* **Infinite Canvas | Quadro infinito:** Navigate by dragging the background and zoom from 15% to 300%.
  Navegue arrastando o fundo e use zoom de 15% a 300%.
* **Pins & Notes | Pinos e Notas:** Pins represent entities with an optional image, while Notes are free-text cards for detailed annotations.
  Pinos representam entidades com imagem opcional, enquanto Notas são cartões de texto livre para anotações detalhadas.
* **Connections | Ligações:** Link any two items and label the relationship on the line (e.g., "depends on", "ally").
  Conecte quaisquer dois itens e escreva o tipo de relação no meio da linha (ex.: "depende de", "aliado").
* **Colors & Legend | Cores e legenda:** Fully editable legend. Your custom colors become shortcuts in the edit panel.
  Legenda totalmente editável. Suas cores personalizadas viram atalhos no painel de edição.
* **Undo & Redo | Desfazer e refazer:** Up to 150 steps for any action (creating, moving, editing, deleting).
  Até 150 passos para qualquer alteração (criar, mover, editar, apagar).
* **Auto-Save & Backups | Salvamento automático e Backups:** The board state is stored in `localStorage`. You can also generate a text backup to save or restore your board.
  O estado do quadro é salvo no `localStorage`. Você também pode gerar um backup em texto para salvar ou restaurar seu quadro.

## 🖱️ How to Use | Como Usar

Open the HTML file in any modern browser. Double-click anywhere on the canvas to create a pin. Click an item to open the side panel and edit its properties. To connect items, hover over one, click the purple dot, and drag it to another item.
Abra o arquivo HTML em qualquer navegador moderno. Dê um duplo clique em qualquer lugar do quadro para criar um pino. Clique em um item para abrir o painel lateral e editar suas propriedades. Para conectar itens, passe o mouse sobre um, clique na bolinha roxa e arraste até outro item.

### Keyboard Shortcuts | Atalhos de Teclado

| Action | Ação | Shortcut / Atalho |
| :--- | :--- | :--- |
| **Create pin** | **Criar pino** | Double-click on background |
| **Navigate** | **Navegar** | Drag the background |
| **Zoom** | **Zoom** | Mouse wheel or − / + buttons |
| **Delete selected** | **Apagar selecionado** | `Delete` or `Backspace` |
| **Undo** | **Desfazer** | `Ctrl+Z` (`Cmd+Z` on Mac) |
| **Redo** | **Refazer** | `Ctrl+Y` or `Ctrl+Shift+Z` |
| **Center view** | **Centralizar visão** | ⌖ Button / Botão ⌖ |

## 💾 Data Storage | Armazenamento de Dados

Data is saved locally in the browser's local storage. This means it is tied to that specific browser and device. Clearing your browser's site data will erase the board. Make frequent backups using the "Backup" button.
Os dados são salvos localmente no armazenamento do navegador. Isso significa que estão ligados àquele navegador e dispositivo específicos. Limpar os dados de site do navegador apagará o quadro. Faça backups frequentemente usando o botão "Backup".

## 🚧 Known Limitations | Limitações Conhecidas

There is currently no pinch-to-zoom on mobile devices (use the on-screen buttons). Connections are straight lines without directional arrows, and there is no cloud syncing between different devices.
Atualmente não há zoom por pinça em dispositivos móveis (use os botões na tela). As conexões são linhas retas sem setas de direção, e não há sincronização em nuvem entre dispositivos diferentes.

## 🗺️ Roadmap | O que vem por aí

Future updates may include pinch-to-zoom for touch screens, directional arrows on connections, multi-selection, item grouping, and an option to export the canvas as an image file.
Futuras atualizações podem incluir zoom por pinça para telas de toque, setas de direção nas conexões, seleção múltipla, agrupamento de itens e uma opção para exportar o quadro como um arquivo de imagem.

## 📄 License | Licença

Built entirely in a single file using pure HTML, CSS, and vanilla JavaScript. Free to use for any commercial or personal projects. Adapt and modify as you see fit.
Construído inteiramente em um único arquivo usando HTML, CSS e JavaScript puros. Uso livre para quaisquer projetos comerciais ou pessoais. Adapte e modifique como achar melhor.
