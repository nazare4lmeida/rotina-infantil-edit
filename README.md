# 🌟 Rotina Visual Edit

> Uma aplicação web interativa desenvolvida para auxiliar na organização da rotina diária de crianças com TEA (Transtorno do Espectro Autista) e TDAH, utilizando reforço visual positivo e gamificação.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Licença](https://img.shields.io/badge/Licença-MIT-blue)

---

## 🔗 Links
- **📱 Acesse o Projeto Online:** [https://rotina-infantil-edit.vercel.app/](https://rotina-infantil-edit.vercel.app/)
- **💻 Repositório:** [https://github.com/nazare4lmeida/rotina-infantil-edit](https://github.com/nazare4lmeida/rotina-infantil-edit)

---

## 🎯 Sobre o Projeto

Este projeto foi criado com o objetivo de fornecer suporte visual e previsibilidade para a rotina de uma criança. A interface foi desenhada para ser amigável, colorida e livre de estímulos sonoros bruscos.

### Principais Funcionalidades:
- **⏰ Relógio em Tempo Real:** Interface visual atrativa (estilo "moeda") que pisca os segundos.
- **🔔 Alarme Suave:** Utiliza a **Web Audio API** para gerar um som harmônico (sintetizado matematicamente) que não assusta a criança, dispensando arquivos de áudio externos.
- **🎨 Foco Visual:** A tarefa atual é destacada (aumenta de tamanho e muda de cor), enquanto tarefas passadas perdem opacidade.
- **⚙️ Totalmente Editável:** Possui um painel de configuração onde é possível alterar o **nome da criança**, horários, ícones e tarefas.
- **💾 Salvamento Automático:** Utiliza **LocalStorage** do navegador para salvar a rotina personalizada. Se fechar o site, a rotina continua lá.
- **🏆 Gamificação:** Botões interativos de "Start" e "Encerrar o Dia" com sons de vitória para gerar senso de conclusão.
- **📱 Responsivo:** Funciona bem em computadores, tablets e celulares.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando **HTML5, CSS3 e JavaScript (Vanilla)**, sem uso de frameworks pesados, garantindo leveza e performance.

- **HTML5:** Estrutura semântica.
- **CSS3:** Animações (`keyframes` para brilho e flutuação), Flexbox para layout e design responsivo.
- **JavaScript:**
  - Lógica de tempo e comparação de horários.
  - Manipulação do DOM.
  - **Web Audio API:** Para criação de sons diretamente pelo navegador.
  - **LocalStorage API:** Para persistência de dados da rotina.

---

## 🚀 Como Usar e Personalizar

### Para a Criança:
1.  Clique no botão **"🎮 Ligar Painel"** (Isso ativa o sistema de som do navegador).
2.  O painel destacará automaticamente a atividade do horário atual.
3.  Ao final do dia, clique em "Encerrar o Dia" para receber os parabéns!

### Para os Pais (Configuração):
Este aplicativo permite que você personalize totalmente a experiência para seu filho(a):

1.  Clique no ícone de engrenagem **(⚙️)** no canto superior direito.
2.  **Alterar o Nome:** No topo da tela de configuração, digite o nome da criança (ex: "Maria", "João"). O título do site mudará automaticamente para "Rotina da Maria".
3.  **Gerenciar Tarefas:**
    - Ajuste os horários.
    - Troque os ícones (use Emojis ou cole códigos de imagem).
    - Adicione ou remova tarefas conforme a necessidade do dia.
4.  Clique em **Salvar**.
5.  Caso queira voltar ao modelo original, clique no botão laranja **Restaurar Padrão**.

---

## 📦 Como rodar localmente

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/nazare4lmeida/rotina-infantil-edit.git](https://github.com/nazare4lmeida/rotina-infantil-edit.git)
    ```
2.  **Entre na pasta:**
    ```bash
    cd rotina-infantil-edit
    ```
3.  **Abra o arquivo:**
    Basta dar dois cliques no arquivo `index.html`.

---

## 👩‍💻 Autora

Feito com carinho por **Nazaré Almeida**.

---