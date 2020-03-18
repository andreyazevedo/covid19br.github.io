---
title: "Observatório COVID-19 BR"
output: 
 flexdashboard::flex_dashboard:
  orientation: columns
  vertical_layout: scroll
  source: embed
  source_code: "https://github.com/covid19br/covid19br.github.io"
  social: menu
  css: styles.css
  navbar:
      - { title: "Início", href: "index.html", align: left}
      - { title: "+Info", href: "informacoes.html", align: left}
      - { title: "Fontes", href: "fontes.html", align: left}
      - { title: "Sobre", href: "sobre.html", align: left}
  favicon: favicon.png
 includes:
  after_body: footer.html
  in_header: header.html
---

# Sobre


<b>Diante da propagação da COVID-19, doença causada pelo novo coronavírus, a Organização Mundial da Saúde (OMS) decretou pandemia mundial no dia 11/03. Segundo a OMS, uma pandemia é a disseminação mundial de uma nova doença. Com início na China, o coronavírus se espalhou rapidamente por todos os continentes, contaminando milhares pessoas e levando diversos governantes a tomarem medidas drásticas para a contenção da doença. A dinâmica da transmissão de doenças infecciosas e, em particular, da COVID-19, deve ser compreendida para que os governos possam tomar as melhores decisões. Neste sentido, modelos matemáticos são fundamentais uma vez que, a partir deles, tendências e diferentes cenários podem ser simulados. Os resultados de simulações matemáticas, embora sempre apresentem incertezas, são de suma importância para o planejamento de políticas públicas. Diante do surto de COVID-19 que já se apresenta no Brasil, nós, cientistas de diversas áreas, apresentamos aqui análises matemáticas baseadas em dados empíricos oficiais da propagação do coronavírus no país. Esperamos contribuir com as autoridades responsáveis e informar a população a partir de um ponto de vista científico.</b>

<p>

</p>

<h2>Sobre a iniciativa</h2>

O **Observatório Covid-19 BR** é uma iniciativa independente, fruto da coaboração entre pesquisadores com o desejo de contribuir para a disseminação de informação de qualidade baseada em dados atualizados e análises cientificamente embasadas. Criamos este um aplicativo de fonte aberta que nos permite acompanhar o estado atual da epidemia de Covid-19 no Brasil, incluindo análises estatísticas e previsões.


A interface gráfica foi produzida utilizando-se [R Markdown](https://rmarkdown.rstudio.com/) e os códigos podem ser encontrados em nosso [github](https://github.com/covid19br/covid19BR).


<h3>Autores</h3>

* Roberto Kraenkel (professor @ [IFT-UNESP](https://professores.ift.unesp.br/roberto.kraenkel/))
    + [CV](http://lattes.cnpq.br/8497878967418484)
    + <kraenkel@ift.unesp.br>

* Paulo Inácio (professor @ [IB-USP](http://ecologia.ib.usp.br/let/doku.php))
    + [CV](http://lattes.cnpq.br/3884092565521453)
    + <prado@ib.usp.br>

* Paulo Guimarães (Miúdo) (professor @ [IB-USP](http://guimaraeslab.weebly.com/))

* Renato Coutinho  (professor @ [CMCC-UFABC](http://professor.ufabc.edu.br/~renato.coutinho/))
    + [CV](http://lattes.cnpq.br/1301865568118160)
    + <renato.coutinho@ufabc.edu.br>

* Rodrigo Corder (doutorando @ [ICB-USP](http://ww3.icb.usp.br))
    + [CV](http://lattes.cnpq.br/9741820804547685)
    + <rodrigo.corder@usp.br>

* Caroline Franco (doutoranda @ [IFT-UNESP](https://www.ift.unesp.br/))
    + [CV](http://lattes.cnpq.br/1810788882318135)
    + <c.franco@unesp.br>
