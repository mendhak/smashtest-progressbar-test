
Testing a git repo with smashtest --progress-bar


Bring up the hub. 

```
docker-compose up -d
```

Install node packages

```
npm install
```

Run the smashtest

```
npx smashtest --test-server=http://localhost:4444/wd/hub
```

Stop the hub.

```
docker-compose down
```
