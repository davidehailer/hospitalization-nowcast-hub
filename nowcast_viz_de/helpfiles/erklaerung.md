### Erklärung der Bedienelemente

- **Datenstand:** Wählen Sie ein Datum in der Vergangenheit, um die Nowcasts, die zu diesem Zeitpunkt gemacht wurden anzuzeigen. Dies ermöglicht den Abgleich vergangener Nowcasts mit später angefallenen Daten.
- **Stratifizierung**: Nowcasts können für ganz Deutschland, pro Bundesland oder pro Altersgruppe gezeigt werden.
- **Zeitreihe eingefrorener Werte**: Eine weitere Alternative besteht darin, für jedes Meldedatum die 7-Tage-Hospitalisierungsinzidenz gemäß des Datenstandes am jeweiligen Datum zu zeigen. Hierdurch sind alle gezeigten Werte ähnlich unvollständig und somit besser über die Zeit hinweg vergleichbar.
- **Zeige letzte zwei Tage**: Für die letzten zwei Tage sind Nowcasts wenig zuverlässig, da nur ein kleiner Teil der Hospitalisierungen zu diesem Meldedatum bereits gemeldet ist. Nicht alle Modelle produzieren Nowcasts für diese Tage, und standardmäßig blenden wir sie nicht ein.
- **Zeige Übersichtstabelle**: Zeigt eine Übersichtabelle, in der für ein gewähltes Modell und Meldedatum die Nowcasts für alle Bundesländer oder Altersgruppen aufgeführt werden. Die Tabelle zeigt die 7-Tages-Inzidenz gemäß des aktuellsten Datenstandes und des Datenstandes basierend auf dem der Nowcast erstellt wurde, den Nowcast, den resultierenden Korrekturfaktor und die Veränderung zur Vorwoche gemäß des Nowcasts.

**Weitere Optionen:**

- **Anzeige**: Daten und Nowcasts können auf einer logarithmischen oder natürlichen Skala gezeigt werden. Exponentielles Wachstum oder Rückgang entsprechen auf einer logarithmischen Skala einer Geraden. Außerdem kann zwischen absoluten Zahlen und Zahlen pro 100.000 gewählt werden. Letzteres macht Werte z.B. über verschiedene Bundesländer hinweg besser vergleichbar.
- **Punktschätzer**: Es kann entweder der Erwartungswert oder der Median angezeigt werden (der Median ist der Wert für den gilt: Der wahre Wert liegt mit 50% Wahrscheinlichkeit darunter und mit 50% Wahrscheinlichkeit darüber).
- **Vorhersageintervall**: Soll ein Vorhersageintervall mit angezeigt werden? 95% Vorhersageintervalle sollen den wahren Wert mit 95% Wahrscheinlichkeit enthalten, 50% Vorhersageintervalle mit 50%. In der Praxis sind die wahren Werte oft seltener enthalten als gewünscht.
- **Zeitreihe nach Erscheinen in RKI-Daten**: Eine Alternative zum Nowcast der Hospitalisierungsinzidenz nach Meldedatum (Datum, an dem der erste positive Test einer Person an das lokale Gesundheitsamt gemeldet wurde) ist es, Hospitalisierungszahlen nach ihrem Auftauchen im Datensatz des RKI zu aggregieren. Diese Zahlen ändern sich in den darauffolgenden Tagen nicht mehr, sodass Trends einfacher zu interpretieren sind.
- **Nachträglich erstellte Nowcasts zeigen**: Zu Forschungszwecken sammeln wir auch Nowcasts, die erst nachtröglich, aber basierend auf dem jeweiligen Datenstand erzeugt wurden. Um Verwechslung mit in Echtzeit produzierten Nowcasts zu vermeiden zeigen wir sie standardmäßig nicht an.
