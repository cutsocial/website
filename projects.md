---
title: Projects
layout: default
description: Projects by Cut The Cake
publish_date: 2018-09-01 03:00:00 +0000

---

{% comment %}
	This layout is used to by projects.md to display all of documents in
	the _projects/ collection
{% endcomment %}

<div class="container pure-g">
	<div class="pure-u-1">
		<div class="content">
			<div class="grid-layout">
				<div class="container pure-g">
					{% for project in site.projects %}
					<div class="pure-u-1 pure-u-md-1-3">
						<div class="card">
							<div class="card-header">
							</div>
							<div class="card-body">
								<h3><a href="{{ project.url | absolute_url }}">{{ project.title }}</a></h3>
								<p>{{ project.summary | truncatewords: 30 | markdownify}}</p>
							</div>
						</div>
					</div>
					{% endfor %}
				</div>
			</div>
		</div>
	</div>
</div>
