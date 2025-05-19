---
permalink: /
layout: archive
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
classes: wide
---
Saber Salehkaleybar is an assistant professor at the Leiden Institute of Advanced Computer Science (LIACS), Leiden University. Prior to this, he worked as a research scientist in the School of Computer and Communication Sciences (IC) and College of Management of Technology (CDM) at École Polytechnique Fédérale de Lausanne. His research interests include causal inference, stochastic optimization, and reinforcement learning. He is particularly interested in causal discovery, experiment design, and applications of causality in generative AI. Additionally, he is focused on developing efficient optimization algorithms for training large learning models. 

<h2>Latest News</h2>
<ul>
  {% for item in site.data.news limit:20 %}
    <li>
      <p>{{ item.title }}</p>
    </li>
  {% endfor %}
</ul>
