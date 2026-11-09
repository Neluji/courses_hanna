# Cours :

<div id="courses_list">

  - acp
  - anova_1_facteur
  - anova_2_facteurs
  - introduction_ML
  - intervalles_confiance_et_prediction
  - regression_lineaire_multiple
  - regression_lineaire_multivariee
  - regression_lineaire_simple
  - tests_hypothèses

</div>


# Détails : 

Les leçons régression linéaire simple, ANOVA à 1 et 2 facteurs, Introduction au Machine Learning, Intervalles de confiance/prédiction et Tests d'hypothèses sont finalisées et tapées 

$\Longrightarrow$ Il ne reste que les modifications suivantes : soigner le style, mettre des annonces des sections et un plan + clair, puis relire les coquilles et fautes

ATTENTION : pour l'ANOVA à 1 facteur, le jeu de donnée n'est pas normal (il faut que je le modifie)

Les leçons régression linéaire multiple & multivariée et ACP sont écrites à la main après l'intro

$\Longrightarrow$ Il faudra les taper si je tombe dessus 

# Objectif : 
Relire les leçons pour voir : 
  - si le plan tient la route
  - si la leçon ressemble plutôt à cours (qui pourrait être enseigné en 45min/1h) 
  - si je n'ai pas écrit d'affreuseté



<script>
  document.querySelectorAll('#courses_list li').values().forEach(el => el.innerHTML = `<a href="./${el.innerText}/public/${el.innerText}.html">${el.innerText.replaceAll("_"," ").replace(el.innerText[0],el.innerText[0].toUpperCase())}</a>`)
</script>
