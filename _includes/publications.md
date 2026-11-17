<h2 id="publications">Publications</h2>
<p class="publication-note">Newest first in each group. <a href="{{ site.google_scholar }}">Google Scholar</a><br><sup>*</sup> Equal contribution · <sup>†</sup> Corresponding author. Click any figure to view it in full.</p>
<div class="publications">
  {% assign publication_groups = "selected,others" | split: "," %}
  {% for group in publication_groups %}
  <h3 class="publication-group-title" id="{{ group }}-publications">{{ group | capitalize }}</h3>
  <ol class="bibliography" aria-label="{{ group | capitalize }} publications">
    {% assign publications = site.data.publications.main | where: "group", group %}
    {% if group == "selected" %}
      {% assign publications = publications | sort: "selected_order" %}
    {% else %}
      {% assign publications = publications | sort: "sort_date" | reverse %}
    {% endif %}
    {% for paper in publications %}
    <li>
      <div class="pub-row">
        <div class="publication-image">
          <a href="{{ paper.image }}" class="publication-figure-link" target="_blank" rel="noopener noreferrer" aria-label="View full figure for {{ paper.title | escape }}" title="View full figure">
            <img src="{{ paper.image }}" class="teaser"{% if paper.image_position %} style="--figure-position: {{ paper.image_position }};"{% endif %} alt="{{ paper.image_alt }}" width="1200" height="{{ paper.image_height }}" loading="lazy">
          </a>
          <span class="publication-badge">{{ paper.conference_short }}</span>
        </div>
        <div class="publication-details">
          <div class="title"><a href="{% if paper.pdf %}{{ paper.pdf }}{% elsif paper.paper %}{{ paper.paper }}{% else %}{{ paper.page }}{% endif %}">{{ paper.title }}</a></div>
          <div class="author">{{ paper.authors }}</div>
          <div class="periodical"><em>{{ paper.conference }}</em></div>
          <div class="links">
            {% if paper.pdf %}<a href="{{ paper.pdf }}" class="btn" target="_blank" rel="noopener noreferrer">PDF</a>{% endif %}
            {% if paper.page and paper.page_before_code %}<a href="{{ paper.page }}" class="btn" target="_blank" rel="noopener noreferrer">Project Page</a>{% endif %}
            {% if paper.paper %}<a href="{{ paper.paper }}" class="btn" target="_blank" rel="noopener noreferrer">Paper</a>{% endif %}
            {% if paper.code %}<a href="{{ paper.code }}" class="btn" target="_blank" rel="noopener noreferrer">Code</a>{% endif %}
            {% if paper.page and paper.page_before_code != true %}<a href="{{ paper.page }}" class="btn" target="_blank" rel="noopener noreferrer">{% if paper.pdf %}Project Page{% else %}Conference{% endif %}</a>{% endif %}
            {% if paper.scholar %}<a href="{{ paper.scholar }}" class="btn" target="_blank" rel="noopener noreferrer">Scholar</a>{% endif %}
            {% if paper.notes %}<span class="publication-highlight">{{ paper.notes }}</span>{% endif %}
          </div>
        </div>
      </div>
    </li>
    {% endfor %}
  </ol>
  {% endfor %}
</div>
