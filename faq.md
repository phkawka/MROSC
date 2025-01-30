---
layout: default
title: Perguntas Frequentes (FAQ)
---
<script>
document.documentElement.lang = 'pt-BR';
</script>

[Pular para o conteúdo principal](#conteudo-principal){:.skip-to-content}

{% include navigation.html %}

<a id="conteudo-principal" class="visually-hidden">Início do conteúdo principal</a>

# Perguntas Frequentes (FAQ)

<div class="faq-container">
  <div class="faq-item">
    <h2 class="faq-question">O que é o MROSC?</h2>
    <div class="faq-answer">
      <p>MROSC significa Marco Regulatório das Organizações da Sociedade Civil. É uma lei (Lei 13.019/2014) que estabelece o regime jurídico das parcerias entre a administração pública e as organizações da sociedade civil.</p>
    </div>
  </div>

  <div class="faq-item">
    <h2 class="faq-question">Quem está sujeito ao MROSC?</h2>
    <div class="faq-answer">
      <p>O MROSC se aplica à administração pública federal, estadual, distrital e municipal, bem como às organizações da sociedade civil que realizam parcerias com o poder público.</p>
    </div>
  </div>

  <div class="faq-item">
    <h2 class="faq-question">Qual a diferença entre Termo de Colaboração e Termo de Fomento?</h2>
    <div class="faq-answer">
      <p>O Termo de Colaboração é usado quando a administração pública propõe a parceria. O Termo de Fomento é utilizado quando a proposta de parceria parte da organização da sociedade civil.</p>
    </div>
  </div>

  <div class="faq-item">
    <h2 class="faq-question">O que é o chamamento público?</h2>
    <div class="faq-answer">
      <p>O chamamento público é o procedimento destinado a selecionar organização da sociedade civil para firmar parceria por meio de termo de colaboração ou de fomento, no qual se garante a observância dos princípios da isonomia, da legalidade, da impessoalidade, da moralidade, da igualdade, da publicidade, da probidade administrativa, da vinculação ao instrumento convocatório, do julgamento objetivo e dos que lhes são correlatos.</p>
    </div>
  </div>

  <div class="faq-item">
    <h2 class="faq-question">Quais são as etapas de uma parceria MROSC?</h2>
    <div class="faq-answer">
      <p>As principais etapas de uma parceria MROSC são: Planejamento, Chamamento Público, Seleção da OSC, Celebração da Parceria, Execução, Monitoramento e Avaliação, e Prestação de Contas.</p>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  const questions = document.querySelectorAll('.faq-question');
  
  questions.forEach(question => {
    question.addEventListener('click', () => {
      const answer = question.nextElementSibling;
      answer.style.display = answer.style.display === 'block' ? 'none' : 'block';
    });
  });
});
</script>
