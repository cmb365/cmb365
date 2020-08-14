---
layout: default
title: Digitale Selbstverteidigung
permalink: /docs/defence
nav_order: 45
has_children: true
has_toc: false
---

# Digitale Selbstverteidigung

Unter dem Schlagwort der digitalen Selbstverteidigung versteht ...  We envisioneer dynamic platforms and synthesize e-business architectures, always enhancig ubiquitous content to redefine scalable metrics and ultimately serve you with web-enabled ROI. We envisioneer dynamic platforms and synthesize e-business architectures, always enhancig ubiquitous content to redefine scalable metrics and ultimately serve you with web-enabled ROI.
{: .fs-6 .fw-300 } 

---
{% if page.has_children == true %}
## Inhalt
{% assign children_list = site.pages | sort:"nav_order" %}
<ul>
  {% for child in children_list %}
    {% if child.parent == page.title and child.title != page.title %}
    <li>
      <a href="{{ child.url | absolute_url }}">{{ child.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
{% endif %}
---

## Eine kurze Anleitung zur digitalen Selbstverteidigung

Die Wochenzeitung, der Chaos Computer Club Schweiz und der Schweizer Konsumentenschutz haben 2018 eine Broschüre zur digitalen Selbstverteidung veröffentlicht. Die Broschüre kann auf der [Webseite der digitalen Gesellschaft](https://www.digitale-gesellschaft.ch/2018/10/25/eine-kurze-anleitung-zur-digitalen-selbstverteidigung-ratgeber-2/) heruntergeladen werden, von wo auch folgender Text stammt: 


>> «Mit der Seilbahn!» lautete eine häufige Antwort, als der Bundesrat in der Volkszählung von 1980 wissen wollte, wie die BürgerInnen den Weg zur Arbeit zurücklegten. Landauf, landab sabotierten Menschen die Umfrage mit Falschangaben. Sie fürchteten um ihre Privatsphäre. Hätte man sie mit den heutigen Verhältnissen konfrontieren können, wären sie wahrscheinlich in Schockstarre verfallen.

>> Die Datenabsauger in dieser gigantischen staatlich-privatwirtschaftlichen Überwachungsmaschinerie sind uns bestens bekannt: Sie heissen WhatsApp, Gmail, Facebook, Google Docs… Tagtäglich füttern wir sie mit Informationen. Dabei gibt es Alternativen, die uns vor Eingriffen in unsere Privatsphäre besser schützen als die datenhungrigen Konzerne. In der kurzen Anleitung zur Digitalen Selbstverteidigung stellen wir sie vor.

>> Die Alternativen versprechen Anonymität, geben weniger oder keine Daten an Dritte weiter, verschlüsseln Nachrichten, legen den Quellcode offen und schaffen damit Transparenz über die Funktionsweise des Programms. Sie betreiben ihre Server in Staaten mit strengen Datenschutzgesetzen oder sichern Informationen dezentral.

>> Absolute Datensicherheit können auch sie nicht gewährleisten. Aber ihre Nutzung verhindert, dass immer mehr Informationen bei immer weniger Instanzen zusammenfliessen. Und sie helfen uns, die Hoheit über unsere Daten zurückzugewinnen.
