# LingoClashDevServer

## Set up

```
yarn install
yarn run start-auth
```

## Export from firestore

npx -p node-firestore-import-export firestore-export -a credentials.json -b firestore_backup.json

## Import to firestore

npx -p node-firestore-import-export firestore-import -a credentials.json -b firestore_backup.json
