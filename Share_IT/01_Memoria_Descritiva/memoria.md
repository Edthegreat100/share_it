# Memória Descritiva – Share IT

> Versão da 1.ª entrega (02.10.2026). As secções 5 e 6 serão preenchidas na 3.ª entrega. 

## 1. Identificação

- **Nome do projeto:** Share IT – aplicação móvel de arrendamento de dispositivos eletrónicos
- **Ano letivo:** 2026-2027
- **Semestre:** 3.º
- **Unidades curriculares:** Projeto Mobile; Programação de Dispositivos Móveis; Bases de Dados; Interfaces e Usabilidade; Redes e Comunicação de Dados; Matemática Discreta
- **Docentes:** Fabio Guilherme; João Monge; Miguel Boavida; Paula Neves; Nathan Campos; Pedro Rosa; André Torcato; Ricardo Sousa

## 2. Resumo

Share IT é uma aplicação móvel, desenvolvida em Flutter, que permite alugar por poucos dias aparelhos eletrónicos pertencentes a outros utilizadores, como consolas, televisões, iPads, câmaras, projetores e colunas. A ideia é simples: quem tem um aparelho parado em casa pode ganhar algum dinheiro com ele, e quem precisa de um aparelho apenas durante um fim de semana paga só pelos dias que utiliza, sem ter de o comprar.

O problema que o projeto aborda é duplo. Por um lado, comprar um aparelho caro para o usar poucas vezes não compensa. Por outro, muitos aparelhos passam semanas parados. Hoje estes empréstimos fazem-se em grupos de redes sociais ou em sites de anúncios gerais, onde não existe calendário de datas livres, não há garantia de devolução, não fica registado o estado do aparelho e as pessoas não se conhecem.

A solução reúne tudo num só sítio. O proprietário publica um anúncio com fotografias, preço por dia, datas livres e um local de levantamento aproximado. O arrendatário procura aparelhos perto de si num mapa, filtra por categoria ou distância, escolhe as datas num calendário e faz o pedido de reserva, que o proprietário aceita ou recusa. A entrega e a devolução são confirmadas com QR Code, validado pelo servidor, e o estado do aparelho fica escrito em cada momento. Como extras, caso haja tempo, prevê-se pagamento simulado com caução, avaliações e notificações.

Tecnicamente, o sistema tem três camadas: uma aplicação Flutter/Dart, um servidor Node.js com API REST e uma base de dados relacional MySQL, seguindo o padrão MVC na aplicação e no servidor. A aplicação usa funcionalidades próprias do telemóvel, nomeadamente localização, mapas e câmara. Na vertente de Matemática Discreta, o método de Monte Carlo e a estatística simples (média, mediana e desvio padrão) sugerem um preço por dia com base nos preços de aparelhos da mesma categoria.

O projeto cumpre o RGPD, recolhendo apenas os dados necessários, guardando as palavras-passe só como hash e usando exclusivamente dados fictícios durante o desenvolvimento. Tem também uma motivação de sustentabilidade: se cada aparelho for usado por mais pessoas, são precisos menos aparelhos novos e produz-se menos lixo eletrónico.

## 3. Contexto

### 3.1 Problema abordado

Comprar um aparelho eletrónico caro para o usar poucas vezes (uma televisão para uma festa, um iPad para uma viagem, uma consola para experimentar um jogo) não compensa. Ao mesmo tempo, muitos aparelhos passam semanas parados. Os empréstimos entre pessoas fazem-se hoje em grupos de redes sociais ou em sites de anúncios gerais, sem calendário de datas livres, sem garantia de devolução, sem registo do estado do aparelho e sem confiança entre as pessoas.

### 3.2 Motivação

- Comprar menos aparelhos novos e aproveitar mais os que já existem (economia circular). Em 2022 o mundo produziu 62 milhões de toneladas de lixo eletrónico, mais 82% do que em 2010, e só cerca de 22% foi reciclado de forma oficial (ITU e UNITAR, 2024).
- Permitir que estudantes e jovens usem tecnologia cara sem a ter de comprar.
- Desenvolver um projeto que use o que o telemóvel tem de especial (localização, câmara, mapas), como pede o briefing.

### 3.3 Objetivos

- Criar uma app em Flutter/Dart, organizada em MVC, ligada a um servidor Node.js (API REST) e a uma base de dados MySQL.
- Permitir publicar, procurar, reservar, levantar e devolver aparelhos.
- Criar confiança entre utilizadores com QR Code e, se houver tempo, caução simulada e avaliações.
- Cumprir o RGPD e usar apenas dados inventados durante o desenvolvimento.
- Aplicar Matemática Discreta (Monte Carlo e estatística) numa funcionalidade da app.
- Trabalhar em equipa, por etapas curtas, com GitHub, GitHub Projects e Figma.

## 4. Processo

### 4.1 Metodologia

Metodologia ágil, com entregas pequenas e frequentes todas as semanas, três milestones (E1: 02.10.2026; E2: 06.11.2026; E3: 11.12.2026) e apresentação na semana seguinte a cada entrega. Faz-se primeiro o essencial e só depois os extras. As tarefas são registadas no GitHub Projects com responsável e estado.

### 4.2 Ferramentas

GitHub (versões e documentação), GitHub Projects (gestão do projeto), Figma (mockups), Android Studio ou Visual Studio Code (desenvolvimento).

### 4.3 Tecnologias

| Camada | Tecnologia |
|---|---|
| Aplicação móvel | Flutter e Dart; plugins para mapas, câmara, leitura de QR Code e notificações |
| Servidor | Node.js, API REST, MVC, login seguro |
| Base de dados | MySQL |
| Gestão e design | Git/GitHub, GitHub Projects, Figma |

### 4.4 Estrutura da equipa

Grupo g07.

| Área | Responsável | Apoio |
|---|---|---|
| Gestão e documentação (GitHub Projects, relatórios, apresentações) | Bernardo Bravo | Denzel Antunes |
| Design e usabilidade (Figma, personas, testes) | Denzel Antunes | Guilherme Rodrigues |
| Base de dados (modelo ER, SQL) | Guilherme Rodrigues | Augusto Mendes |
| Backend/API (Node.js, documentação REST) | Bernardo Bravo | Guilherme Rodrigues |
| App móvel: estrutura, login, reservas e QR Code | Augusto Mendes | Bernardo Bravo |
| App móvel: mapa, pesquisa e ecrã de publicar aparelho | Denzel Antunes | Augusto Mendes |
| Matemática Discreta (Monte Carlo, estatística) | Guilherme Rodrigues | Denzel Antunes |

## 5. Resultados

*A preencher na 3.ª entrega.*

### 5.1 Descrição da solução desenvolvida



### 5.2 Funcionalidades principais



### 5.3 Contributos relevantes



## 6. Reflexão

*A preencher na 3.ª entrega.*

### 6.1 Lições aprendidas



### 6.2 Limitações

### 6.3 Trabalho futuro
