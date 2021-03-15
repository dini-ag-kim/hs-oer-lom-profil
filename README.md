# LOM for Higher Education OER Repositories

Verschiedene Hochschulrepositorien deutscher Bundesländer haben sich zum Ziel
gesetzt, ihre frei verfügbaren Materialien vernetzt zugänglich zu machen. Für
den Austausch von Metadaten über die Materialien wurde eine XML Schema Description
erstellt. Das Schema basiert auf LOM, wurde aber konsequent reduziert auf die
für die Repositorien notwendigen Metadaten.

## Maintainer\*innen

[Michael Menzel](https://github.com/mic-men) und [Adrian Pohl](https://github.com/acka47)

## Versionen der Spezifikation

Die aktuelle Fassung der Spezifikation findet sich unter folgendem Permalink:

[`https://w3id.org/kim/hs-oer-lom-profil/latest/`][latest_version]

Dieser Permalink führt immer zur jeweils aktuellsten publizierten Version der
Spezifikation. Zur Implementierung der Spezifikation sollte immer diese Fassung
herangezogen werden.

Ältere Fassungen der Spezifikation und konkrete Versionen können ebenfalls über
Permalinks referenziert werden. Dazu muss die Pfadangabe `latest` im obigen Link
durch die jeweilige Versionnummer ersetzt werden.

Bisher wurden folgende Versionen veröffentlicht:

- [`latest`][latest_version] (Aktuelle Version vom 28.02.2020)
- [`20200228`][20200228] (Version vom 28.02.2020)
- [`20200116`][20200116] (Version vom 16.01.2020)


## Lokales Setup

Um die `index.html`-Datei lokal editieren und anzeigen zu können, klone das Repo und wechsle in das `hs-oer-lom-profil`-Verzeichnis:

`git clone git@github.com:dini-ag-kim/hs-oer-lom-profil.git ; cd hs-oer-lom-profil`

Lasse einen Server im `hs-oer-lom-profil`-Verzeichnis laufen:

`python3 -m http.server`

Dann lässt sich die Spezifikation im Web-Browser anschauen unter [http://localhost:8000](http://localhost:8000).

## Mitwirkung

In der Entwicklung der Spezifikation nutzen wir die [StöberSpecs](https://w3id.org/kim/stoeberspecs/)-Werkzeuge und -Prozesse.
Die redaktionelle Arbeit erfolgt auf [GitHub][https://github.com/dini-ag-kim/hs-oer-lom-profil]. Dort kann der jeweils
aktuelle Arbeitsstand eingesehen werden und Verbesserungsvorschläge eingebracht
werden. Zudem kann der aktuelle Arbeitsentwurf der Spezifikation unter folgendem
Permalink betrachtet und kommentiert werden:

[`https://w3id.org/kim/hs-oer-lom-profil/draft/`][draft_version]

Zur Kommentierung kann entweder der in die [Entwurfsfassung][draft_version]
eingebundene Annotationsdienst [hypothes.is](https://web.hypothes.is/) (siehe
rechte Spalte) oder die [Kommentarfunktion von GitHub][multi-line comments]
([Beispiel](https://github.com/dini-ag-kim/hs-oer-lom-profil/blob/master/draft/index.html#L122-L126))
verwendet werden.

[latest_version]: https://w3id.org/kim/hs-oer-lom-profil/latest/
[20200228]: https://w3id.org/kim/hs-oer-lom-profil/20200228/
[20200116]: https://w3id.org/kim/hs-oer-lom-profil/20200116/
[draft_version]: https://w3id.org/kim/hs-oer-lom-profil/draft/
[github]: https://github.com/dini-ag-kim/hs-oer-lom-profil/
[multi-line comments]: https://help.github.com/en/github/managing-your-work-on-github/opening-an-issue-from-code
