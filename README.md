# Continuous Integration

```
docker-compose up
docker-compose down

docker run --rm -itv $(pwd):/app -w /app golangci/golangci-lint golangci-lint run controllers/ database/ models/ routes/
echo $?

docker-compose up -d
docker-compose exec app go test main_test.go

sudo apt install build-essential

make lint
make test
make start

make ci
```