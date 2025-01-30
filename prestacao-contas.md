---
layout: default
title: Prestação de Contas na Lei do MROSC
---
<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include header.html %}

{% include navigation.html %}

<main id="conteudo-principal" markdown="1">

## Prestação de Contas na Lei do MROSC

A prestação de contas é uma etapa crucial no ciclo das parcerias entre o poder público e as Organizações da Sociedade Civil (OSCs). Ela visa demonstrar o cumprimento do objeto da parceria e o alcance das metas e resultados previstos.

### Importância da Prestação de Contas

- Demonstra a correta aplicação dos recursos públicos
- Comprova o cumprimento do objeto e o alcance das metas
- Promove a transparência e o controle social
- Permite a avaliação dos resultados da parceria

### Procedimento de Prestação de Contas

1. **Apresentação pela OSC**
   - Relatório de Execução do Objeto
   - Relatório de Execução Financeira (quando necessário)

2. **Análise pela Administração Pública**
   - Relatório técnico de monitoramento e avaliação
   - Parecer técnico conclusivo

3. **Decisão da Autoridade Competente**
   - Aprovação
   - Aprovação com ressalvas
   - Rejeição com determinação de imediata instauração de tomada de contas especial
  
## Fluxograma do Processo de Prestação de Contas

<div class="mermaid">
graph TD
    A[Início] --> B[Preparação da Prestação<br>de Contas pela OSC]
    B --> C[Elaboração do Relatório<br>de Execução do Objeto]
    C --> D[Elaboração do Relatório<br>de Execução Financeira]
    D --> E[Envio da Prestação de Contas<br>à Administração Pública]
    E --> F[Análise da Prestação<br>de Contas]
    F --> G{Necessidade de<br>Diligências?}
    G -->|Sim| H[Notificação à OSC]
    H --> I[Resposta da OSC]
    I --> F
    G -->|Não| J[Emissão de Parecer<br>Técnico Conclusivo]
    J --> K{Resultado da<br>Análise}
    K -->|Aprovação| L[Quitação da OSC]
    K -->|Aprovação com Ressalvas| M[Determinação de<br>Medidas Saneadoras]
    K -->|Rejeição| N[Determinação de<br>Devolução de Recursos]
    M --> O[Monitoramento das<br>Medidas Saneadoras]
    N --> P[Instauração de Tomada<br>de Contas Especial]
    L --> Q[Arquivamento do Processo]
    O --> Q
    P --> Q
    Q --> R[Fim]

    style B fill:#f9f,stroke:#333,stroke-width:2px
    style E fill:#bbf,stroke:#333,stroke-width:2px
    style F fill:#bfb,stroke:#333,stroke-width:2px
    style J fill:#fbb,stroke:#333,stroke-width:2px
</div>

Este fluxograma ilustra as etapas principais do processo de Prestação de Contas, desde a preparação pela OSC até o arquivamento do processo. As cores destacam fases cruciais do processo.

### Relatório de Execução do Objeto

Deve conter:
- Demonstração do alcance das metas
- Descrição das ações desenvolvidas
- Documentos de comprovação da execução das ações e do alcance das metas
- Documentos de comprovação do cumprimento do objeto
- Elementos para avaliação dos impactos econômicos ou sociais das ações desenvolvidas
- Elementos para avaliação do grau de satisfação do público-alvo
- Elementos para avaliação da possibilidade de sustentabilidade das ações após a conclusão do objeto

### Relatório de Execução Financeira

Exigido apenas em caso de descumprimento de metas e resultados estabelecidos no plano de trabalho ou indícios de irregularidade. Deve conter:
- Relação das receitas e despesas realizadas
- Relação de bens adquiridos, produzidos ou transformados
- Comprovante da devolução do saldo remanescente da conta bancária específica
- Extrato da conta bancária específica
- Cópia simples das notas e dos comprovantes fiscais ou recibos
- Memória de cálculo do rateio das despesas, quando for o caso

### Prazos

- A OSC deve apresentar a prestação de contas final em até 90 dias após o término da vigência da parceria
- A administração pública tem até 150 dias para apreciar a prestação de contas, contados da data de seu recebimento ou do cumprimento de diligência por ela determinada

### Documentação e Guarda

- A OSC deve manter a guarda dos documentos originais relativos à execução das parcerias pelo prazo de 10 anos, contado do dia útil subsequente ao da apresentação da prestação de contas

### Sanções por Irregularidades

Em caso de rejeição da prestação de contas e não devolução dos recursos, a administração pública poderá:
- Determinar o ressarcimento integral dos recursos
- Instaurar tomada de contas especial
- Aplicar sanções previstas em lei

### Dicas para uma Prestação de Contas Eficaz

- Mantenha uma organização rigorosa da documentação desde o início da parceria
- Utilize sistemas informatizados para registro e controle das despesas
- Siga estritamente o plano de trabalho aprovado
- Comunique-se regularmente com o gestor da parceria para esclarecer dúvidas
- Atenda prontamente às solicitações de informações adicionais

### Base Legal
- Artigos 63 a 72 da Lei 13.019/2014 - Estabelecem as regras para a prestação de contas das parcerias

### Próximos Passos
Após a prestação de contas, é importante refletir sobre as lições aprendidas e aplicá-las em futuras parcerias. Além disso, é fundamental manter a [Transparência e Controle Social]({{ site.baseurl }}/transparencia-controle-social) em todas as etapas do processo.

### Conteúdos Relacionados
- [Execução]({{ site.baseurl }}/execucao)
- [Monitoramento e Avaliação]({{ site.baseurl }}/monitoramento-avaliacao)
- [Transparência e Controle Social]({{ site.baseurl }}/transparencia-controle-social)

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

</main>

{% include footer.html %}
