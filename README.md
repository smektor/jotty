

# Create folders and permissions

``` sh
mkdir -p config data/users data/checklists data/notes data/sharing data/encryption cache && sudo chown -R 1000:1000 data/ && sudo chown -R 1000:1000 config/ && sudo chown -R 1000:1000 cache/
```

# start

``` sh
docker compose up -d
```