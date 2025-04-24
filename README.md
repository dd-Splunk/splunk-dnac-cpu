# Splunk Feinstaub

Using GH Actions to release `.spl`

## Starting the Splunk environment

Create an `.env` file with the following variables:

```ìni
SPLUNK_PASSWORD="Your Super Secret Admin Password"
```

Then start the container:

```bash
docker compose up -d
```

and login to the [instance](http://localhost:8000/)
