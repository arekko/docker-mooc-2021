
```bash
docker run -d -it --name ubuntu  ubuntu sh -c 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'`
```

```bash
docker exec -it ubuntu bash
root@d2cac453afcc:/# apt-get update && apt-get install curl
```
