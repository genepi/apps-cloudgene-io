---
layout: default
title: Applications
---

<div class="album py-5 bg-light">
  <div class="container">
    <div class="row">
    {% for app in site.apps %}
      <div class="col-md-4">
        <div class="card mb-4 box-shadow">
          <div class="card-body">
            <h5 class="card-title"><a href="{{app.url}}">{{ app.title }}</a> <small>{{ app.version }}</small></h5>
            <div style="height: 150px;">
            <p class="card-text">{{ app.description_short}}</p>
            </div>
            <div class="d-flex justify-content-between align-items-center">
              <div>
              {% for author in app.authors %}
              	<img src="{{author.avatar}}" title="{{author.name}}"/>
              {% endfor %}
              </div>
              <small class="text-muted">xx downloads</small>
            </div>
          </div>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</div>
