---
layout: default
title: Perguntas Frequentes (FAQ)
---

{% include navigation.html %}

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
