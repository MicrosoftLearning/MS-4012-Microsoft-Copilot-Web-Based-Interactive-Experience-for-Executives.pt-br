---
title: Instruções online hospedadas
permalink: index.html
layout: home
---

# Diretório de conteúdo

As demonstrações deste curso são baseadas nas demonstrações do kit acelerador [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

É importante que você se familiarize com as demonstrações antes de ministrar este treinamento. Para vários laboratórios, você utilizará documentos de exemplo e reuniões e emails pré-criados do Teams.

- Faça o pré-download de todos os documentos de amostra [aqui](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Configure reuniões do Teams e threads de email seguindo as instruções [aqui](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarize-se com a experiência interativa encontrada [aqui](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf).

    > **OBSERVAÇÃO:** o arquivo PDF da Experiência Interativa será baixado diretamente para o dispositivo (pasta de downloads).

- Revise o conjunto de treinamento mais atual [aqui](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx).

## Descrição do curso

Explore o potencial transformador do Microsoft Copilot e seu impacto na eficiência organizacional. Projetada para executivos e líderes de negócios sem uma licença do Copilot, essa experiência se aprofunda na arte de criar prompts eficazes, oferece uma experiência interativa e demonstra como o Microsoft Copilot para Microsoft 365 pode se integrar perfeitamente aos fluxos de trabalho diários de negócios para aumentar a produtividade e a inovação.

Os principais objetivos para esta entrega são:

- Ensine como criar prompts eficazes
- Demonstre o Microsoft Copilot (escopo da Web) e oriente os participantes por meio de uma experiência interativa
- Demonstrar o Microsoft Copilot para Microsoft 365 – Microsoft Copilot (escopo de trabalho), Word, Outlook e Teams
- Convide os participantes a baixar e experimentar o Microsoft Copilot para dispositivos móveis

## Duração do curso (não finalizado) 

| # | Tópico                                 | Detalhes                                                                                          | Tempo Total      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Crie prompts eficazes no Copilot para Microsoft 365 | – Arte do slide de prompt <br> – Slide de construção rápida <br> – Slide de laboratório do Copilot | 5 a 10 minutos    |
| 2 | Microsoft Copilot na Web          | – Demonstração do Microsoft Copilot (modo web) <br> – Experiência interativa  <br> – Slide Compartilhar sua experiência | 35 minutos      |
| 3 | Copilot para Microsoft 365 no trabalho     | – Slide do Microsoft Graph <br> – Demonstração do Copilot no Word, Microsoft Copilot (modo de trabalho), Copilot no Outlook e Copilot no Teams <br> – Slide de depoimento <br> – Slide do Microsoft Copilot em dispositivos móveis | 25 minutos      |
|   |                                       |                                                                                                  | **O tempo total pode chegar a 70 minutos** |


Hiperlinks para cada uma das demonstrações estão listados abaixo.

## Demonstrações

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demonstração |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
