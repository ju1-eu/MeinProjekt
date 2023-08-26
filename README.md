# README

update: 26-8-23

Das Skript `git_hilfsprogramm.py` scheint ein Hilfsprogramm für Git zu sein, das eine Benutzeroberfläche im Terminal bietet, um verschiedene Git-Aufgaben durchzuführen. Ich werde es jetzt detailliert beschreiben:

### Beschreibung:

Das Skript bietet eine Reihe von Funktionen, um mit Git zu interagieren:

1. **lokales_repo_erstellen_und_initialisieren**: Erstellt ein lokales Repository und initialisiert es. Es überprüft auch, ob eine `.gitignore`-Datei vorhanden ist und erstellt sie, falls nicht.
2. **lokales_repo_mit_github_verknüpfen**: Verknüpft ein lokales Repository mit einem GitHub-Repository.
3. **änderungen_hinzufügen**: Fügt Dateien/Änderungen zur Git-Staging-Area hinzu.
4. **änderungen_commiten**: Committet Änderungen im lokalen Repository.
5. **änderungen_pushen**: Pusht Änderungen von einem lokalen Repository zu GitHub.
6. **änderungen_pullen**: Holt Änderungen von GitHub und führt einen Merge im lokalen Repository durch.
7. **repository_klonen**: Klont ein GitHub-Repository.
8. **branch_erstellen**: Erstellt einen neuen Git-Branch.
9. **branch_wechseln**: Wechselt zwischen Git-Branches.
10. **branches_auflisten**: Listet alle verfügbaren Git-Branches auf.
11. **merge_branch**: Führt einen Git-Branch in einen anderen ein.
12. **stash_änderungen**: Verwendet den Befehl `git stash` um Änderungen temporär zu speichern.
13. **konflikte_anzeigen**: Zeigt Git-Konflikte an.
14. **pull_requests_auflisten**: Listet alle verfügbaren Pull-Requests auf (dies erfordert möglicherweise zusätzliche Konfiguration oder Abhängigkeiten).
15. **gitignore_anzeigen**: Zeigt den Inhalt der `.gitignore`-Datei an.
16. **gitignore_verwalten**: Verwaltet Einträge in der `.gitignore`-Datei.
17. **log_anzeigen**: Zeigt den Git-Log an.
18. **status_anzeigen**: Zeigt den Git-Status an.
19. **github_repositorys_anzeigen**: Listet alle GitHub-Repositories des Benutzers auf (dies erfordert möglicherweise zusätzliche Konfiguration oder Abhängigkeiten).
20. **github_repository_löschen**: Löscht ein GitHub-Repository (dies erfordert möglicherweise zusätzliche Konfiguration oder Abhängigkeiten).
21. **Beenden**: Beendet das Programm.

### Benutzung:

Um das Skript zu verwenden, führen Sie es mit Python aus und geben Sie den Ordnernamen als Argument an:

```
python3 git_hilfsprogramm.py MeinProjekt
```

Nachdem das Skript gestartet ist, zeigt es ein Menü mit den oben beschriebenen Optionen an. Der Benutzer kann eine Option auswählen, indem er die entsprechende Nummer eingibt.

### Hinweis:

Einige Funktionen des Skripts können von externen Bibliotheken oder Tools abhängen (z.B. `requests` oder `gh`), die installiert sein müssen, damit das Skript ordnungsgemäß funktioniert.

Es scheint auch, dass dieses Skript speziell für einen Benutzer namens "ju1-eu" auf GitHub konfiguriert ist. Falls Sie ein anderer Benutzer sind, müssen Sie möglicherweise die `GITHUB_URL`-Variable im Skript ändern.