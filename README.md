# ntnu-torget-notifier

```bash
# Running
FEIDE_USERNAME=abc FEIDE_PASSWORD=abc SLACK_WEBHOOK_URL=https://slack.... EACH_N_SEC=60 node main.js
```

```bash
# Building
docker buildx build -t ntnu-torget-notifier --platform linux/amd64,linux/arm64,linux/arm .
```
