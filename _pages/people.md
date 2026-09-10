---
permalink: /people/
title: "People"
author_profile: false
layout: splash
---

<link rel="stylesheet" href="{{ '/people.css' | relative_url }}?v={{ site.time | date: '%s' }}">

<div class="people-page">
  <h1 class="directory-page-title">People</h1>
  <nav class="people-nav" aria-label="People sections">
    <a href="#principal-investigator">Principal Investigator</a>
    <a href="#current-group-members">Current Members</a>
    <a href="#former-group-members">Former Members</a>
    <a href="#group-life">Group Life</a>
  </nav>
  {% assign principal_investigator = site.data.people.principal_investigator %}
  <h2 id="principal-investigator" class="people-section-title">Principal Investigator</h2>
  <div class="people-directory">
    <article id="{{ principal_investigator.name | slugify }}" class="people-directory-row people-directory-row--featured" aria-labelledby="{{ principal_investigator.name | slugify }}-name" tabindex="-1">
      <img
        class="people-portrait"
        src="{{ principal_investigator.image | relative_url }}"
        alt="{{ principal_investigator.image_alt | escape }}"
        width="116"
        height="116"
      >
      <div class="people-identity">
        <h3 id="{{ principal_investigator.name | slugify }}-name" class="people-name">{{ principal_investigator.name }}</h3>
        <p class="people-role">{{ principal_investigator.role }}</p>
      </div>
      <div class="people-background">
        {% for item in principal_investigator.background %}
          <p>{{ item }}</p>
        {% endfor %}
      </div>
      <div class="people-contact">
        <address>
          <a href="mailto:{{ principal_investigator.email }}">{{ principal_investigator.email }}</a><br>
          {{ principal_investigator.office }}
        </address>
      </div>
    </article>
  </div>

  <h2 id="current-group-members" class="people-section-title">Current Group Members</h2>
  <div class="people-directory">
    {% for person in site.data.people.current_members %}
      <article id="{{ person.name | slugify }}" class="people-directory-row" aria-labelledby="{{ person.name | slugify }}-name" tabindex="-1">
        <img
          class="people-portrait"
          src="{{ person.image | relative_url }}"
          alt="{{ person.image_alt | escape }}"
          width="76"
          height="76"
          loading="lazy"
        >
        <div class="people-identity">
          <h3 id="{{ person.name | slugify }}-name" class="people-name">{{ person.name }}</h3>
          <p class="people-role">{{ person.role }}</p>
        </div>
        <div class="people-background">
          {% for item in person.background %}
            <p>{{ item }}</p>
          {% endfor %}
        </div>
        <div class="people-contact">
          <address>
            <a href="mailto:{{ person.email }}">{{ person.email }}</a><br>
            {{ person.office }}
          </address>
        </div>
      </article>
    {% endfor %}
  </div>

  <h2 id="former-group-members" class="people-section-title">Former Group Members</h2>
  <div class="people-alumni">
    <div class="people-alumni-header" aria-hidden="true">
      <span>Name</span>
      <span>Former Role</span>
      <span>Current Position</span>
    </div>
    {% for person in site.data.people.former_members %}
      <article id="{{ person.name | slugify }}" class="people-alumni-row" aria-labelledby="{{ person.name | slugify }}-name" tabindex="-1">
        <h3 id="{{ person.name | slugify }}-name" class="people-alumni-name">{{ person.name }}</h3>
        <div class="people-alumni-role">
          <span class="people-field-label">Former Role</span>
          {{ person.former_role }}
        </div>
        <div class="people-alumni-position">
          <span class="people-field-label">Current Position</span>
          {% if person.current_position_url %}
            <a href="{{ person.current_position_url }}">{{ person.current_position }}</a>
          {% elsif person.current_position %}
            {{ person.current_position }}
          {% else %}
            Not Listed
          {% endif %}
        </div>
      </article>
    {% endfor %}
  </div>

  <h2 id="group-life" class="people-section-title">Group Life</h2>
  <div class="people-photo-strip">
    {% for photo in site.data.people.group_life %}
      <img
        src="{{ photo.image | relative_url }}"
        alt="{{ photo.alt | escape }}"
        width="480"
        height="300"
        loading="lazy"
      >
    {% endfor %}
  </div>
  <a class="people-gallery-link" href="{{ '/gallery/' | relative_url }}">View All Group Photos</a>
</div>
