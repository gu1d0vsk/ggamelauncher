<img width="730" height="242" alt="banner" src="https://github.com/user-attachments/assets/a9810b44-8d4c-4656-912f-e3c2072215e7" />


Um launcher de jogos para PC minimalista.
---

## ✨ Destaques e Funcionalidades

- 🕹️ **Navegação Nativa por Controle:** Mapeado para controles de Xbox/PlayStation. Navegue, edite e inicie jogos sem tocar no mouse.
- 📖 **Diário de Jogos (Journal):** Registre os jogos Finalizados, congele jogos na *Geladeira* e acompanhe os próximos lançamentos no *Radar*.
- 🤖 **Auto-Cura e Integração RAWG:** Adicionou um `.exe` e esqueceu a capa? O launcher busca automaticamente artes em alta resolução (SteamGridDB), sinopses traduzidas, gênero e notas do Metacritic (RAWG API) em segundo plano.
- 🎨 **UI Fluida:** Interface limpa, artes wide de fundo, modo Grid ou Carrossel, e destaques sutis em neon.
- ⚡ **Leve e Otimizado:** Minimiza para a bandeja do sistema ou fecha completamente ao iniciar um jogo para liberar 100% da sua memória RAM.

---

## 📸 Galeria

Aqui está uma olhada no GGameLauncher em ação:

### Visão Principal (Carrossel / Banner)
<img width="1561" height="981" alt="image" src="https://github.com/user-attachments/assets/a218162a-cb37-4e29-9558-4770667a14b1" />

*Navegação fluida com artes wide em tela cheia e informações automáticas.*

### Visão em Grade (Grid)
<img width="1571" height="980" alt="image" src="https://github.com/user-attachments/assets/4ccc1724-971e-429a-a8a6-c96ad93ecb30" />
*Para quem prefere ver toda a biblioteca de uma vez.*

### Diário de Jogos 
<img width="1577" height="985" alt="image" src="https://github.com/user-attachments/assets/b84e3796-e824-4747-875b-cbf2b4744306" />
*Acompanhe seu progresso, dê notas e gere "Cards de Conquista" para compartilhar.*

### Calendário de Lançamentos
<img width="1573" height="977" alt="image" src="https://github.com/user-attachments/assets/e33ab43c-217d-4b81-993c-94ed5f0ce3c0" />
*Saiba quais jogos estão saindo na próxima semana com trailers integrados.*

---

## 📥 Como Instalar e Usar

1. Acesse a aba de [Releases](../../releases) aqui no GitHub.
2. Baixe o instalador mais recente (`GGameLauncher_Setup.exe`).
3. Execute o instalador. 
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
| **Chamar Launcher** | `Start` + `Back` (Segurar) | `Ctrl` + `Shift` + `L` |

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
