# Caderno Temático de Inteligência Artificial

Projeto do desafio da DIO feito com o NotebookLM.

---

## Por que escolhi esse tema

A Inteligência Artificial já virou parte do cotidiano. Aparece no feed, nas recomendações de música, em exames médicos e até na hora de pesquisar qualquer coisa. Mesmo assim, ainda é um assunto cheio de exagero e confusão.

Eu quis montar algo mais sólido. Queria entender os conceitos de verdade, conseguir separar bem Machine Learning, Deep Learning e IA Generativa, e ver na prática como essas coisas funcionam.

Também aproveitei para treinar uma habilidade que acho importante: fazer perguntas melhores para a IA. Porque ter a ferramenta não adianta muito se a gente não sabe usá-la direito.

Tudo foi construído no NotebookLM com fontes que selecionei, vários testes de prompt e bastante curadoria do que a ferramenta gerava.

---

## Fontes que usei

Escolhi quatro materiais abertos e subi no NotebookLM:

1. **“A Nova Eletricidade”: Aplicações, Riscos e Tendências da IA Moderna**  
   Texto em português, bem direto.  
   [PDF](https://arxiv.org/pdf/2310.18324.pdf)

2. **Gathering Strength, Gathering Storms – Relatório AI100 2021 (Stanford)**  
   Uma visão mais séria sobre o estado da IA e seus impactos.  
   [PDF](https://arxiv.org/pdf/2210.15767.pdf)

3. **Intelligence Primer: Natural and Artificial**  
   Boa para entender o que realmente significa inteligência.  
   [PDF](https://arxiv.org/pdf/2008.07324.pdf)

4. **Panorama da História da Inteligência Artificial**  
   Serve para ter uma noção da linha do tempo da área.  
   [Link](https://www.redalyc.org/journal/3844/384481416024/)

---

## Como trabalhei os prompts (e o que deu errado)

Essa foi a parte que mais me engajou.

Comecei com perguntas bem simples e fui melhorando conforme via o resultado:

**Primeira tentativa:**  
“Explique a diferença entre Machine Learning e Deep Learning.”

A resposta saiu genérica e meio confusa.

**Segunda tentativa:**  
“Explique a diferença entre Machine Learning e Deep Learning usando uma analogia do dia a dia e uma tabela simples.”

Melhorou um pouco, mas ainda faltava organização.

**Terceira versão:**  
“Aja como um professor paciente. Explique a diferença entre Machine Learning, Deep Learning e IA Generativa para um iniciante. Use analogias do cotidiano e finalize com uma tabela clara.”

Essa já entregou algo bem mais útil.

### O que aprendi no caminho

Quando a pergunta ficava aberta demais, a IA misturava os conceitos. Passei a pedir para tratar cada um separadamente.

As respostas também tendiam a ficar genéricas. Forçar analogias e exemplos concretos ajudou bastante.

Em alguns momentos ela inventava informação ou não mostrava de onde tinha tirado. Comecei a pedir sempre para se basear só nos documentos que eu tinha carregado e citar a fonte.

A principal lição: o jeito de perguntar pesa quase tanto quanto a qualidade da fonte. Pequenas mudanças no prompt mudam bastante o resultado.

---

## Miniguia de estudo

### Resumo dos conceitos principais

**O que é Inteligência Artificial?**  
De forma bem direta: é quando sistemas conseguem fazer coisas que normalmente a gente associa à inteligência humana, tipo reconhecer padrões, tomar decisões ou criar conteúdo.

**Principais ramos**

- **IA Fraca (Narrow AI):** resolve uma tarefa específica muito bem (recomendar filmes, reconhecer voz).
- **Machine Learning:** sistemas que aprendem olhando dados.
- **Deep Learning:** usa redes neurais com várias camadas para enxergar padrões mais complexos.
- **IA Generativa:** consegue criar coisas novas (texto, imagem, código, áudio).

**Formas de aprendizado**
- Supervisionado → usa dados que já vêm rotulados
- Não supervisionado → tenta encontrar padrões sozinho
- Por reforço → aprende tentando e recebendo feedback

**Onde a IA já aparece**
Assistentes virtuais, apoio em diagnósticos, recomendações, carros autônomos, detecção de fraude e geração de conteúdo.

**Limitações que valem prestar atenção**
Ela ainda inventa informação (alucinação), pode carregar viés dos dados, gasta bastante energia, muitas vezes não explica o porquê das respostas e levanta várias questões éticas.

### Glossário rápido

| Conceito              | Explicação simples |
|-----------------------|--------------------|
| Machine Learning      | Máquinas que aprendem com dados |
| Deep Learning         | Machine Learning usando redes neurais profundas |
| Rede Neural           | Modelo inspirado no jeito que o cérebro funciona |
| IA Generativa         | IA que cria conteúdo novo |
| Prompt                | A instrução que você manda para a IA |
| Engenharia de Prompt  | A prática de escrever boas instruções |
| Alucinação            | Quando a IA inventa informação |
| LLM                   | Modelo de linguagem grande (tipo os que geram texto) |
| Fine-tuning           | Ajuste fino de um modelo que já foi treinado |
| Token                 | Pedacinho de texto que o modelo processa |

### Prompts para revisar depois

Guardei estes para voltar no tema quando precisar:

1. “Faça um resumo claro e estruturado dos conceitos fundamentais de Inteligência Artificial.”
2. “Explique a diferença entre Machine Learning, Deep Learning e IA Generativa usando analogias do cotidiano.”
3. “Monte uma tabela comparativa simples entre os principais tipos de aprendizado de máquina.”
4. “Liste os oito conceitos mais importantes de IA para iniciantes, com definições curtas.”
5. “Quais são os principais riscos e limitações da Inteligência Artificial atualmente?”
6. “Explique o que é uma rede neural de forma simples e visual, sem termos técnicos demais.”
7. “Crie cinco perguntas de revisão de nível intermediário sobre Inteligência Artificial.”
8. “Faça um mapa mental em texto dos principais ramos da Inteligência Artificial.”
