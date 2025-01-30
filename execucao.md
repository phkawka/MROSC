---
layout: default
title: Execução da Parceria na Lei do MROSC
---
<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include header.html %}

{% include navigation.html %}

<main id="conteudo-principal" markdown="1">

## Execução da Parceria na Lei do MROSC

A fase de execução é o momento em que a Organização da Sociedade Civil (OSC) coloca em prática o plano de trabalho aprovado, realizando as atividades e alcançando as metas estabelecidas na parceria com o poder público.

### Importância da Execução

- Materialização dos objetivos da parceria
- Implementação das ações planejadas
- Aplicação efetiva dos recursos públicos
- Geração de impacto social

### Principais Aspectos da Execução

1. **Início da Execução**
   - Liberação da primeira parcela dos recursos
   - Cumprimento das condições suspensivas, se houver

2. **Realização das Atividades**
   - Execução das ações conforme o plano de trabalho
   - Cumprimento do cronograma estabelecido

3. **Gestão Financeira**
   - Utilização dos recursos conforme o plano de trabalho
   - Manutenção dos recursos em conta bancária específica
   - Aplicação financeira dos recursos enquanto não utilizados

4. **Aquisições e Contratações**
   - Observância dos princípios da administração pública
   - Cotação prévia de preços no mercado
   - Manutenção da documentação referente às compras e contratações
  
## Fluxograma do Processo de Execução da Parceria

<div class="mermaid">
graph TD
    A[Início da Execução] --> B[Liberação de Recursos]
    B --> C[Realização das Atividades<br>conforme Plano de Trabalho]
    C --> D[Monitoramento Contínuo]
    D --> E{Necessidade de<br>Alteração?}
    E -->|Sim| F[Proposta de<br>Termo Aditivo]
    F --> G[Análise e Aprovação<br>da Alteração]
    G --> C
    E -->|Não| H[Continuação da Execução]
    H --> I[Elaboração de Relatórios<br>Periódicos]
    I --> J[Avaliação dos Resultados<br>Parciais]
    J --> K{Metas<br>Alcançadas?}
    K -->|Sim| L[Continuação ou<br>Conclusão da Parceria]
    K -->|Não| M[Medidas Corretivas]
    M --> C
    L --> N[Preparação para<br>Prestação de Contas]
    N --> O[Fim da Execução]

    style B fill:#f9f,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style D fill:#bfb,stroke:#333,stroke-width:2px
    style J fill:#fbb,stroke:#333,stroke-width:2px
</div>

Este fluxograma ilustra as etapas principais do processo de Execução da Parceria, desde o início da execução até a preparação para a prestação de contas. As cores destacam fases cruciais do processo.

### Responsabilidades da OSC durante a Execução

- Executar fielmente o objeto da parceria
- Zelar pela boa qualidade das ações e serviços prestados
- Manter escrituração contábil regular
- Divulgar a parceria em seu sítio eletrônico e em locais visíveis de sua sede social
- Permitir o livre acesso dos agentes da administração pública e do controle interno e externo

### Responsabilidades da Administração Pública

- Liberar os recursos de acordo com o cronograma de desembolso
- Realizar procedimentos de fiscalização das parcerias
- Acompanhar e avaliar o cumprimento do objeto da parceria
- Emitir relatório técnico de monitoramento e avaliação

### Alterações na Execução

- Possibilidade de remanejamento de recursos sem prévia aprovação, dentro de limites estabelecidos
- Necessidade de termo aditivo para alterações que modifiquem o plano de trabalho

### Movimentação e Aplicação Financeira dos Recursos

- Movimentação mediante transferência eletrônica
- Pagamentos em espécie limitados a R$ 1.800,00 por beneficiário
- Aplicação financeira em caderneta de poupança ou fundo de aplicação financeira de curto prazo

### Vedações na Execução

- Utilização dos recursos para finalidade alheia ao objeto da parceria
- Pagar, a qualquer título, servidor ou empregado público com recursos da parceria
- Modificar o objeto da parceria sem autorização prévia

### Dicas para uma Execução Eficaz

- Mantenha uma comunicação constante com o gestor da parceria
- Documente todas as atividades realizadas e despesas efetuadas
- Esteja atento aos prazos e metas estabelecidos no plano de trabalho
- Realize avaliações periódicas internas para garantir o alinhamento com os objetivos da parceria

### Base Legal
- Artigos 42 a 50 da Lei 13.019/2014 - Estabelecem as regras para a execução da parceria

### Próximos Passos
Durante e após a execução, é fundamental realizar o [Monitoramento e Avaliação]({{ site.baseurl }}/monitoramento-avaliacao) da parceria, seguido pela [Prestação de Contas]({{ site.baseurl }}/prestacao-contas).

### Conteúdos Relacionados
- [Celebração da Parceria]({{ site.baseurl }}/celebracao-parceria)
- [Monitoramento e Avaliação]({{ site.baseurl }}/monitoramento-avaliacao)
- [Prestação de Contas]({{ site.baseurl }}/prestacao-contas)

</main>

{% include footer.html %}

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>
