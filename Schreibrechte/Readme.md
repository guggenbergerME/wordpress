# Schreibrechte bei Problemen

Ändern der Ordner Rechte

```
find . -type f -exec chmod 644 {} \;
```
und
```
find . -type d -exec chmod 755 {} \;
```
