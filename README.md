# saskia_hugo

Öffentliche Website für Saskia Kaiser.

Die Website wird mit [HUGO](https://gohugo.io) und Template [Massively](https://themes.gohugo.io/hugo-theme-massively/) 
(ursprünglich von [HTML5UP](http://html5up.net/)) gebaut.

Content Management erfolgt mittels [Forestry](https://forestry.io). 

Forestry deployed bei jedem git-push eine neue Version auf github Pages ([github.io](https://github.io)).
Die custom domain [saskiakaiser.ch](https://saskiakaiser.ch) und das Server Cert sind auf github Pages registriert.
Siehe auch Datei CNAME im static Verzeichnis.


*ACHTUNG:*

nach einem Update mit Deployment aus Forestry funktioniert des Setzen der Custom Domain noch nicht. Der Zugriff auf die produktive Site saskiakaiser.ch endet dann in einem 403 Fehler. In dieser Situation muss in den github Settings die Custom Domain manuell auf saskiakaiser.ch gesetzt werden. Nach einigen Minuten erscheint dann die Website wieder. Es scheint ein Fehler mit dem CNAME-File zu sein, das noch behoben werden muss.
