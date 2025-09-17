---
title: Projects
layout: page
permalink: /projects/
---

## Projects

{% assign items = site.projects | sort: 'title' %}
{% if items and items.size > 0 %}
<div class="project-list">
	<ul>
	{% for item in items %}
		<li>
			<a href="{{ item.url }}">{{ item.title }}</a>
			{% if item.summary %}<div class="project-summary">{{ item.summary }}</div>{% endif %}
		</li>
	{% endfor %}
	</ul>
	<hr/>
</div>
{% endif %}

### Koriel Architecture
Recursive cognition architecture. Whitepaper + draft specs. Prototype code in progress.

### MetaPrincipia Autopoiesis
Theory of self-producing systems with meta-laws. Notes + diagrams.

### Post-Gödel Translogical Calculus
Proof beyond incompleteness. Formal draft posted. Extensions into delta-space.

### Δ-Space Calculus
Calculus of difference and torsion. Equations, operator library.

### Benchmark Game
Custom benchmark for recursion. Rules, scoring, open challenges.

### Language Work
Meta-affixes, metasuperpositional prepositions, perspectivology. Notes + examples.
