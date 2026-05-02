<img width="2547" height="710" alt="abbeer" src="https://github.com/user-attachments/assets/9c4c3f89-5e00-44b5-b1c1-71e4bb434862" />


Um launcher de jogos para PC minimalista.
---

## ✨ Destaques e Funcionalidades

- 🕹️ **Navegação Nativa por Controle:** Mapeado para controles de Xbox/PlayStation. Navegue, edite e inicie jogos sem tocar no mouse.
- 📖 **Diário de Jogos (Journal):** Muito mais que um atalho. Registre os jogos Finalizados, congele jogos na *Geladeira* e acompanhe os próximos lançamentos no *Radar*.
- 🤖 **Auto-Cura e Integração RAWG:** Adicionou um `.exe` e esqueceu a capa? O launcher busca automaticamente artes em alta resolução (SteamGridDB), sinopses traduzidas, gênero e notas do Metacritic (RAWG API) em segundo plano.
- 🎨 **Glassmorphism e UI Fluida:** Interface limpa com desfoque dinâmico (blur), artes wide de fundo, modo Grid ou Carrossel, e destaques sutis em neon.
- ⚡ **Leve e Otimizado:** Minimiza para a bandeja do sistema ou fecha completamente ao iniciar um jogo para liberar 100% da sua memória RAM.

---

## 📸 Galeria

Aqui está uma olhada no GGameLauncher em ação:

### Visão Principal (Carrossel / Banner)
<img width="1575" height="980" alt="image" src="https://github.com/user-attachments/assets/822ce845-1e43-4c38-bb6a-851fd572e6ed" />


*Navegação fluida com artes wide em tela cheia e informações automáticas.*

### Visão em Grade (Grid)
<img width="1574" height="983" alt="image" src="https://github.com/user-attachments/assets/f0008462-5155-4ca3-bcd6-cdb3fedc5347" />

*Para quem prefere ver toda a biblioteca de uma vez.*

### Diário de Jogos 
<img width="1565" height="977" alt="image" src="https://github.com/user-attachments/assets/032006ea-7b90-4716-bb21-8de6e3035f31" />
*Acompanhe seu progresso, dê notas e gere "Cards de Conquista" para compartilhar.*

### Calendário de Lançamentos
<img width="1568" height="970" alt="image" src="https://github.com/user-attachments/assets/1358e740-8b64-47e3-8ea1-47cf9b6da7f1" />
*Saiba exatamente quais jogos estão saindo na próxima semana com trailers integrados.*

---

## 📥 Como Instalar e Usar

1. Acesse a aba de [Releases](../../releases) aqui no GitHub.
2. Baixe o instalador mais recente (`GGameLauncher_Setup.exe`).
3. Execute o instalador. **Importante:** Escolha a opção `Non administrative install mode (install for current user only)`. Isso garante que o aplicativo tenha permissão para salvar seus dados do Diário na pasta do usuário sem o Windows bloquear.
4. Abra o launcher, adicione o `.exe` dos seus jogos ou faça uma varredura automática!

---

## 🎮 Controles e Atalhos

O launcher foi desenhado para brilhar nas mãos. Aqui está o mapeamento atual:

| Ação | Controle (Xbox) | Teclado |
| :--- | :--- | :--- |
| **Iniciar Jogo / Confirmar** | `A` | `Enter` |
| **Voltar / Minimizar** | `B` | `Esc` |
| **Editar Jogo Selecionado** | `X` | `E` |
| **Próximos Lançamentos / Diário**| `Y` | - |
| **Adicionar Novo Jogo** | `Start` / `Menu` | - |
| **Mudar Aba / Modo Visualização**| `RB` | `F2` |
| **Mudar Aba / Modo Edição** | `LB` | `M` |
| **Alternar Ordenação** | `LT` | `Clique Mouse` |
| **Tela Cheia / Modo Janela** | `RT` | - |
| **Excluir Jogo** | - | `Delete` |
| **Chamar Launcher (Em Jogo)** | `Start` + `Back` (Segurar) | `Ctrl` + `Shift` + `L` |

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com:
* **[Flutter](https://flutter.dev/):** Para a interface multiplataforma.
* **[window_manager](https://pub.dev/packages/window_manager):** Controle avançado de janelas no Windows (Borderless, Blur, Tray).
* **[win32_gamepad](https://pub.dev/packages/win32_gamepad):** Comunicação nativa sem lag com controles XInput.
* **[audioplayers](https://pub.dev/packages/audioplayers):** Efeitos sonoros de navegação.
* **APIs:** SteamGridDB (Artes) e RAWG (Dados e Metadados).

---

## 🤝 Contribuição

Este é um projeto de uso pessoal.
