---
layout: default
permalink: /cv/
title: cv|resume
nav: true
nav_order: 4
description: Attached Below are copies of my CV or Resume as an embedded frame for your perusal!
---
<header class="post-header">
	<h1 class="post-title">{{ page.title }} {% if page.cv_pdf %}<a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h1>
		{% if page.description %}<p class="post-description">{{ page.description }}</p>{% endif %}
</header>

<h4>Attached CV </h4>
<iframe
	src="https://docs.google.com/document/d/e/2PACX-1vTeAUTxPLDBe-gX19Pgw3Mit8_L5iqq5MuwfqPF7lNMW52FzBLKFoxdWcnvN-ZcXfEebY2Ir5h1QD_A/pub?embedded=true"
	width="100%"
	height="500"

	border="0"
	marginwidth="0"
	marginheight="0">
</iframe>
