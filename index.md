---

pubs2018:   
  - title: "aaa"
    author: "bbb"
    conf: "ACL 2018 long paper"
    slides: "https://arxiv.org/list/cs.CL/recent"
    code: "https://arxiv.org/list/cs.CL/recent"
    url: "https://arxiv.org/list/cs.CL/recent"
    bibtex: "https://arxiv.org/list/cs.CL/recent"

  - title: "aaa"
    author: "bbb"
    conf: "COLING 2018 long paper"
    url: "https://arxiv.org/list/cs.CL/recent"


---




# Hi!



My name is Qi Zeng. I am a senior year student at Peking University.



<img src="/images/brown.jpg" class="floatpic" width="200" height="200">



<br>
# Publications

### 2018

{% for pub in page.pubs2018 %}
{% unless pub.hidden %}
  - {% if pub.url %} [{{pub.title}}]({{pub.url}}).
    {% else %} {{pub.title}}.
    {% endif %}{% if pub.conf %}({{pub.conf}})
    {% endif %}<br>
    {{pub.author}}.<br>
    {% if pub.address %}{{pub.address}}.
    {% endif %}{% if pub.slides %}[Slides]({{pub.slides}}).
    {% endif %}{% if pub.bibtex %}[Bibtex]({{pub.bibtex}}).
    {% endif %}{% if pub.code %}[Code]({{pub.code}}).
    {% endif %}
{% endunless %}
{% endfor %}




<br>
# Academic Experience



### SUNY Stony Brook University (PhD in Computer Science, 2018 - present) 
<!---
  - Advisor: [H. Andrew Schwartz][has]
  - Research Assistant: [The HLAB: Human Language Analysis Beings][HLAB] (2018-present)
  - Teaching Assistant: ?? (Fall 2018)
-->


[has]:http://www3.cs.stonybrook.edu/~has/
[HLAB]:http://hlab.cs.stonybrook.edu/



### Peking University (BS in Information Science, 2013 - 2018)
  - Research Assistant
    - Institute of Computational Linguistics, Peking University (2017-2018)
  - Teaching Assistant
    - Study and Practice on Topics of Frontier Computing(I) (Fall 2017)


<br>
# Work Experience

### [Acwing] (03/2018 - present)
  - Co-founder


### Microsoft Research Asia (01/2018 - 07/2018)
  - Research Intern at Big Data Mining Group



### Microsoft STC Asia (03/2017 - 12/2017)
  - NLP Algorithm Intern at Xiaoice Group

[Acwing]: http://acwing.com

<br>
<br>
<br>
<br>
<br>

