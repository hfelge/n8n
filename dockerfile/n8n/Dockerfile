# Dockerfile für n8n (nutzt das offizielle Image als Basis)
FROM docker.n8n.io/n8nio/n8n:latest

# Optionale Basis-Konfiguration (kannst du auch im Compose setzen)
ENV GENERIC_TIMEZONE="Europe/Berlin" \
    TZ="Europe/Berlin" \
    N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS="true" \
    N8N_RUNNERS_ENABLED="true"

# Falls du später eigene Files reinkopieren willst (z.B. custom settings),
# könntest du hier COPY-Befehle ergänzen.
# Beispiel:
# COPY ./config /home/node/.n8n/config