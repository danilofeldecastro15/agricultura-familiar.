# agricultura-familiar.

projeto produzido para o concurso do agrinho

# 🌍 Sustentabilidade na Agricultura Familiar — Quiz Interativo

Este é um projeto web interativo desenvolvido em HTML5, CSS3 e JavaScript (ES6+) focado na conscientização e educação sobre a **Agricultura Familiar**. Através de uma interface limpa, moderna e responsiva, o usuário aprende sobre a importância socioeconômica e ecológica dos pequenos produtores e testa seus conhecimentos em um **Quiz dinâmico dividido em fases com sistema de dicas**.

---

## 🌱 Sobre o Tema

A agricultura familiar é o verdadeiro coração da nossa alimentação, sendo responsável por cerca de 70% dos alimentos frescos que chegam às mesas brasileiras. Este ecossistema digital destaca os três pilares essenciais do setor:
1. **Diversidade no Prato:** O oposto das monoculturas exaustivas.
2. **Manejo Consciente:** Preservação de recursos híbridos e irrigação inteligente.
3. **Protetores da Vida:** Redução de insumos químicos e proteção ativa à biodiversidade (como polinizadores).

---

## 🏆 O Jogo: Desafio da Agricultura Familiar

O Quiz conta com **10 perguntas exclusivas** estruturadas de forma evolutiva e gamificada:

* **Fase 1: Introdução à Terra (Fácil) — Perguntas 1 a 3:** Conceitos básicos, importância nacional e economia de água.
* **Fase 2: Manejo Sustentável (Média) — Perguntas 4 a 7:** Rotação de culturas, bioinsumos, adubação verde e circuitos curtos de comercialização.
* **Fase 3: Mestre da Agroecologia (Difícil) — Perguntas 8 a 10:** Sistemas Agroflorestais (SAF), Sementes Crioulas e sequestro de carbono do solo.

### 💡 Mecânicas e Funcionalidades:
* **Sistema Antiduplicação:** Bloqueio inteligente de cliques para impedir que o usuário selecione mais de uma alternativa na mesma rodada.
* **Dicas em Tempo Real:** Caso o jogador selecione uma alternativa errada, o painel revela automaticamente uma **dica pedagógica personalizada** e marca em verde a resposta correta antes de permitir o avanço.
* **Ranking e Medalhas:** Ao fim do jogo, o script calcula o desempenho e entrega títulos dinâmicos baseados na pontuação (*Mestre Supremo da Terra*, *Produtor Sustentável* ou *Aprendiz do Campo*) permitindo reiniciar o desafio com um clique.

---

## 📁 Estrutura do Projeto

O código-fonte foi modularizado para facilitar a manutenção e leitura:

```text
├── index.html       # Estrutura semântica da página e containers do Quiz.
├── style.css        # Identidade visual (Paleta de cores em tons de Verde/Terra, cards e feedbacks visuais).
└── script.js        # Motor do Quiz (Banco de dados de questões, lógica de fases, dicas e pontuação).
