# Lern-Bericht
Durian
Inamorato, Eisenring; Frey

## Einleitung

In unserem Projekt haben wir eine Webseite erstellt, auf der wir Crocs vermarkten und verkaufen. 

## Was habe ich gelernt?

In diesem Projekt haben wir den Zusammenhang von Margin, Border, Padding und Content gelernt. 

## Beschreibung

Margin, Border und Padding sind alles Begriffe die zur Gestaltung, also im CSS, eine Rolle spielen. Sie bestimmen jeweils, wie viel Abstand ein Objekt zu einem anderen hat. Die unterschiedlichen Begriffe nehmen dabei andere Startpunkte. 
```html
<div>
    <img class ="pic_1" src="picture1.jpeg">

    <img class ="pic_2" src="picture2.jpeg">

</div>

```
In diesem simplen Code haben wir zwei verschiedene Bilder. Wenn wir nun den Abstand zwischen den zwei Bildern genau bestimmen möchten, müssen wir einen CSS Code schreiben. 
Bevor wir das machen, müssen wir uns zuerst fragen, welche Art von Abstand wir überhaupt wollen.


![Bild des Box Modelles](https://blog.hubspot.de/hs-fs/hubfs/Germany/Blog_images/padding-und-margin-ueberblick.png?width=746&height=672&name=padding-und-margin-ueberblick.png)

Dieses Bild, das auch Box-Modell genannt wird, visualisiert sehr gut, wie die unterschiedlichen Begriffe funktionieren. 
Auto steht hierbei für den automatisch generierten Content, in unserem Fall wäre das unser Bild. Der Begriff Padding beschreibt den Innenabstand zu seinem Rahmen. Wenn wir Padding erhöhen, wird der Abstand zu dem Rahmen grösser. 
Border ist hierbei der Rahmen oder die Grenze unseres Bildes. Wenn wir Border erhöhen, wird der Rahmen dicker.
Margin beschreibt den Aussenabstand vom Ende unserer Border zum nächsten Element. Wenn wir Margin erhöhen, wird der Abstand zu dem nächsten Element grösser. 
Die Abstände können bei allen drei Begriffen auf alle vier Seiten festgelegt werden. Dies kann mit top, right, left oder bottom spezifiziert werden. 

Nun haben wir uns entschieden, dass wir unseren Bilder einen 3 % dicken Rahmen und einen Abstand zum nächsten Element von 5 % geben wollen. Das würde im CSS folgendermassen aussehen. 

```CSS
.pic_1{
    border:3%;
    margin:5%;
}
.pic_2{
    border:3%;
    margin:5%;
}

```
So sieht der dazu passende Code aus.
## Verifikation
Der Text erklärt, wie die einzelnen Begriffe funktioniere. Das Bild Visualisiert dies und bildet die Basis der Erklärung. 
Die Code-Beispiele zeigen auf, wie das gesagte Umgesetzt werden kann.
# Reflektion zum Arbeitsprozess


Gut war, dass wir einander geholfen haben, wenn einer nicht weiterkam.  

Schlecht war, dass wir nicht sehr gut koordiniert waren. Ausserdem hat jeder für sich gearbeitet, was zu Schweirigkeiten beim Zusammenfügen des Codes geführt hat. 

**VBV**: Beim nächsten Projekt sind wir in engerem Kontakt und konstantem  Austausch, damit wir besser koordiniert und zusammen arbeiten.
