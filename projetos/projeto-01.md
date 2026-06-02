# Projeto 01 - Web App Multimídia & Comunidade (Figma)

Projeto voltado para a aplicação prática de **Design de Interfaces (UI)**, **Usabilidade (UX)** e **Prototipagem Interativa Avançada no Figma**, focando na simulação de reprodução de mídias, arquitetura de informação e fluxos de estados de componentes.

Neste projeto, o objetivo principal é desenhar a experiência de um Website tematizado de comunidade, onde a usabilidade dita como o usuário consome mídias e gerencia seu próprio perfil. Este projeto pode ser implementado nos designs anteriores.

---

## Ponto Crucial: Usabilidade, Affordance e Arquitetura

Diferente de um projeto focado em programação, **neste trabalho o foco total é a experiência do usuário antes do código**. Vocês precisarão garantir que a interface aplique os conceitos de:
* **Affordance:** Deixar claro a função do que foi criado e o que é clicável (botões de play, inputs, abas).
* **Contraste:** Garantir a legibilidade textual completa.
* **Lei da Proximidade:** Agrupamento lógico de posts, ações e blocos de comentários.
* **Consistência Visual:** Manter padrões estéticos e funcionais por todo o ecossistema do app.

---

## Estrutura Mínima (Páginas Obrigatórias)

O protótipo no Figma deve conter, no mínimo, as seguintes telas/fluxos integrados:

1.  **Página de Feed/Posts:** Onde o usuário visualiza as publicações e consome os conteúdos do tema escolhido. Deve conter áreas explícitas para players de mídia (imagem, áudio ou vídeo).
2.  **Página do Post + Comentários:** Uma visão detalhada de um post específico onde a seção de comentários da comunidade é exibida de forma organizada abaixo do conteúdo.
3.  **Página de Perfil do Usuário:** Área que exibe os dados do usuário logado e possui o mecanismo interativo para alteração de sua foto de perfil.

---

## Níveis de Entrega

O projeto está dividido em dois níveis de complexidade. A nota final dependerá de do nível do estudante e até onde o grupo escolheu avançar no refinamento das interações.

### Nível 1 (N1) - O Essencial da Interface (Nota Máxima: 10.0 / 7.0 para N2)
*Foco na estrutura estática de alta fidelidade e fluxos básicos de navegação.*

* **Telas Estruturadas:** Criação das 3 telas obrigatórias em alta fidelidade utilizando um Grid de alinhamento padronizado ou o modo de exibição flex direcional.
* **Representação Visual de Mídias:** Uso de elementos gráficos nativos de UI (ícones de play/pause, barras de progresso simuladas e timers) que deixem claro se a mídia proposta é um vídeo, áudio ou imagem.
* **Navegação entre Telas:** Fluxo básico de ligações no modo de prototipagem do Figma (clicar em um card do feed leva para os comentários; clicar no menu leva para o perfil).
* **Troca de Foto de Perfil (Fluxo Base):** O botão "Alterar Foto" deve levar o usuário para uma tela duplicada onde a foto final já apareça modificada.

### Nível 2 (N2) - Componentização e Microinterações (Nota Máxima: 10.0)
*Foco em transformar o protótipo em uma simulação idêntica a um sistema real e funcional.*

* **Interactive Components (Estados de Botões):** Criação obrigatória de componentes com variantes para simular feedback dinâmico. Botões de ação, inputs de texto e abas de menu devem ter, no mínimo, os estados: *Default*, *Hover* (passar o mouse) e *Pressed* (clicado).
* **Fluxo de Foto via Overlays:** O botão "Alterar Foto" deve abrir um *Overlay* (modal flutuante) simulando a janela de arquivos do celular/computador. Ao escolher a nova imagem, o perfil deve atualizar a foto dinamicamente usando a transição *Smart Animate*.
* **UX de Estado Vazio (Empty State):** Criação de uma variante para a lista de comentários simulando a tela quando não há interações (ex: exibição de um ícone discreto e o texto descritivo *"Seja o primeiro a comentar nesta publicação!"*).
* **UI Kit / Guia de Estilos:** Criação de uma página dedicada no arquivo do Figma documentando a identidade visual do projeto: Paleta de Cores Semânticas (Primária, Secundária, Sucesso, Erro), Estilos de Tipografia e os componentes reutilizados.

---

## Sugestão de Temas

Os grupos estão livres para escolher o nicho do projeto. Abaixo estão algumas sugestões focadas em multimídia:

| Tema | Foco do Feed | Foco do Perfil |
| :--- | :--- | :--- |
| **Streaming Musical (Spotify-Demo)** | Playlists e podcasts com foco em cards de áudio. | Página do ouvinte com gêneros favoritos. |
| **Mini-Tutoriais (YouTube-Demo)** | Grade de vídeos com foco em thumbnails e tempos de duração. | Página do canal com estatísticas do criador. |
| **Rede Social (Twitter-Demo)** | Página principal com foco em posts imagens e vídeos. | Página de perfil com biografia e postagens pessoais. |
| **Blog de Culinária Integrado** | Posts contendo vídeos rápidos de receitas ou carrosséis de fotos do preparo. | Página do Chef destacando suas receitas salvas. |

---

## Critérios de Avaliação

* **Protótipo Interativo e Fluxos (3.0 pts):** Navegação funcional entre telas, uso de Overlays e animações condizentes com a experiência web.
* **Hierarquia Visual e UX (3.0 pts):** Aplicação de pesos tipográficos, espaçamentos lógicos (Lei da Proximidade), contraste e clareza na diferenciação das mídias.
* **Tratamento de Estados (2.0 pts):** Presença de botões interativos (Hover/Pressed) e respostas visuais a ações como estados vazios (Requisito N2).
* **Organização do Figma (2.0 pts):** Uso de frames organizados, nomenclatura limpa das camadas (*layers*) e entrega da página de Guia de Estilos.

---

## Janela de Entrega e Apresentação

* **Prazo Final:** Até quinta-feira, 11/06.
* **Formato de Apresentação:** O grupo deverá rodar o modo de exibição (*Play*) do Figma ao vivo, demonstrando o fluxo de navegação completo, a interação com os players de mídia simulados e o funcionamento do fluxo de alteração da foto de perfil.

---

## Instruções de Entrega

1. O link do arquivo do Figma deve ser compartilhado para o email `samuel.santos@prof.ce.gov.br` com a permissão configurada para **"Can view" (Pode visualizar)**.
2. Na primeira página do arquivo do Figma, deve haver uma capa contendo:
   * Nome do Tema Escolhido;
   * Nome Completo dos Integrantes do Grupo;
   * Indicação clara se os desafios de nível **N2** foram implementados.

---

## Configuração Inicial do Ambiente no Figma

Para garantir a padronização e consistência na hora da correção, todos os grupos devem seguir os passos abaixo:

1. Acesse o Figma e crie um novo **Design File**.
2. No menu de páginas esquerdo, crie duas abas: `📱 Protótipo` e `🎨 Guia de Estilos`.
3. Na página de protótipo, pressione a tecla `F` para criar um Frame. No painel direito, selecione o tamanho padrão **Desktop > Desktop (1440x1024)** ou **MacBook Pro 14"**.
4. Com o Frame selecionado, ative a **Layout Grid** no painel lateral direito e configure para **Columns**:
   * **Count:** 12
   * **Type:** Center
   * **Width:** 80
   * **Gutter:** 24  
   *(Esse grid de 12 colunas garantirá o alinhamento perfeito de cards, listas e menus de forma profissional, mas você pode muito bem utilizar o layout vertical e horizontal como bem entender).*

---

# Lista de estudantes com seus respectivos níveis

## Nível 1
- ANA DAVILA DA SILVA SIQUEIRA
- ANA DELLY
- ANGELA KYARA MOREIRA FERREIRA
- CARLOS RENAN PEREIRA BARROS
- EDIGAR CHAVES DE ALMEIDA
- FRANCISCO BRUNO LOPES DO NASCIMENTO
- FRANCISCO ENZO LOPES FELIX
- FRANCISCO TAISLAN MORAIS DE ALMEIDA
- ISABELLE LOPES DO NASCIMENTO
- JOAO VICTOR SOUSA SILVA
- LUCIVANIA BEZERRA DE SOUSA
- LUIS FERNANDO BRAGA DOS SANTOS
- MARIA LARISSA RAMOS DE SOUSA
- REBEKA MARIA BRITO DE SOUSA
- SAMUEL RIBEIRO SOUZA
- STEFANY ALVES RIBEIRO

## Nível 2
- ANDRE RYAN ARAUJO SOARES
- ARISTIDES ALVES DOS SANTOS NETO
- CAIO VICTOR BARROS UCHOA
- DAVYSON LEVI DOS SANTOS CORDEIRO
- ERYCK FERNANDO DE OLIVEIRA BARBOSA
- JOAO EMANOEL ALVES DA SILVA
- JOAO MATEUS CARNEIRO DE SOUSA
- JOAO PAULO CARDOSO DE ABREU FILHO
- JOSE HENRIQUE LIMA DUARTE
- KAUA GOMES BEZERRA
- KEIRRYSON RAFFAEL LIMA SOARES
- LUIS GUILHERME BRITO GOMES
- MARIO PIETRO RODRIGUES MACIEL
- PEDRO HENRIQUE INACIO DE CASTRO
- PEDRO JUAN DO NASCIMENTO RODRIGUES
- THAIRES SOUSA RODRIGUES
- WANESSA PEREIRA DA SILVA
