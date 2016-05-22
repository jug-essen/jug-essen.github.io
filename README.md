# JUG Essen Blog

## Use Cases

# Einen Blog Post schreiben

Erzeugt einfach einen neuen Blog Post in `_posts`. Dieser kann in Markdown geschrieben werden.
Die Namenskonvention für die Blogposts seht ihr an den existierenden.
Ihr solltet mindestens 2 Werte als Frontmatter eintragen.
Frontmatter wird mit `---` begonnen und beendet.

Die wichtigen Werte sind:

* categories
* author

Der Autor sollte einem Eintrag in `_authors` entsprechen (entsprechend dem
username Attribute im Frontmatter). Damit stellt ihr die Verknüpfung zur
[Autorenseite](#Autorenseite) 

## Autorenseite

Unter `_authors` kann für jeden Sprecher / Autor / ... eine Autorenseite
angelegt werden. Eine Autorenseite besteht aus strukturieten Attributen im
Frontmatter und einem Freitext.

* title
  Name des Users
* username
  Identifizierender username. Konvention: vorname.nachname
* email
  Optional. Kann agegeben werden
* website:
  Optional. Eigene Webseite des Autors, Sprechers, ...
* picture
  Name des Autorenfotos. Ablegen unter `img/authors`.
* social
  twitter, github, stackovervflow, facebook, xing, lanyrd accounts des users.
* topics
  Yaml Liste der Themen, mit denen sich der Autor, User, ... beschäftigt

## Events

Um einen neuen Event anzulegen, muss unter `_events` ein neues "Event" angelegt
werden.

## Titelstories

Um einen Blog Post auf der Homepage zu zeigen, muss dieser im Frontmatter das
Attribut `coverstory` auf true gesetzt bekommen:

```
---
coverstory: true
---
```

Dabei werden aber aktuell nicht mehr als 2 Coverstories angezeigt und zwar die
neuesten zu erst.

## Credits
Dieser Blog nutzt das [Creative Theme](http://startbootstrap.com/template-overviews/creative/) template von [Start Bootstrap](http://startbootstrap.com).
See it live in action at <https://volny.github.io/creative-theme-jekyll/>


