---
layout: default
title: Chamamento Público na Lei do MROSC
---
<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include header.html %}

{% include navigation.html %}

<main id="conteudo-principal" markdown="1">

## Chamamento Público na Lei do MROSC

O Chamamento Público é um procedimento destinado a selecionar organizações da sociedade civil para firmar parcerias com a administração pública, garantindo oportunidades de acesso a todas as organizações interessadas.

### O que é Chamamento Público?

- Processo transparente de seleção de OSCs
- Garante isonomia e impessoalidade na escolha das organizações parceiras
- Obrigatório na maioria dos casos, com exceções previstas em lei

### Quando é Necessário

O chamamento público é obrigatório para a celebração de termos de colaboração ou de fomento, exceto em casos específicos previstos na Lei 13.019/2014, como:

- Urgência decorrente de paralisação/iminência de paralisação de atividades de relevante interesse público
- Casos de guerra, calamidade pública, grave perturbação da ordem pública ou ameaça à paz social
- Programas de proteção a pessoas ameaçadas ou em situação que possa comprometer sua segurança

## Fluxograma do Processo de Chamamento Público

<div class="mermaid">
graph TD
    A[Início] --> B[Planejamento do Edital]
    B --> C[Elaboração do Edital]
    C --> D[Aprovação Jurídica]
    D --> E[Publicação do Edital]
    E --> F{Impugnação<br>do Edital?}
    F -->|Sim| G[Análise da Impugnação]
    G --> H{Impugnação<br>Aceita?}
    H -->|Sim| I[Retificação do Edital]
    I --> E
    H -->|Não| J[Manutenção do Edital]
    J --> K[Recebimento das Propostas]
    F -->|Não| K
    K --> L[Abertura e Avaliação<br>das Propostas]
    L --> M[Divulgação do<br>Resultado Preliminar]
    M --> N{Recursos<br>Apresentados?}
    N -->|Sim| O[Análise dos Recursos]
    O --> P[Decisão Final]
    N -->|Não| P
    P --> Q[Homologação e<br>Publicação do Resultado]
    Q --> R[Fim]

    style B fill:#f9f,stroke:#333,stroke-width:2px
    style E fill:#bbf,stroke:#333,stroke-width:2px
    style L fill:#bfb,stroke:#333,stroke-width:2px
    style Q fill:#fbb,stroke:#333,stroke-width:2px
</div>

Este fluxograma ilustra as principais etapas do processo de Chamamento Público, desde o planejamento do edital até a publicação do resultado final. As cores destacam fases cruciais do processo.

### Etapas do Chamamento Público

1. **Planejamento e Elaboração do Edital**
   - Definição clara do objeto da parceria
   - Estabelecimento de critérios objetivos de seleção

2. **Publicação do Edital**
   - Ampla divulgação em sítio oficial e outros meios
   - Prazo mínimo de 30 dias para apresentação de propostas

3. **Recebimento e Avaliação das Propostas**
   - Análise pela comissão de seleção
   - Aplicação dos critérios estabelecidos no edital

4. **Divulgação dos Resultados**
   - Publicação da classificação das propostas
   - Abertura de prazo para recursos

5. **Homologação e Celebração da Parceria**
   - Verificação dos requisitos para celebração
   - Assinatura do termo de colaboração ou fomento

### Elaboração do Edital

O edital de chamamento público deve conter, no mínimo:

- Programação orçamentária
- Objeto da parceria
- Datas, prazos, condições, local e forma de apresentação das propostas
- Critérios de seleção e julgamento das propostas
- Valor de referência para a realização do objeto

### Comissão de Seleção

- Órgão colegiado destinado a processar e julgar chamamentos públicos
- Composta por pelo menos 2/3 de servidores ocupantes de cargos permanentes
- Deve ser assegurada a participação de pelo menos um servidor da área finalística

### Dicas para um Chamamento Público Eficaz

- Seja claro e objetivo na descrição do objeto da parceria
- Estabeleça critérios de seleção mensuráveis e relevantes
- Garanta ampla publicidade ao edital
- Mantenha transparência em todas as etapas do processo

### Base Legal
- Artigos 23 a 32 da Lei 13.019/2014 - Estabelecem as regras para o chamamento público

### Próximos Passos
Após a conclusão do chamamento público, segue-se para a etapa de [Seleção da OSC]({{ site.baseurl }}/selecao-osc) e posterior [Celebração da Parceria]({{ site.baseurl }}/celebracao-parceria).

### Conteúdos Relacionados
- [Planejamento]({{ site.baseurl }}/planejamento)
- [Seleção da OSC]({{ site.baseurl }}/selecao-osc)
- [Celebração da Parceria]({{ site.baseurl }}/celebracao-parceria)

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

</main>

{% include footer.html %}
