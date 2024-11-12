**Anleitung Export Umfrage**

1. In LimeSurvey, gehe zu "Antworten" -> "Antworten & Statistik"
2. Gehe zu "Export" -> "Ergebnisse für externe Anwendungen exportieren"
3. Wähle als Export-Format "CSV" und bei den Spalten nur die relevanten Antworten (von "A1 - Wie alt bist du?" bis "GE24[SQ007] - Bitte bewerte folgende A...eams empfehlen." -> insgesamt 61 Spalten) aus
4. Wähle bei Komplettierungsstatus "Nur komplette Antwortsätze" und bei Überschriften "Fragecode" aus
5. Klicke auf Export und benenne die Datei als "Export_Umfrage_[DD.MM.JJJJ]" (z.B. "Export_Umfrage_11.11.2024")
6. Lade diese Datei in den Ordner "Input"
7. Öffne "AFE2.ipynb" in Google Colab, füge den Raw URL der Datei hin, welche du transformieren möchtest, und führe den Code aus
8. Nach der Trasnsformation wird die neue Datei automatisch heruntergeladen. Lade diese in the Ordner "Output" hoch
