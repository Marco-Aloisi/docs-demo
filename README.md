# docs-demo

Questo repository è un esempio di documentazione costruita con MkDocs e il tema Material.

## Eseguire in locale (Python virtualenv)

1. Crea un ambiente virtuale e attivalo:

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Installa le dipendenze:

```bash
pip install -r requirements.txt
```

3. Avvia il server di sviluppo:

```bash
mkdocs serve
```

Il sito sarà disponibile in http://127.0.0.1:8000/

## Eseguire con Docker Compose (locale)

All'interno della cartella `local/` è presente un `docker-compose.yml` e un `Dockerfile` per eseguire MkDocs in un container.

1. Costruisci ed avvia i servizi:

```bash
docker compose up --build
```

2. Il server di sviluppo sarà esposto sulla porta 8000 di localhost.

Il compose monta la cartella del progetto nel container per abilitare il live-reload durante lo sviluppo.

## File utili

- `mkdocs.yml` - configurazione del sito
- `docs/` - contenuti markdown
- `requirements.txt` - dipendenze Python per MkDocs
- `local/` - setup Docker Compose per esecuzione locale

---

Creato da Marco Aloisi.
# docs-demo