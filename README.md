# Cyber Security

## Information
- Taksaya Chueanakha (MINT)
- 6602041610038
- s6602041610038@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```


## Running a services
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d #background
```

### PG Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d #background
```

### Apps
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d #background
```