# README

## Running the project

```bash
docker-compose up
```

## Viewing the site

Navigate to `http://localhost:8123` in your browser.

## Accessing the container

1. Install the Dev Containers extension in VS Code.

2. Run Dev Containers: Attach to Running Container... command in VS Code.

3. Open the folder `/var/www/html2/` in the container.

## Viewing site logs

### All logs

```bash
docker-compose logs -f
```

### Wordpress logs

```bash
docker-compose logs -f wordpress
```

OR

```bash
docker logs -f wordpress-sandbox-wordpress-1
```
