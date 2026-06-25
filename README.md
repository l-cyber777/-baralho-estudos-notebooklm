# 🃏 Caderno Temático: Aprendendo Jogos de Baralho com IA

> Projeto desenvolvido como parte do desafio da DIO — uso de IA Generativa (NotebookLM) para criação de caderno de estudos temático.

---

## 📌 Contexto e Objetivos

**Tema escolhido:** Jogos de Baralho — história, regras e estratégias

**Objetivo principal:**  
Utilizar o NotebookLM como ferramenta de aprendizagem ativa para aprender a jogar baralho e dominar os principais jogos de cartas, combinando fontes em vídeo e texto para criar um caderno de estudos estruturado com auxílio de IA Generativa.

**Objetivos específicos:**
- Compreender a história e origem do baralho
- Aprender as regras dos principais jogos de cartas
- Desenvolver estratégias e técnicas para cada jogo
- Criar um glossário com os termos mais importantes
- Produzir prompts reutilizáveis para revisão futura

---

## 📚 Curadoria de Fontes

### 🎥 Fontes em Vídeo (YouTube)
| # | Título / Link |
|---|---------------|
| 1 | [Como jogar baralho](https://www.youtube.com/watch?v=-CvcAKa1-d8) |
| 2 | [Jogos de cartas para iniciantes](https://www.youtube.com/watch?v=5QGIppCGwOk) |
| 3 | [Regras e estratégias](https://www.youtube.com/watch?v=LMuSZhDByEs) |
| 4 | [Técnicas avançadas](https://www.youtube.com/watch?v=jKz77Wx5Azk) |
| 5 | [Jogos clássicos de baralho](https://www.youtube.com/watch?v=zhVZgARkMbA) |
| 6 | [Tutorial completo](https://www.youtube.com/watch?v=hEUkr7sveXM) |
| 7 | [Dicas e truques](https://www.youtube.com/watch?v=6PnlY2ajy6s) |

### 📄 Fontes em Texto
| # | Título / Link |
|---|---------------|
| 1 | [História do Baralho — Elking](https://elking.com.br/blog/historia-do-baralho/) |
| 2 | [Quem inventou o baralho — Blog Copag](https://blog.copag.com.br/dicas/quem-inventou-o-baralho-conheca-a-historia-completa) |
| 3 | [Guia de Baralho — Westwing](https://www.westwing.com.br/guiar/baralho/) |

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Prompts Testados no NotebookLM

**Prompt 1 — Visão Geral**
> "Com base nas fontes fornecidas, me dê um resumo completo sobre a história do baralho e como ele chegou ao Brasil."

*Resultado:* Resposta detalhada com linha do tempo desde a origem na China/Pérsia até a popularização no Brasil. ✅

---

**Prompt 2 — Regras específicas**
> "Quais são as regras básicas do jogo de Truco? Liste passo a passo de forma simples para um iniciante."

*Resultado:* O NotebookLM listou as regras de forma clara com base nas fontes de vídeo. ✅

---

**Prompt 3 — Estratégias**
> "Quais estratégias posso usar para ganhar no Poker? Me dê dicas baseadas nas fontes disponíveis."

*Resultado:* Retornou dicas gerais. Reformulei para ser mais específico 👇

**Prompt 3.1 — Refinado**
> "Com foco nas fontes de vídeo, liste as 5 principais estratégias para iniciantes no Poker Texas Hold'em."

*Resultado:* Resposta muito mais objetiva e útil. ✅ **Lição: quanto mais específico o prompt, melhor a resposta.**

---

**Prompt 4 — Glossário**
> "Crie um glossário com os 15 termos mais importantes usados nos jogos de baralho presentes nas fontes."

*Resultado:* Glossário gerado com termos como blefe, mão, rodada, trunfo, etc. ✅

---

**Prompt 5 — Comparação de jogos**
> "Compare os jogos de Buraco, Truco e Poker em termos de dificuldade, número de jogadores e estratégia necessária."

*Resultado:* Tabela comparativa clara e bem estruturada. ✅

---

### 💡 Aprendizados de Troubleshooting
- Prompts genéricos geram respostas superficiais → **sempre especifique o jogo, o nível e o formato desejado**
- Pedir "liste", "compare" ou "crie uma tabela" melhora muito a organização da resposta
- Referenciar explicitamente "com base nas fontes" faz o NotebookLM citar os materiais corretamente

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📝 Resumos Estruturados

**História do Baralho**
- Origem estimada no século IX na China, espalhando-se pela Pérsia e Europa
- Os 4 naipes (copas, ouros, paus, espadas) surgiram na Europa medieval representando classes sociais
- O baralho moderno de 52 cartas foi padronizado na França no século XV
- Chegou ao Brasil com os colonizadores portugueses

**Estrutura do Baralho**
- 52 cartas divididas em 4 naipes: ♠ Espadas, ♥ Copas, ♦ Ouros, ♣ Paus
- Cada naipe tem 13 cartas: A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K
- Curingas (Jokers) são cartas extras usadas em alguns jogos

**Principais Jogos de Cartas**
| Jogo | Jogadores | Dificuldade | Objetivo |
|------|-----------|-------------|----------|
| Truco | 2–4 | ⭐⭐ | Ganhar rodadas apostando pontos |
| Buraco | 4 | ⭐⭐⭐ | Formar canastras e zerar a mão |
| Poker | 2–10 | ⭐⭐⭐⭐ | Ter a melhor combinação de cartas |
| Blackjack | 2–7 | ⭐⭐ | Chegar a 21 sem ultrapassar |
| Canastra | 4–6 | ⭐⭐⭐ | Formar sequências e grupos |

---

### 📚 Glossário dos Principais Conceitos

| Termo | Definição |
|-------|-----------|
| **Baralho** | Conjunto de 52 cartas divididas em 4 naipes |
| **Naipe** | Cada um dos 4 grupos de cartas (copas, ouros, paus, espadas) |
| **Mão** | Conjunto de cartas que um jogador segura |
| **Rodada** | Cada ciclo de jogo onde todos os jogadores jogam uma carta |
| **Trunfo** | Naipe ou carta que supera os demais em determinado jogo |
| **Blefe** | Estratégia de enganar os adversários sobre a força da sua mão |
| **Canasta** | Sequência ou grupo de 7 cartas no jogo de Buraco/Canastra |
| **Coringa** | Carta especial que pode substituir qualquer outra |
| **Embaralhar** | Misturar as cartas antes de distribuir |
| **Dar as cartas** | Distribuir as cartas aos jogadores |
| **Fold** | Desistir da rodada no Poker |
| **All-in** | Apostar todas as fichas de uma vez no Poker |
| **Pedir** | Solicitar mais uma carta (Blackjack) |
| **Parar** | Ficar com as cartas atuais sem pedir mais |
| **Vaza** | Conjunto de cartas jogadas em uma rodada |

---

### 🔁 Prompts Reutilizáveis para Revisão Futura

```
// Para aprender um jogo novo:
"Explique as regras completas do jogo [NOME DO JOGO] para um iniciante absoluto, em formato de passo a passo numerado."

// Para praticar estratégias:
"Quais são as 5 estratégias mais importantes para vencer no [NOME DO JOGO]? Inclua exemplos práticos."

// Para revisar termos:
"Crie um quiz de 10 perguntas sobre os termos e regras do baralho com base nas fontes estudadas."

// Para comparar jogos:
"Compare [JOGO A] e [JOGO B] em termos de regras, dificuldade e estratégia necessária."

// Para simular situações:
"Descreva uma situação comum no jogo de [NOME DO JOGO] e explique qual seria a melhor decisão estratégica."
```

---

## 🛠️ Tecnologias Utilizadas

- [NotebookLM](https://notebooklm.google.com/) — IA Generativa para criação do caderno temático
- [GitHub](https://github.com/) — Versionamento e entrega do projeto
- [DIO](https://www.dio.me/) — Plataforma do desafio

---

## 👤 Autor

**Caique Lourenço**  
[![GitHub](https://img.shields.io/badge/GitHub-l--cyber777-black?logo=github)](https://github.com/l-cyber777)

---

*Projeto desenvolvido para o Desafio de IA Generativa — DIO* 🚀
