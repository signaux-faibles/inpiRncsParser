# inpiRncsParser
CLI pour convertir les bilans INPI/XML en csv ou json

## Installation
Testée avec `go 1.16.2` et `go 1.17`
```
go get github.com/signaux-faibles/inpiRncsParser@latest
```

## Utilisation
```
~/go/bin/inpiRncsParser $yourRef < yourFile.xml
```

$yourRef permet d'introduire une clé `reference` dans le JSON de sortie pour aider le traçage des traitements.
