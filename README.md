# courses

- acp
- anova_1_facteur
- anova_2_facteurs
- classification
- intervalles_confiance_et_prediction
- regression_lineaire_multiple
- regression_lineaire_multivariee
- regression_lineaire_simple
- tests_hypothèses

<script>
  document.querySelectorAll('li').values().forEach(el => el.innerHTML = `<a href="./${el.innerText}/public/${el.innerText}.html">${el.innerText.replaceAll("_"," ").replace(el.innerText[0],el.innerText[0].toUpperCase())}</a>`)
</script>
