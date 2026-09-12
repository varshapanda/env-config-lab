# Cloud Run Configuration Mapping

## Service

`env-config-lab`

## Configuration Variables

These are non-secret configuration values and can be supplied using Cloud Run environment variables.

| Variable | Type | Source |
|---|---|---|
| `LOG_LEVEL` | Non-secret configuration | Cloud Run environment variable |
| `PORT` | Non-secret configuration | Cloud Run/runtime configuration |

Example:

```bash
gcloud run deploy env-config-lab \
  --set-env-vars LOG_LEVEL=info