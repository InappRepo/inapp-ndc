# inapp-ndc
#Repository INAPP che alimenta il National Data Catalog https://www.schema.gov.it.

# Asset per il catalogo nazionale della semantica dei dati
Questo è il repository INAPP per l'alimentazione del National Data Catalog (NDC): https://www.schema.gov.it/.
Esso contiene il vocabolario controllato ...Theasaurus... 
Il catalogo nazionale della semantica dei dati, o NDC, consente:
> "Ricerca e riuso di asset semantici, tra cui ontologie, schemi dati e vocabolari controllati per supportare lo sviluppo di API semanticamente e sintatticamente interoperabili"

## Organizzazione delle informazioni

I file presenti in questo repository sono organizzati secondo la seguente alberatura:

```bash
┌─ assets/controlled-vocabularies/
│  |
│  ├─ latest
│  │
│  ├─ v{version} 
│  ├─ ... 
│  └─ notes.md
├─ README.md
└─ publiccode.yaml
```

Ontologie e [vocabolari controllati](https://www.agid.gov.it/it/dati/vocabolari-controllati) sono documenti [RDF](https://www.w3.org/RDF/) serializzati in formato [TURTLE](https://www.w3.org/TR/turtle/) mentre gli schemi  [Open Api 3 (OAS3)](https://spec.openapis.org/oas/v3.1.0) sono serializzati in formato [YAML](https://yaml.org/).
