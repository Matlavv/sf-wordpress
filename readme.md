# Comment installer le projet ?

## Lancez un conteneur

```
docker-compose up -d
```

## Installer les dépendances wordpress

```
npm -g install @wordpress/env
wp-env start
```

### Then run

```
http://localhost:8888
```

### Connect in admin

```
http://localhost:8888/wp-admin
```
