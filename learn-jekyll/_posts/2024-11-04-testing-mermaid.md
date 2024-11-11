---
layout: post
categories: jekyll update
mermaid: true
---

Following <a href="https://japoneris.neocities.org/tech/2022/07/15/including_html">HTML files within markdown for Jekyll</a>, HTML for Mermaid injected as follows: 
<br /><br />

{% include mm/test.html %}
<br /><br />

{% include mm/kbd.html %}
<br /><br />

{% include mm/chart.html %}
<br /><br />

> Note: Code injection for components (as above) is probably not how it was intended to be used.

- With **injected** HTML, it is possible to write posts using a combination of HTML and markdown!
- Including [ChartJS](https://comp.anu.edu.au/docs/jekyll-anu-theme-docs/site-developers/html-and-markdown/) is easy!
- (WIP) Try changing background of above diagram to transparent