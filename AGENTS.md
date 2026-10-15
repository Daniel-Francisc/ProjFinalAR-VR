# Contexto do projeto para agentes de IA

Leia este arquivo antes de sugerir ou alterar código neste repositório. Ele serve como contexto compartilhado para assistentes de programação e deve ser atualizado quando decisões importantes do projeto mudarem.

## 1. Identidade e objetivo

Este repositório pertence ao projeto acadêmico **Galeria Presidencial**, uma aplicação educacional de **realidade virtual (VR)** feita com **A-Frame** e acessível pelo navegador. A experiência deve permitir que visitantes explorem uma galeria tridimensional e aprendam sobre períodos da história política brasileira.

Não confunda o escopo atual com uma aplicação de realidade aumentada. O objetivo atual é VR com A-Frame. WebXR é relevante para o modo imersivo, dependendo do suporte do navegador e do dispositivo.

## 2. Escopo inicial aprovado

A primeira versão contempla:

- Uma sala 3D.
- Cinco painéis sobre Deodoro da Fonseca, Getúlio Vargas, Juscelino Kubitschek, Castello Branco e José Sarney.
- Conteúdo histórico resumido, período de governo, retrato e fontes associadas aos painéis.
- Um quiz de três perguntas, com feedback, pontuação de 0 a 3 e opção de refazer.
- Navegação em desktop para desenvolver e testar; modo imersivo a validar conforme a disponibilidade de hardware e compatibilidade com WebXR.
- Aplicação web sem backend no escopo inicial.

Não adicione novas salas, sistemas de conta, banco de dados, serviços externos ou funcionalidades grandes sem explicar a necessidade e obter confirmação.

## 3. Stack técnica

- A-Frame para cena, entidades e componentes 3D.
- HTML, CSS e JavaScript.
- WebXR para suporte de realidade virtual imersiva.
- Git/GitHub para versionamento e colaboração.

Não assuma que AR.js é necessário: a direção atual é uma aplicação VR em A-Frame. Não adicione frameworks ou bibliotecas por hábito. Primeiro explique qual problema concreto resolvem e quais custos trazem.

## 4. Estado e evidências

O repositório está em fase de preparação. Inspecione os arquivos reais e o histórico antes de dizer que uma funcionalidade, dependência ou configuração existe. Não invente caminhos, comandos de execução, scripts, estruturas de pastas ou funcionalidades que não foram confirmados.

Se a implementação ainda não existir, apresente a proposta como uma sugestão, não como descrição do código atual. Atualize a documentação para refletir mudanças efetivamente realizadas.

## 5. Orientações para trabalhar neste repositório

1. **Explique antes de alterar:** descreva o objetivo da mudança, a razão técnica e o comportamento esperado para o usuário antes de fazer uma alteração relevante.
2. **Não trabalhe no escuro:** ao propor código, explique onde ele se encaixa e como será testado.
3. **Inspecione antes de editar:** leia os arquivos relacionados e preserve o estilo e a estrutura existentes quando fizer sentido.
4. **Mudanças pequenas e rastreáveis:** evite reescritas abrangentes quando uma alteração localizada resolve o problema.
5. **Não invente resultados:** diferencie o que foi implementado, o que foi testado e o que ainda precisa ser validado.
6. **Não sobrescreva trabalho alheio:** verifique o estado da branch e mudanças existentes antes de sugerir operações destrutivas, reset, rebase ou substituição de arquivos.
7. **Evite dependências desnecessárias:** explique alternativas e impactos antes de introduzir bibliotecas.
8. **Mantenha a documentação coerente:** quando mudar a forma de executar, a estrutura ou as decisões técnicas, atualize os documentos correspondentes.
9. **História e direitos de uso:** não invente fatos históricos nem referências. Para textos e mídias, registre fontes e condições de uso e sinalize informações que precisem de verificação.
10. **Acessibilidade e experiência:** considere legibilidade, navegação intuitiva, interação por mouse/teclado no desktop e controles adequados para VR.

## 6. Critérios de qualidade para a experiência

- O visitante deve entender como entrar na galeria e interagir com os painéis.
- Os textos devem ser curtos e legíveis no espaço 3D.
- As interações devem ser consistentes e ter feedback compreensível.
- A experiência precisa oferecer um caminho de teste em desktop, mesmo quando não houver headset.
- Recursos 3D, imagens e áudio devem ser otimizados para não prejudicar o carregamento e a fluidez.
- O quiz deve permitir compreender a resposta e refazer a atividade conforme o escopo definido.

## 7. Fluxo de trabalho esperado

Antes de uma tarefa:
- Consulte o README e os arquivos pertinentes.
- Confirme os requisitos da tarefa e identifique dependências.
- Explique a abordagem e os arquivos que provavelmente serão afetados.

Depois de uma tarefa:
- Resuma as alterações realizadas e a razão de cada uma.
- Informe quais testes foram executados e seus resultados.
- Registre claramente limitações, pendências e passos manuais.

Não marque uma tarefa como concluída apenas porque o código foi escrito; considere os testes necessários.

## 8. Decisões ainda a confirmar

Não invente decisões para os pontos abaixo; proponha opções quando forem necessários:

- Estrutura final de arquivos e estratégia de carregamento.
- Navegadores e dispositivos-alvo para validação WebXR.
- Formato definitivo dos dados dos painéis e do quiz.
- Origem, licenças e créditos das imagens e dos demais recursos.
- Ferramenta e comando exatos para executar o projeto localmente.

## 9. Fonte de verdade

Use este arquivo para o contexto geral do projeto e o README para a apresentação pública e instruções gerais. Para prioridades, responsáveis e prazos acadêmicos, consulte o quadro Trello do projeto. Se houver conflito entre documentação e código existente, não escolha silenciosamente: aponte a divergência e peça confirmação ou proponha uma atualização explícita.
