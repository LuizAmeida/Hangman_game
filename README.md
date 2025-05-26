# 🎯 Jogo da Forca: O Desafio da Forca que Você Respeita! 🎯

Prepare-se para testar sua mente! Este não é apenas mais um Jogo da Forca; é uma aventura clássica reinventada em **Python** com a elegância da **Programação Orientada a Objetos (POO)**. Aqui, cada letra conta e cada erro desenha um passo para o destino final do nosso amiguinho na forca! Você consegue adivinhar a palavra secreta antes que seja tarde demais?

---

### ✨ O Que Torna Este Jogo IMPERDÍVEL?

* **Palavras Fresquinhas!** 🍋 Cada rodada é uma surpresa! O jogo seleciona **automaticamente** uma palavra deliciosa (todas frutas, por enquanto!) de uma lista interna.
* **Visuais que Contam a História:** Veja a forca se desenhando! A cada erro, um novo segmento do boneco aparece, dando aquele friozinho na barriga.
* **Seis Chances para a Glória:** Você tem **6 tentativas** para acertar a palavra. Use-as com sabedoria!
* **Feedback de Mestre:** Saiba exatamente o que está rolando! O jogo mostra as letras que você já acertou na palavra, as que você errou (para não repetir!) e as que ainda são um mistério.
* **Tela Limpa, Mente Clara:** Nada de bagunça! A tela do console é **limpa automaticamente** a cada jogada para você focar no que importa.
* **Vitória ou Derrota?** O jogo te avisa! Ele sabe a hora exata de declarar um campeão ou, bem, o fim da linha para o boneco.

---

### 🎮 A Experiência de Jogo

Ao iniciar o **Jogo da Forca**, você será recebido com a forca vazia e a palavra secreta representada por underlines. O objetivo é digitar uma letra por vez para tentar adivinhar a palavra.

* **Acerte uma letra:** A letra aparecerá em todas as posições corretas na palavra escondida.
* **Erre uma letra:** Um novo pedaço do boneco da forca será desenhado, e a letra errada será exibida para que você não a repita.
* **Venceu:** Adivinhe todas as letras da palavra antes que o boneco esteja completo!
* **Perdeu:** Se o boneco for desenhado por completo (após 6 erros), você perde o jogo, e a palavra correta será revelada.

É simples, viciante e um ótimo exercício para o vocabulário!

---

### 🧠 Nos Bastidores: A Mágica da POO

O coração deste Jogo da Forca é a **classe `Hangman`**, um verdadeiro centro de comando que orquestra toda a lógica e os dados do jogo. É a prova de que código limpo e organizado faz toda a diferença!

#### **Estrutura Essencial:**

* **`import random` e `from os import system, name`**: As ferramentas secretas! `random` para escolher as palavras de forma divertida e `os` para aquela limpeza de tela mágica que funciona em qualquer sistema (Windows, Mac ou Linux).
* **`limpa_tela()`**: Sua faxineira pessoal no console! Garante que a interface esteja sempre organizada.
* **`board`**: A galeria de arte da forca! Uma lista que guarda cada estágio do nosso amigo, do nada à forca completa.

#### **A Alma do Jogo: Classe `Hangman`**

* **`__init__(self, palavra)`**: Onde a aventura começa! Define a palavra secreta e prepara as listas para suas `letras_erradas` e `letras_escolhidas`.
* **`guess(self, letra)`**: Sua jogada! Verifica se a letra está na palavra, se já foi tentada, e atualiza tudo. Inteligente, né?
* **`hangman_over(self)`**: O juiz do jogo! Decide se a partida já terminou (você venceu ou atingiu o limite de erros).
* **`hangman_won(self)`**: O momento da verdade! Confere se você desvendou a palavra secreta e saiu vitorioso.
* **`hide_palavra(self)`**: O esconde-esconde da palavra! Mostra as letras que você acertou e esconde as que faltam com `_`.
* **`print_game_status(self)`**: O painel de controle! Exibe o desenho da forca, a palavra com as letras adivinhadas, as letras erradas e as corretas já tentadas. Tudo na sua frente!

#### **Funções Globais Essenciais:**

* **`rand_palavra()`**: O sorteador oficial! Escolhe uma palavra aleatória da nossa lista de frutas para você adivinhar.
* **`main()`**: O maestro! É a função que inicia tudo, cuida do loop do jogo, pede suas jogadas e, no final, revela o desfecho da partida.

---

### 🚀 Como Executar?

É super fácil dar o play nessa diversão!

1.  **Salve o código:** Guarde tudo em um arquivo Python (tipo `jogo_da_forca.py`).
2.  **Abra seu terminal:** Seja no Prompt de Comando, Powershell ou Terminal.
3.  **Navegue:** Vá até a pasta onde você salvou o arquivo.
4.  **Execute:** Digite e aperte Enter:

    ```bash
    python jogo_da_forca.py
    ```

---

### 📝 Licença

Este projeto está licenciado sob a Licença MIT. Sinta-se à vontade para usar, modificar e distribuir este código, mas mantenha o aviso de direitos autorais.

Para mais detalhes, veja o arquivo [LICENSE](LICENSE).

---

### 🧑‍💻 Autor

Desenvolvido por: [Luiz Almeida/GitHub Luiz_Almeida]

---

**Divirta-se e prepare-se para adivinhar!** 🚀
