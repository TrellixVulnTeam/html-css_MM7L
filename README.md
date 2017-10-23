![Start Coding](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/start-coding-banner.jpg)

<br>

**Termine:**

2017

> **12.10.** // Kick-Off, IDE, Terminal, Browser, HTML

> **17.10** // Chrome DevTools, HTML, CSS

> **25.10.** // Chrome DevTools, HTML, CSS

<br>

- [Roadmap to become a web developer in 2017](https://github.com/danielhauchler/developer-roadmap)
- [Kollaborative Notizen aus unseren Sessions](https://docs.google.com/document/d/17UVzmxNfac6yb9yI6B0vMZwanRJNC34Tepmt1gZ7-rI/edit)

<br>

## 01 - Entwicklungsumgebung

### IDEs (Integrated Development Environments)

Die [IDE (integrierte Entwicklungsumgebung)](https://de.wikipedia.org/wiki/Integrierte_Entwicklungsumgebung/) sammelt unter einer gemeinsamen Oberfläche die wichtigsten Tools für das Erstellen von Software, wie z.B. [Quelltextformatierung](https://de.wikipedia.org/wiki/Quelltextformatierung), [Syntaxhervorhebung](https://de.wikipedia.org/wiki/Syntaxhervorhebung), [Compiler](https://de.wikipedia.org/wiki/Compiler), [Debugger](https://de.wikipedia.org/wiki/Debugger), [Interpreter](https://de.wikipedia.org/wiki/Interpreter), [Versionskontrolle](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Wozu-Versionskontrolle%3F) und Werkzeuge für das Erstellen von grafischen Oberflächen.

Es gibt viele gute IDEs, die Wahl der Richtigen hängt von eurem Technologie Stack ab. Als Web Entwickler konzetriere ich mich in unseren Start Coding Sessions auf HTML, CSS, JavaScript, Node, PHP, SQL, Git und beliebige Task Runner.
- [Sublime Text](https://www.sublimetext.com/)
- [Adobe Edge Code](http://www.adobe.com/de/products/edge-code.html)
- [Brackets](http://brackets.io/)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [PhpStorm](https://www.jetbrains.com/phpstorm/)
- [Netbeans](https://netbeans.org/)

... sind alles mächtige IDEs!
Für unsere Zwecke empfehle ich im Augenblick den Visual Studio Code von Microsoft.
- [Visual Studio Code](https://code.visualstudio.com/)

Schaut euch Emmet an, ein Plugin für viele gängige Texteditoren, welches den HTML- und CSS-Workflow erheblich verbessert! - in Visual Studio Code schon standardmäßig implementiert.
- [Emmet.io](https://emmet.io/)
- [Emmet Docs](https://docs.emmet.io/)

<br>

### Terminal (Command Line Interface)


Der Terminal, auch als Kommandozeile oder "Command Line" bezeichnet, liefert uns eine Befehlszeilenschnittstelle und textbasierten Zugriff auf unser Betriebssystem.
![Terminal](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/terminal.png)

Betriebssystem basierte Kommandozeilen-Befehle
- [Terminal Cheatsheet for Mac (Basics)](https://github.com/danielhauchler/terminal-mac-cheatsheet)

Ein nützliches Plugin Bundle und Theme für den Terminal
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

<br>

### Git

Open-Source Software zur verteilten Versionsverwaltung, stetiger Protokollierung von Änderungen eurer Dateien/Projekte innerhalb eines "Repositories". Vor allem in der Programmierung dient es dazu die eigenen Änderungen zu überwachen, sie rückgängig zu machen, sie anderen über sogenannte Repos zur Verfügung zu stellen oder Aktualisierungen von anderen einzuholen.

- Die eigene Arbeit kann einfach wieder in die zentrale Basis integriert werden.
- Es kann zeitgleich weiterentwickelt werden, z.B. jeder an verschiedenen Features.
- Die Versionierung verhindert, dass bereits getätigte Arbeiten verloren gehen bzw. überschrieben werden.
- Bei Bedarf kann zu früheren Versionen zurückgekehrt werden oder simultan an verschiedenen Versionen gearbeitet werden (auch "Branches" genannt).

Für die Nutzung muss folgende Software auf eurem Betriebssystem installiert sein:
- [Git](https://git-scm.com/), Download unter [https://git-scm.com/downloads](https://git-scm.com/download/mac).

Folgend Online-Dienste zur webbasierter Versionsverwaltung.

- [GitHub](https://github.com/) 
- [Bitbucket von Atlassian](https://bitbucket.org/) (kostenfreie "Privat" and Public Repositories")

Du befindest dich gerade in einem meiner Ropositorys auf [Github](https://github.com/). Hier aktualisiere, versioniere und teile ich den aktuellen Stand unseres Quellcodes aus den Sessions, sowie diese Doku.

<br>

### Webbrowser

Webbrowser stellen die Benutzeroberfläche für Webanwendungen dar. Ein Computerprogramm zur Visualisierung von Webseiten im World Wide Web basierend auf HTML Dokumenten, Vektor Grafiken, Bildern und PDF-Dokumenten durch Zuhilfenahme von [Cascading Stylesheets](## 03 - CSS (Cascading Style Sheets)). [Browse Happy!](https://browsehappy.com/)

- [Google Chrome](https://www.google.de/chrome/browser/desktop/index.html) (WebKit / V8)
- [Mozilla Firefox](https://www.mozilla.org/de/firefox/) (Gecko)
- [Safari](https://www.apple.com/de/safari/) (WebKit)
- [Internet Explorer](https://www.microsoft.com/de-de/download/internet-explorer.aspx) (Trident)
- [Opera](http://www.opera.com/de/download) (Presto)

Funktionsweisen von Browsern: [Hinter den Kulissen moderner Web-Browser.](https://www.html5rocks.com/de/tutorials/internals/howbrowserswork/)

<br>

### Dev Tools
Google Chrome Developer Tools zum debuggen von Web Applikationen.

'Rechtsklick' + 'Untersuchen/Inspect'

```
cmd + shift + I
```

![Screenshot - Inspect Element](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/devtools.png)

[Paul Irish](https://www.paulirish.com/), amerikanischer Front End und Google Chrome Web Browser Engineer.

<br>

## 02 - HTML (Hypertext Markup Language)

- HTML beschreibt die semantische Dokumentenstruktur von Web Applikationen
- HTML Tags repräsentieren HTML Elemente
- HTML Elemente bilden eine Baumstruktur, auch DOM (Dokumenten-Objekt-Modell) gegannt
- DOM-Elemente bildet Knoten, jeder Knoten bildet ein Objekt
- Objekte repräsentieren Teile des Dokumentes
- Browser nutzen das DOM um Inhalte zu rendern

![DOM-Knoten](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/dom-knoten.png)

[Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/), Wegbereiter des World Wide Webs und Director des World Wide Web Consortiums ([W3C](https://www.w3.org/)).

- [World Wide Web Consortium (W3C)](https://www.w3.org/)
- [World Wide Web Consortium (W3Schools)](https://www.w3schools.com/)

### DOCTYPE

Dateiname:
````
index.html
````

Mit der Dateiendung '.html' definieren wir die Datei als HTML Dokument.

````
<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>
    
</body>
</html>
````

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/01_doctype/index.html)*__

### HEAD
Das Head Element ist ein Container für Metadaten. Metadaten beinhalten Informationen über das HTML Dokument wie z.B. 'character sets', 'styles', 'links', 'scripts'...

- [HTML Elemente für den Head.](https://github.com/danielhauchler/HEAD)

````
<head>
  <meta charset="UTF-8">
  <title>Der einzigartige Titel</title>
  <meta name="description" content="Die einzigartige Beschreibung">
</head>
````
__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/02_html-head/index.html)*__

##### Unicodes and Character Sets
[Unicode](https://wiki.selfhtml.org/wiki/Referenz:HTML/Zeichenreferenz) ist ein internationaler Standard, in dem langfristig für jedes Sinn tragende Schriftzeichen oder Textelement aller bekannten Schriftkulturen und Zeichensysteme ein digitaler Code festgelegt wird. [Character Sets](https://www.w3schools.com/tags/ref_charactersets.asp) (Zeichenkodierungen) erlauben die eindeutige Zuordnung von Schriftzeichen und Symbolen innerhalb eines Zeichensatzes.

- [About unicodes and character sets.](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

```
<meta charset="utf-8">
```

### BODY
Der Body definiert Inhalte von HTML Dokumenten wie Überschriften, Text, Hyperlinks, Bilder, Listen und Tabellen.
- [HTML5 Elemente](https://www.w3schools.com/tags/ref_byfunc.asp)

````
<body>
  <h1></h1>
  <p></p>
  <a href=""></a>      
  <img src="" title="">
  <div>
    <div></div>
  </div>
</body>
````

__*[Sourcecode](https://github.com/danielhauchler/start-coding/blob/master/02-html/03_html-body/index.html)*__

<br>

## 03 - CSS (Cascading Style Sheets)
CSS ist eine Stylesheet-Sprache für elektronische Dokumente mit der Gestaltungsanweisungen erstellt werden.

- [Can i use?](https://caniuse.com/])

### CSS Einbindung
Es gibt verschiedene Wege CSS zu implementieren:

- **Inline Styles** - innerhalb von HTML-Elementen
- **Internal Styles** - im Head des HTML-Dokumentes
- **External Styles** - ausgelagertes Stylesheet in externer CSS-Datei

#### Inline Styles
Inline-Styles sind an ein Element gebunden und können nicht an zentraler Stelle bearbeitet werden. Die Formatdefinition gilt dann nur für den Geltungsbereich des betreffenden HTML-Elements. Innerhalb eines einleitenden HTML-Elements wird das globale Attribut style verwendet. Die Wertzuweisung an das style-Attribut besteht in einer oder mehreren CSS-Formatdefinitionen.
````
  <HTML-Tag style="Formatdefinition-01, Formatdefinition-02"></HTML-Tag>
````
Sinnvoll ist die Verwendung von Inline-Styles, wenn Du sonst auf CSS verzichten möchtest und es nur mal für ein paar Ausnahmen benötigst, oder wenn Du zentrale Formate verwendest, einzelne Elemente aber ausnahmsweise anders gestalten möchtest. Darüber hinaus ist das Injekten von Inline-Styles per Javascript üblich, weiteres hierzu später.

Grundsätzlich solltest du die Verwendung von „Inline-Styles“ meiden, da du keine globalen Änderungen mehr vornehmen kannst und es den Wartungsaufwand erhöht.

Beispiel:
````
<h1 style="color:white;background-color:black">Eine Überschrift</h1>
````
Inline-Styles angewendet auf eine Überschrift ersten Grades in Weiß auf schwarzem Hintergrund.


#### Internal Styles
Hier sind die CSS-Anweisungen im Kopfbereich (Head) des HTML-Dokumentes platziert und haben Auswirkungen auf das gesamte HTML-Dokument.
````
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
        color: white;
        background-color: black;
    }
  </style>
</head>
<body>
  <h1>Eine Überschrift</h1>
</body>
</html>
````
Ein Nachteil von internen Stylesheets ist, dass Änderungen nur die Seite selbt beeinflussen, in der die Styles platziert wurden.


#### External Styles
Eine externe CSS-Datei ist die erste Wahl, wenn mehr als ein HTML-Dokument mit denselben CSS-Regeln formatiert werden soll. Bei der Verwendung von externen Styles werden CSS-Anweisungen in eine externe CSS-Datei (style.css) ausgelagert, welche im Head des Dokumentes über ein link-Tag eingebunden wird.

Inhalt des ausgelagerten Stylesheets:
````
h1 {
    color: white;
    background-color: black;
}
````

Einbindung im Head des HTML-Dokumentes:
````
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" src="css/style.css"
</head>
<body>
  <h1>Eine Überschrift</h1>
</body>
</html>
````

CSS ist nicht auf eine externe CSS-Datei beschränkt. Mit HTML link-Tags und der import-Regel können beliebig viele externe CSS-Dateien eingebunden werden.

Grundsätzlich ist es besser, nicht zu viele CSS-Dateien anzulegen. Jede CSS-Datei wird mit einem HTTP-Request geladen – das kostet vor allem bei den mobilen Geräte zusätzliche Ladezeit für die CSS-Dateien.

Damit eine große CSS-Datei übersichtlich bliebt, helfen ein CSS-Reset, eine strikte Organisation und eine saubere Struktur.

#### Cascading
Wenn CSS-Stile in Konflikt geraten, weil sie extern in der CSS-Datei, im style-Tag, in einer inline-Regel und im Stylesheet des Benutzers unterschiedlich deklariert sind, löst die Kaskade den Konflikt. Die Regel, die dem Element am nächsten liegt, hat die höhere Priorität.

- Eine CSS-Eigenschaft überschreibt die vom Browser vorgegebene Eigenschaft.
- Führen CSS-Stile zu Konflikten innerhalb des globalen Stylesheets, übertrumpft die zuletzt im globalen Stylesheet aufgeführt Anweisung.

![Stylesheet Cascading](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/cascading.png)

### Box Model
### CSS3
#### Flexbox
#### Transitions
#### Transforms / Rotate / Scale
### Responsive Web

<br>

## Nodes
Server

Preprocessors

Sass/Less

Libraries/Frameworks

Bootstrap

Terminal Usage

Javascript

Task Runner

npm

Semantic Web / SEO

HTML Head

grunt / gulp / webpack

module bundler

Version Control/Git

CMS

Tracking

URL Tracking

Event Tracking

Datenbanken

Images (png, jpg, svg)

Ad-Session

<br>

## Assets

### Colors
![Colors](https://raw.githubusercontent.com/danielhauchler/start-coding/master/_assets/media/images/readme/colors.jpg)
```
  #f6f6f6
  #99a0aa
  #4d545d
  #20a3d4
  #05b1b2
  #009899
```
