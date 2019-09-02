# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

1- Seite nur für mobile
2- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
3- Link für Email, der E-Mail Anwendung öffnet (0/5)
4- Link für Telefon, der Telefon-Anwendung öffnet (0/5)
5- Link zum Lebenslauf(PDF), der einen Download auslöst (0/5)
```diff
- Es gibt hier keine Links
```
6- Links zu Social Media Profilen
  *- Haben Icons der Dienste (10/10)
  **- Sollen in einem neuen Tab öffnen (0/5)
```diff
- Es gibt hier keine Links
```
  
7- Foto, das im Kreis dargestellt wird, mit border-radius (0/5)
8- Navigation zu den Abschnitten mit Hash-Links (6/10)
```diff
- Das funktioniert. Aber es sollten keine a-Tags in button-Tags sein
```
9- Bilder im Portfolio sollen verlinkt sein (0/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
```diff
- bitte keine headings(h1, h2, h3, h4,...) in p-Tags
```
- Padding in den Links der Hauptnavigation (0/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (4/10)
```diff
- Vor allem die Links ganz unten sind viel zu nah aneinander, da sollte Abstand im CSS definiert werden.
```
- Korrekte html-Grundstruktur (html, head, body) (10/10)
- Keine Viewport-Elemente im head (5/5)

### Punkte
SUMME (**45**/100)
