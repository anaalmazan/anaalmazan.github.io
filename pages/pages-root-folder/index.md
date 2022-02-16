---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "película del mes: Spencer"
  url: 'https://www.imdb.com/title/tt12536294/'
  image: widget-1-302x182.jpg
  text: 'Biopic de Lady Di que cuenta la historia de un fin de semana crucial a principios de los años 90, cuando la princesa Diana -de nombre Diana Frances Spencer- decidió que su matrimonio con el príncipe Carlos no estaba funcionando, y que necesitaba desviarse de un camino que la había puesto en primera fila para algún día ser reina... El drama tiene lugar durante tres días, en una de sus últimas vacaciones de Navidad en la Casa de Windsor en su finca de Sandringham en Norfolk, Inglaterra.'
widget2:
  title: "Talento Mexicano: Alexandra Can"
  url: 'https://www.instagram.com/alexandra_cn_/'
  text: '<em>La artista cancunense</em> Alexandra Can nos sorprende con un cover del éxito de Olivia rodrigo "Driver License".'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://anaalmazan.github.io/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Lo que no vistes en el nuevo tráiler de Doctor Strange: en el multiverso de la locura"
  url: 'https://www.youtube.com/watch?v=_IwvFi5TRr0'
  image: widget-github-303x182.jpg
  text: '<em>La espera ha terminado</em> y el nuevo tráiler de la secuela de Doctor Strange ha salido. En dos minutos y diecisiete segundos hemos notado muchas referencias escondidas que te aseguramos no haz notado.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://www.instagram.com/aana_almazan/
  text: Más sobre la creadora ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://youtu.be/bd9j1XpbJCg" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
