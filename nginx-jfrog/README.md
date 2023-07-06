# This compose create a working jfrog artifactory oss app behind nginx proxy

To use it, run:
```bash
docker-compose -f compose.yml up
```
Or to remove it, run:
```bash
docker-compose -f compose.yml down
```

Wait a moment (up to 5min), open web browser at http://localhost
You should now redirect to http://localhost/ui/login (artifactory url)
