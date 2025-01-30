---
layout: default
title: Seleção da OSC na Lei do MROSC
---
<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include header.html %}

{% include navigation.html %}

<main id="conteudo-principal" markdown="1">

## Seleção da OSC na Lei do MROSC

A seleção da Organização da Sociedade Civil (OSC) é uma etapa crucial no processo de estabelecimento de parcerias entre o poder público e as organizações da sociedade civil. Esta fase visa garantir que a organização mais adequada seja escolhida para executar o objeto da parceria.

### Importância da Seleção da OSC

- Garante a escolha da organização mais capacitada para executar o projeto
- Assegura transparência e impessoalidade no processo de escolha
- Promove a competitividade e a eficiência na aplicação dos recursos públicos

### Critérios de Seleção

Os critérios de seleção devem ser claros, objetivos e alinhados com o objeto da parceria. Alguns exemplos incluem:

1. **Capacidade Técnica e Operacional**
   - Experiência prévia na realização de projetos semelhantes
   - Estrutura física e recursos humanos adequados

2. **Adequação da Proposta**
   - Coerência entre objetivos, metas e custos
   - Viabilidade de execução do projeto

3. **Impacto Social**
   - Benefícios esperados para a comunidade
   - Potencial de transformação social

4. **Sustentabilidade**
   - Capacidade de continuidade das ações após o término da parceria
   - Estratégias de captação de recursos complementares

### Processo de Avaliação

1. **Análise das Propostas**
   - Verificação do cumprimento dos requisitos do edital
   - Avaliação técnica das propostas recebidas

2. **Pontuação**
   - Atribuição de notas conforme critérios estabelecidos no edital
   - Classificação das propostas em ordem decrescente

3. **Diligências**
   - Esclarecimento de dúvidas ou solicitação de informações adicionais, se necessário
  
   ## Fluxograma do Processo de Seleção da OSC

<div class="mermaid">
graph TD
    A[Início] --> B[Recebimento das Propostas]
    B --> C[Abertura dos Envelopes]
    C --> D[Análise dos Documentos<br>de Habilitação]
    D --> E{OSC Habilitada?}
    E -->|Não| F[Inabilitação da OSC]
    E -->|Sim| G[Análise Técnica<br>da Proposta]
    G --> H[Avaliação e Pontuação<br>conforme Critérios do Edital]
    H --> I[Classificação das Propostas]
    I --> J[Divulgação do<br>Resultado Preliminar]
    J --> K{Recursos<br>Apresentados?}
    K -->|Sim| L[Análise dos Recursos]
    L --> M[Decisão sobre os Recursos]
    M --> N[Divulgação do<br>Resultado Final]
    K -->|Não| N
    N --> O[Homologação do Resultado]
    O --> P[Convocação da OSC<br>Selecionada]
    P --> Q[Verificação dos Requisitos<br>para Celebração]
    Q --> R{Requisitos<br>Atendidos?}
    R -->|Sim| S[Celebração da Parceria]
    R -->|Não| T[Convocação da Próxima<br>OSC Classificada]
    T --> Q
    S --> U[Fim]

    style D fill:#f9f,stroke:#333,stroke-width:2px
    style G fill:#bbf,stroke:#333,stroke-width:2px
    style J fill:#bfb,stroke:#333,stroke-width:2px
    style Q fill:#fbb,stroke:#333,stroke-width:2px
</div>

Este fluxograma ilustra as etapas principais do processo de Seleção da OSC, desde o recebimento das propostas até a celebração da parceria. As cores destacam fases cruciais do processo.

### Comissão de Seleção

- Órgão colegiado destinado a processar e julgar o chamamento público
- Composta por pelo menos 2/3 de membros servidores ocupantes de cargo efetivo ou emprego permanente
- Deve ser assegurada a participação de pelo menos um servidor ocupante de cargo efetivo ou emprego permanente do órgão ou entidade da administração pública realizadora do chamamento público

### Divulgação dos Resultados

- Publicação do resultado preliminar do processo de seleção no site oficial
- Abertura de prazo para recursos (geralmente 5 dias úteis)
- Análise dos recursos pela Comissão de Seleção
- Publicação do resultado definitivo

### Homologação e Publicação

- Homologação do resultado final pela autoridade competente
- Publicação do resultado final em meio oficial de publicidade

### Dicas para uma Seleção Eficaz

- Estabeleça critérios objetivos e mensuráveis
- Garanta a imparcialidade da Comissão de Seleção
- Mantenha transparência em todas as etapas do processo
- Documente cuidadosamente todas as decisões e justificativas

### Base Legal
- Artigos 23 a 32 da Lei 13.019/2014 - Estabelecem as regras para o processo de seleção

### Próximos Passos
Após a seleção da OSC, o próximo passo é a [Celebração da Parceria]({{ site.baseurl }}/celebracao-parceria), onde serão formalizados os termos da colaboração ou fomento.

### Conteúdos Relacionados
- [Chamamento Público]({{ site.baseurl }}/chamamento-publico)
- [Celebração da Parceria]({{ site.baseurl }}/celebracao-parceria)
- [Planejamento]({{ site.baseurl }}/planejamento)

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

</main>

{% include footer.html %}
