## XML Schema

Für den Austausch von Metadaten über die Materialien wurde eine
[XML Schema Description](../schemas/hs-oer-lom.xsd) erstellt. Bitte
beachten Sie, dass sie nur vollständig mit dem kleinen begleitenden
[Dokument](../schemas/xml.xsd) ist, das auch für korrekte Validierungen
benötigt wird.

Eigene XML–Dokumente können gegen das XML Schema mit gängigen
Werkzeugen validiert werden, z. B. mit `xmllint`:

`$ xmllint --noout --schema hs-oer-lom.xsd mein-oer-lom.xml`

Wenn Sie das Schema in Ihrem eigenen XML-Dokument referenzieren
möchten, verwenden Sie bitte die folgende URL:

`https://dini-ag-kim.github.io/hs-oer-lom-prpofil/20200116/schemas/hs-oer-lom.xsd`

<section id="xml-schema">

    ## XML Schema

    <pre data-include="../schemas/hs-oer-lom.xsd" data-include-format="text"></pre>

</section>

<section id="schema-addition">

    ## Schema-Ergänzung

    <pre data-include="../schemas/xml.xsd" data-include-format="text"></pre>

</section>
