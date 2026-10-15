# Galeria Presidencial — Projeto VR

## Objetivo

A **Galeria Presidencial** é uma aplicação educacional de realidade virtual executada pelo navegador, desenvolvida com **A-Frame**, para apresentar aspectos da história política brasileira por meio de uma experiência interativa em uma galeria tridimensional.

O projeto faz parte de um trabalho acadêmico. A proposta é permitir que visitantes explorem um espaço virtual, consultem painéis históricos sobre presidentes selecionados e respondam a um pequeno quiz de revisão.

## Escopo inicial

A primeira versão prevê:

- Uma sala tridimensional que funciona como galeria virtual.
- Cinco painéis históricos sobre:
  - Deodoro da Fonseca;
  - Getúlio Vargas;
  - Juscelino Kubitschek;
  - Castello Branco;
  - José Sarney.
- Interação com os painéis para consultar retrato, período de governo, resumo histórico e fontes.
- Um quiz de três perguntas, com feedback, pontuação de 0 a 3 e opção de refazer.
- Navegação e testes em computador; a experiência imersiva será validada conforme a disponibilidade de dispositivo e suporte a WebXR.

O escopo inicial **não prevê backend**. Priorize uma aplicação web simples, com conteúdo e recursos organizados no próprio projeto.

## Tecnologias

- **A-Frame** — construção da cena e dos elementos 3D.
- **HTML, CSS e JavaScript** — estrutura, apresentação e lógica de interação.
- **WebXR** — entrada em modo imersivo em dispositivos e navegadores compatíveis.
- **Git e GitHub** — versionamento e colaboração.
- **Trello** — acompanhamento das tarefas.

Bibliotecas adicionais, incluindo integração com outras tecnologias de realidade aumentada, não devem ser consideradas obrigatórias. Só as proponha quando houver uma necessidade concreta alinhada ao escopo VR.

## Estado do projeto

O repositório está sendo preparado para o desenvolvimento. Consulte os arquivos e commits existentes antes de afirmar que alguma funcionalidade está implementada. Não presuma que a cena, os painéis, o quiz ou o modo imersivo já estejam prontos.

## Princípios do projeto

- Manter a experiência focada em realidade virtual e na visita à galeria.
- Preservar o escopo da primeira versão; registrar expansões como propostas, sem incorporá-las automaticamente.
- Priorizar legibilidade, navegação compreensível, desempenho e compatibilidade.
- Usar informações históricas verificáveis e registrar as fontes.
- Conferir autoria, origem e condições de uso de imagens, modelos 3D, áudio e demais recursos externos.
- Manter o projeto simples enquanto os requisitos não justificarem complexidade adicional.

## Documentação para agentes de IA

Antes de propor ou realizar alterações de código, leia [AGENTS.md](AGENTS.md), que reúne o contexto do projeto e as orientações para assistentes de programação.

## Como executar

A estrutura executável ainda precisa ser confirmada durante a configuração inicial. Como o projeto usa A-Frame no navegador, a execução local deverá usar um servidor HTTP local quando os arquivos e recursos estiverem preparados. As instruções exatas serão adicionadas assim que a estrutura de desenvolvimento for definida.

## Contexto acadêmico

O projeto será desenvolvido incrementalmente ao longo do semestre, com protótipos, testes, documentação e apresentações de fase. O Trello é a referência para o estado das tarefas e dos prazos.
