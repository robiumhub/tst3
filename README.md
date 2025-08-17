# tst3

Dev-ready containerized workspace for tst3.

## Quickstart (preferred)

Use the helper scripts:

1) Start dev container (detached):

```
bash scripts/dev-start.sh
```

2) Open a shell (repeat for multiple terminals):

```
bash scripts/dev-shell.sh
```

3) Stop the environment:

```
bash scripts/dev-stop.sh
```

Changes in this repo are live-mounted at /workspace inside the container.

## Alternative (docker compose directly)

```
docker compose up -d
docker compose exec app bash
docker compose down
```
