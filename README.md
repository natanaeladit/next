## Run

```bash
npm run dev
```

## Run docker

```bash
docker build -t nextjs-ui .
docker run -d --name nextjsui -p 3000:3000 nextjs-ui
```

## Exec to running container

```bash
docker exec -it nextjsui /bin/sh
```

## nextjs + nginx

```bash
docker-compose up -d
```