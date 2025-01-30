---
layout: default
title: Guia Interativo da Lei do MROSC
---

<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include header.html %}

{% include navigation.html %}

<main id="conteudo-principal" markdown="1">

Bem-vindo ao Guia Interativo da Lei do Marco Regulatório das Organizações da Sociedade Civil (MROSC)!

Este guia foi desenvolvido para auxiliar gestores públicos, representantes de organizações da sociedade civil e demais interessados a compreender e aplicar a Lei 13.019/2014, conhecida como Lei do MROSC.

## O que é o MROSC?

O Marco Regulatório das Organizações da Sociedade Civil (MROSC) é uma agenda política ampla que tem como objetivo aperfeiçoar o ambiente jurídico e institucional relacionado às organizações da sociedade civil e suas relações de parceria com o Estado.

## Sobre este guia

Este guia interativo aborda as principais etapas e aspectos da Lei do MROSC. Navegue pelo menu acima para explorar cada etapa do processo e aprofundar seus conhecimentos sobre a Lei do MROSC.

Além disso, oferecemos uma seção de [Perguntas Frequentes (FAQ)](faq) para esclarecer dúvidas comuns sobre a lei e sua aplicação.

## Fluxograma do Processo MROSC

<div class="mermaid">
graph TD
    A[Início] --> B[Planejamento]
    B -->|Art. 22| C{Há demanda da<br>administração pública?}
    C -->|Sim| D[Termo de Colaboração]
    C -->|Não| E[Termo de Fomento]
    D --> F[Chamamento Público]
    E --> F
    F -->|Art. 24-28, 30 dias mín.| G[Seleção da OSC]
    G -->|Art. 33-34| H[Celebração da Parceria]
    H -->|Art. 42-45| I[Liberação de Recursos]
    I --> J[Execução do Projeto]
    J -->|Art. 58-60| K[Monitoramento e Avaliação]
    K --> L{Necessidade de<br>alteração?}
    L -->|Sim, Art. 57| M[Termo Aditivo]
    M --> J
    L -->|Não| N[Continuação da Execução]
    N --> O[Prestação de Contas]
    O -->|Art. 63-72| P{Contas aprovadas?}
    P -->|Sim| Q[Encerramento da Parceria]
    P -->|Não| R[Providências Corretivas]
    R --> S{Irregularidades<br>sanadas?}
    S -->|Sim| Q
    S -->|Não, Art. 73| T[Sanções e<br>Responsabilização]
    Q --> U[Fim]
    T --> U

    click B "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art22" _blank
    click F "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art24" _blank
    click G "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art33" _blank
    click H "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art42" _blank
    click K "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art58" _blank
    click M "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art57" _blank
    click O "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art63" _blank
    click T "https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l13019.htm#art73" _blank

    style B fill:#f9f,stroke:#333,stroke-width:2px
    style F fill:#bbf,stroke:#333,stroke-width:2px
    style J fill:#bfb,stroke:#333,stroke-width:2px
    style K fill:#fbf,stroke:#333,stroke-width:2px
    style O fill:#fbb,stroke:#333,stroke-width:2px
</div>

Este fluxograma apresenta uma visão geral do processo de parceria entre o poder público e as Organizações da Sociedade Civil (OSCs) conforme a Lei do MROSC. Cada etapa está vinculada aos artigos relevantes da lei, e as cores destacam as fases principais do processo.

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

</main>

{% include footer.html %}
