## Thus, an example of a ready-made command to start one module (container) looks like this:


```
docker run -d --restart unless-stopped --pull always --name exorde-cli_1 exordelabs/exorde-cli -m 0x16f177263988fF6fc8999013BD9bCB70F39b42d3 -l 2
```

```
docker ps -a
```
```
docker restart
```
```
docker logs --follow
```
