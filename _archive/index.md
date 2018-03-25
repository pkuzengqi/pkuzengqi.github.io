---
layout: page
title: 


pubs:   
  - title: "aaa"
    author: "bbb"
    conf: "ACL 2018"
    url: 2006pdpta.pdf
    bibtex: 2006pdpta.bib
    slides: "https://arxiv.org/list/cs.CL/recent"
    code: "https://arxiv.org/list/cs.CL/recent"

---

# About Me

<img src="/images/brown.jpg" class="floatpic" width="200" height="200">

My name is Qi Zeng.  I am a senior year student at Peking University.

See [acwing].


[acwing]: http://acwing.com



<br>
<br>
<br>
<br>
<br>



# Publications

{% for pub in page.pubs %}
{% unless pub.hidden %}
  - {% if pub.url %} [{{pub.title}}]({{pub.url}}).{% else %} {{pub.title}}.{% endif %}
    {{pub.author}}.<br>
    {% if pub.conf %}({{pub.conf}}){% endif %}<br>
    {% if pub.Code %}[Code]({{pub.slides}}).{% endif %}
    {% if pub.slides %}[Slides]({{pub.slides}}).{% endif %}
	{% if pub.bibtex %}[Bibtex]({{pub.bibtex}}).{% endif %}
{% endunless %}
{% endfor %}



<br>
<br>
<br>
<br>
<br>




# Academic Experience

### (SUNY) Stony Brook University  (2018 - present: PhD in Computer Science)
  - Advisor: [H. Andrew Schwartz][has]
  - Research Assistant: [The HLAB: Human Language Analysis Beings][HLAB] (2018-present)
  - Teaching Assistant: ? (Fall 2018)


[has]:http://www3.cs.stonybrook.edu/~has/
[HLAB]:http://hlab.cs.stonybrook.edu/

<br>

### Peking University (2013 - 2018: BS in Information Science)
  - Research Assistant: [Institute of Computational Linguistics][icl], Peking University(2017-2018)
  - Teaching Assistant: Study and Practice on Topics of Frontier Computing(I) (Fall 2017)

[icl]:icl.pku.edu.cn/

<br>
<br>
<br>
<br>
<br>




# Work Experience


### Microsoft Research Asia (01/2018 - 07/2017)
  - Research Intern at Big Data Mining Group

<br>

### Microsoft Search Technology Center Asia (03/2017 - 12/2017)
  - Software Engineer Intern at Xiaoice Group



<br>
<br>
<br>
<br>
<br>

