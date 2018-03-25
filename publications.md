---
layout: page
permalink: /publications/index.html
title: Publications
pubs:   
  - title: "aaa"
    author: "bbb"
    booktitle: "ACL 2018"
    year: 2018
    url: 2006pdpta.pdf
    bibtex: 2006pdpta.bib


  - key: "ansel:pact:2014"
    author: "Jason Ansel, Shoaib Kamil, Kalyan Veeramachaneni, Jonathan Ragan-Kelley, Jeffrey Bosboom, Una-May O'Reilly, Saman Amarasinghe"
    title: "OpenTuner: An Extensible Framework for Program Autotuning"
    url: "http://groups.csail.mit.edu/commit/papers/2014/ansel-pact14-opentuner.pdf"
    slides: "http://groups.csail.mit.edu/commit/papers/2014/ansel-pact14-opentuner-slides.pdf"
    keywords: "OpenTuner"
    month: "August"
    year: "2018"
    address: "Edmonton, Canada"
    booktitle: "ACL 2018 long paper"


  - title: "Transparent User-Level Checkpointing for the Native POSIX Thread Library for Linux"
    author: "Michael Rieker, Jason Ansel, Gene Cooperman"
    booktitle: "The International Conference on Parallel and Distributed Processing Techniques and Applications"
    address: "Las Vegas, NV"
    month: Jun
    year: 2006
    url: 2006pdpta.pdf
    bibtex: 2006pdpta.bib




---

# Publications

{% for pub in page.pubs %}
{% unless pub.hidden %}
  - {% if pub.url %} [{{pub.title}}]({{pub.url}}).
    {% else %} {{pub.title}}.
    {% endif %}{% if pub.type %}({{pub.type}})
    {% endif %}<br>
    {{pub.author}}.<br>
    {% if pub.type == 'Technical Report' %}{{pub.number}}
    {% endif %}{{pub.booktitle}}{{pub.school}}{{pub.journal}}.<br>
    {% if pub.address %}{{pub.address}}.
    {% endif %} {{pub.month}}, {{pub.year}}. {% if pub.slides %}[Slides]({{pub.slides}}).
    {% endif %}{% if pub.key %}[Bibtex](http://groups.csail.mit.edu/commit/bibtex.cgi?key={{pub.key}}).
    {% endif %}{% if pub.bibtex %}[Bibtex]({{pub.bibtex}}).
    {% endif %}
{% endunless %}
{% endfor %}



