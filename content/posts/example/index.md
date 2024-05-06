+++
title = "Das Märchen vom bösen Wolf"
date = "2024-03-28"
draft = false
pinned = false
tags = ["Lilo", "Example"]
image = ""
description = "In diesem Artikel werden Möglichkeiten aufgezeigt für das Verfassen von Blogeinträgen."
footnotes = "In der Fusszeile können zum Beispiel Bildquellen angegeben werden. Dieser Text ist abgetrennt durch eine Linie und etwas kleiner."
+++
# Das Märchen vom bösen Wolf

{{<lead>}}
Mit der Wiederansiedelung des Wolfes in der Schweiz entsteht zugleich ein grosser Konflikt zwischen den Bestrebungen der Tierschützer und der Angst und Verzweiflung der Bergbevölkerung. Die Debatte um den Wolf in der Schweiz spitzt sich immer weiter zu.
{{</lead>}}

Nach vier Stunden Zugfahrt kommen wir in Luchsingen im Kanton Glarus an. Die frische Bergluft strömt uns in die Nase. Vor uns bäumen sich die hohen, mächtigen Berge auf, während die Sonne nur vereinzelt durch die Wolken dringt. Das beruhigende Geräusch eines Rassenmähers im Hintergrund begleitet uns auf dem Weg zu unserem heutigen Gesprächspartner. Als wir die gemütliche Wohnung von Reto Glarner betreten, kommt uns der Geruch von frischem Kaffee entgegen. Er ist Herdenschutzbeauftragter im Kanton Glarus und ist in der Bauerngruppe Glarus Süd tätig. Er betreibt einen landwirtschaftlichen Betrieb mit eigenen Tieren. Der Wolf ist auf Gemeindegebiet sehr präsent und hat grossen Einfluss auf den landwirtschaftlichen Betrieb. Wie Reto Glarner sagt: «Es ist einfach eine enorme zusätzliche Arbeit, die man da macht». 

## Bilder

Bilder werden mit dem `+`-Symbol eingefügt.

![]()

- - -

## Lead

{{<lead>}}
Oft haben Artikel unterhalb des Haupttitels einen einführenden Lead, der etwas grösser dargestellt wird.
{{</lead>}}

`{{</*lead*/>}}`\
Ein Lead steht zwischen zwei solchen Blöcken.\
`{{</*/lead*/>}}`

## Kasten

{{<box>}}
In dieser Box können Texte, Bilder, Videos oder andere Inhalte dargestellt werden.
{{</box>}}

`{{</*box*/>}}`\
Der Inhalt einer Box muss wie hier von zwei Blöcken umgeben werden.\
`{{</*/box*/>}}`

{{<box title="Ausklappbare Box">}}
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.

Dies eignet sich auch für längere Inhalte.

![](/img/default-image.jpg)

Auch Bilder können in eine Box gepackt werden.
{{</box>}}

`{{</*box title="Ausklappbare Box"*/>}}`\
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.\
`{{</*/box*/>}}`

## Video, Audio und andere Medien einbetten

Es kann auch `HTML-Code` eingefügt werden. Manchmal geht dies etwas einfacher, wenn man dazu in den `Markdown`-Modus wechselt.

Damit können zum Beispiel Filme, Audiodateien oder Karten eingebettet werden. Meist sind auf den entsprechenden Plattformen (YouTube, Vimeo, Google Maps, etc.) entsprechende Code-Ausschnitte vorbereitet, die man direkt in den Blog einfügen kann. Am besten auf der jeweiligen Plattform nach einem Knopf für `embed` oder `share` suchen.

Bei Videos ist es ideal, wenn sie sich automatisch **an die Bildschirmgrösse anpassen**. Dies geht am einfachsten mit den hinterlegten YouTube- und Vimeo-Codes:

### YouTube einbetten

Einbetten von YouTube-Videos mit dem Code: `{{</*youtube video_id*/>}}`

(Die `video_id` steht bei jedem YouTube-Video in der Browser-URL.)

{{<youtube kQjtK32mGJQ>}}

### Vimeo einbetten

Einbetten von Vimeo-Videos geht mit dem Code: `{{</*vimeo video_id*/>}}`

{{<vimeo 194276412>}}

### Code und Code-Blöcke

Mit dem Code-Symbol `<>` können Wörter auf `diese Art` hervorgehoben werden. Dies wird zum Beispiel für Tastenkombinationen wie `ctrl+s` oder für `Programmiercode` verwendet. Auch Math-Formeln können so ausgedrückt werden: `y = mx + b`.

Für längere solche Abschnitte verwendet man am besten das Code-Block-Symbol. Damit wird ein solcher Block erstellt:

```
const sun1 = "sun" + "il";
const sun2 = "su" + "n" + "il";
sun1 === sun2;
```

## Spass haben

😀 Viel Spass mit deinem Blog!