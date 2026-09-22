# 💸 FinPath AI

Aplicativo conceitual de organização de finanças pessoais com Inteligência Artificial, desenvolvido como parte do desafio **App de Organização de Finanças Pessoais com Vibe Coding**, da DIO.

> **Status:** MVP conceitual em desenvolvimento.

## 📌 Sobre o projeto

O **FinPath AI** foi pensado para tornar o controle financeiro pessoal mais simples, principalmente para pessoas que estão começando a administrar o próprio dinheiro.

Em vez de depender de planilhas, formulários extensos ou registros manuais, o usuário pode conversar com o aplicativo em linguagem natural.

Exemplo:

> "Gastei R$ 32 no almoço hoje."

A IA interpreta a mensagem, identifica o valor, a categoria e a data e registra a transação.

Também é possível criar metas de forma natural:

> "Quero juntar R$ 2.000 até janeiro para comprar um computador."

A partir disso, o aplicativo pode calcular uma meta mensal, acompanhar o progresso e oferecer orientações simples com base nos dados cadastrados.

## 🎯 Problema

Muitas pessoas começam a utilizar aplicativos de controle financeiro, mas abandonam o hábito porque precisam registrar manualmente cada gasto, selecionar categorias e interpretar relatórios que nem sempre são intuitivos.

Além disso, apenas mostrar quanto foi gasto não necessariamente ajuda o usuário a entender o que fazer com aquela informação.

## 💡 Solução proposta

O FinPath AI utiliza uma experiência conversacional para:

- registrar receitas e despesas;
- classificar transações automaticamente;
- acompanhar metas financeiras;
- apresentar um resumo simples da situação financeira;
- identificar padrões de gastos;
- oferecer orientações educativas por meio de um Agente Financeiro com IA.

## 👥 Público-alvo

O foco principal são jovens e adultos que estão começando a organizar suas finanças, incluindo:

- estudantes;
- pessoas no primeiro emprego;
- profissionais com renda variável;
- usuários que consideram planilhas e aplicativos financeiros tradicionais complexos ou trabalhosos.

## 🚀 Funcionalidades principais do MVP

### 1. Registro financeiro por conversa

O usuário registra receitas e despesas utilizando linguagem natural.

Exemplo:

> "Recebi R$ 800 do estágio."

A IA identifica o valor, o tipo da transação e uma categoria adequada.

### 2. Classificação automática

As transações podem ser classificadas automaticamente em categorias como:

- alimentação;
- transporte;
- educação;
- lazer;
- moradia;
- compras;
- saúde;
- renda.

O usuário continua podendo corrigir a categoria quando necessário.

### 3. Dashboard financeiro

Uma tela simples apresenta informações como:

- saldo atual;
- receitas do mês;
- despesas do mês;
- principais categorias de gastos;
- evolução dos gastos.

### 4. Metas financeiras

O usuário pode definir objetivos em linguagem natural.

Exemplo:

> "Quero juntar R$ 3.000 em seis meses."

O aplicativo calcula uma meta mensal e apresenta o progresso ao longo do tempo.

### 5. Agente Financeiro com IA

Um agente analisa as informações registradas e apresenta observações educativas e personalizadas.

Exemplo:

> "Seus gastos com alimentação fora de casa aumentaram neste mês. Reduzir parte desse valor pode ajudar você a avançar mais rapidamente em sua meta."

O agente não substitui aconselhamento financeiro profissional e deve evitar apresentar previsões ou recomendações como garantias.

---

# 🧠 Prompt final / PRD

## Contexto

Quero criar o conceito de um aplicativo de organização de finanças pessoais chamado **FinPath AI**.

O aplicativo terá como principal diferencial permitir que o usuário controle sua vida financeira por meio de conversas em linguagem natural, evitando a necessidade de preencher diversos formulários, planilhas ou categorias manualmente.

A proposta é transformar o controle financeiro em uma atividade simples, rápida e acessível, especialmente para pessoas que estão começando a administrar o próprio dinheiro.

## Problema

Muitas pessoas começam a utilizar aplicativos de controle financeiro, mas abandonam o hábito porque precisam registrar manualmente cada gasto, escolher categorias, atualizar valores e interpretar relatórios complexos.

Além disso, saber quanto foi gasto nem sempre ajuda o usuário a entender **o que fazer com aquela informação**.

O FinPath AI pretende resolver esses dois problemas utilizando inteligência artificial para automatizar registros e transformar os dados financeiros em orientações simples e práticas.

## Público-alvo

O público principal são jovens e adultos que estão começando a organizar suas finanças e procuram uma ferramenta fácil de utilizar.

O aplicativo também pode atender estudantes, pessoas no primeiro emprego, profissionais com renda variável ou qualquer usuário que considere planilhas e aplicativos financeiros tradicionais complexos ou trabalhosos.

## Proposta de valor

Permitir que uma pessoa organize suas finanças da mesma maneira que conversaria com alguém.

Em vez de preencher manualmente valor, categoria, descrição, data e tipo da transação, o usuário poderia simplesmente escrever:

> "Gastei R$ 45 no mercado hoje."

A IA interpretaria a mensagem e registraria automaticamente a transação.

## Funcionalidades-chave

1. Registrar receitas e despesas via chat em linguagem natural.
2. Classificar automaticamente as transações.
3. Exibir um dashboard financeiro simples.
4. Criar e acompanhar metas financeiras.
5. Oferecer orientações por meio de um Agente Financeiro com IA.

## Fluxo principal

1. O usuário acessa o aplicativo.
2. Visualiza um resumo financeiro.
3. Abre o chat.
4. Informa uma receita, despesa, dúvida ou meta.
5. A IA interpreta a mensagem.
6. O usuário confirma ou corrige a informação.
7. O sistema atualiza automaticamente o dashboard e as metas.
8. O agente financeiro pode apresentar orientações baseadas nos novos dados.

## Telas do MVP

O MVP deverá possuir:

- Tela inicial / dashboard;
- Chat financeiro;
- Histórico de transações;
- Metas financeiras;
- Área de análise do Agente Financeiro.

## Comportamento do Agente Financeiro

O agente deverá utilizar linguagem simples, amigável e objetiva.

Ele deverá:

- explicar padrões de gastos;
- ajudar na criação de metas;
- identificar gastos recorrentes;
- mostrar possíveis oportunidades de economia;
- explicar conceitos financeiros quando necessário;
- evitar julgamentos sobre as escolhas do usuário.

O objetivo não é substituir um profissional financeiro, mas ajudar o usuário a compreender melhor sua própria situação.

## Validação do MVP

O MVP poderá ser testado inicialmente com um pequeno grupo de usuários.

A validação deverá observar:

- facilidade para registrar uma transação;
- quantidade de registros feitos sem correção;
- compreensão dos relatórios;
- frequência de utilização;
- quantidade de usuários que criam uma meta;
- percepção de utilidade das sugestões da IA.

Também deverá ser perguntado aos usuários se controlar as finanças pelo chat foi mais simples do que utilizar formulários tradicionais.

## Entregável esperado da IA

Com base neste PRD:

1. Desenvolva o conceito visual e funcional do MVP.
2. Defina o fluxo entre as telas.
3. Proponha uma interface simples e moderna.
4. Simule o funcionamento do chat financeiro.
5. Defina como o Agente Financeiro deverá responder.
6. Apresente os recursos necessários para o MVP.
7. Sugira uma estratégia simples de validação com usuários.

Priorize uma experiência intuitiva, acessível para iniciantes e compatível com dispositivos móveis.

Utilize português brasileiro e linguagem simples.

---

## 🔄 Fluxo conceitual do MVP

```text
Dashboard
   ↓
Chat Financeiro
   ↓
Interpretação da IA
   ↓
Confirmação do usuário
   ↓
Registro da transação
   ↓
Atualização do Dashboard
   ↓
Metas e análises
   ↓
Agente Financeiro
```

## 🤖 Exemplo de interação

**Usuário**

> Gastei R$ 28 no almoço hoje.

**FinPath AI**

> Identifiquei uma despesa de R$ 28 em Alimentação para hoje. Deseja confirmar?

**Usuário**

> Sim.

**FinPath AI**

> Registrado. Seus gastos com alimentação neste mês foram atualizados no painel.

---

## 🖼️ Evidências das interações com IA

Esta seção será atualizada com os registros das etapas de criação e refinamento do projeto.

Arquivos planejados:

- `images/01-prd.png` — envio do PRD para a IA;
- `images/02-primeira-versao.png` — primeira proposta do MVP;
- `images/03-refinamento.png` — interação de melhoria;
- `images/04-dashboard.png` — dashboard ou interface criada;
- `images/05-resultado-final.png` — resultado final do conceito.

> As imagens serão adicionadas após as interações com Copilot, Lovable ou outra ferramenta de IA utilizada no desenvolvimento do conceito.

## 🧪 Plano de validação

Para validar a proposta do FinPath AI, o MVP pode ser apresentado a um pequeno grupo de usuários e avaliado por critérios como:

- rapidez para registrar uma despesa;
- precisão da classificação automática;
- facilidade para compreender o dashboard;
- facilidade para criar uma meta;
- utilidade percebida das análises da IA;
- preferência entre registro por conversa e formulários tradicionais.

## 📝 Reflexão sobre o processo

Até esta etapa, o principal aprendizado foi perceber que a qualidade da resposta da IA depende diretamente da qualidade das instruções fornecidas.

Um pedido genérico como "crie um aplicativo financeiro" deixa muitas decisões abertas para a ferramenta. Ao transformar a ideia em um PRD, definindo problema, público-alvo, funcionalidades, comportamento da IA, fluxo e critérios de validação, o resultado esperado fica muito mais claro.

O processo também mostrou que Vibe Coding não significa apenas pedir para uma IA gerar alguma coisa. A parte mais importante está em definir o problema, avaliar o resultado produzido e refinar as instruções até que a solução fique coerente com o objetivo inicial.

Esta reflexão será complementada após as etapas de prototipação e refinamento do MVP.

## 📚 Tecnologias e ferramentas

- Inteligência Artificial generativa;
- Copilot e/ou Lovable;
- GitHub;
- conceitos de Vibe Coding;
- conceitos de MVP;
- elaboração de PRD.

## ✅ Checklist do desafio

- [x] Fork do repositório-base;
- [x] Definição do conceito do aplicativo;
- [x] Criação do PRD;
- [x] Definição das funcionalidades principais;
- [x] Definição do fluxo conceitual;
- [ ] Executar o PRD em uma ferramenta de IA;
- [ ] Refinar o MVP por meio de novas interações;
- [ ] Adicionar prints ou vídeos das interações;
- [ ] Complementar a reflexão final;
- [ ] Revisar o README;
- [ ] Entregar o link do repositório na plataforma da DIO.

---

## 🎓 Desafio DIO

Projeto desenvolvido para o desafio **App de Organização de Finanças Pessoais com Vibe Coding**, com foco na criação de um conceito de produto utilizando IA como parceira no processo de ideação, especificação e refinamento.
