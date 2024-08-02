# Infografik Anlageneffizienz & Dekarbonisierung

## Demo

- [Blaue Variante](/demo-blue.html)
- [Orange Variante](/demo-orange.html)

## Assets

Hier könnt ihr die Dateien herunterladen:

- [Blaue Variante](https://github.com/mayaherbst/decarb-efficiency-svg-demo/tree/main/blue)
- [Orange Variante](https://github.com/mayaherbst/decarb-efficiency-svg-demo/tree/main/orange)

Bitte ladet sie herunter und hostet sie selber, GitHub mag es nicht, wenn man sie als CDN verwendet.

## Einbettung

Die JS und CSS files im `<head>` einbinden:

```html
<head>
  ...

  <script type="module" crossorigin src="<Pfad zur JS Datei>"></script>
  <link rel="stylesheet" crossorigin href="<Pfad zur CSS Datei>" />
</head>
```

An der Stelle, wo die Grafik dargestellt werden soll, einen leeren Container mit der Klasse `dcb-container` erstellen:

```html
<div class="dcb-container"></div>
```

Fertig!
