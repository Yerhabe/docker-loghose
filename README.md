# logprett

Collect all the logs from all docker containers and prettify. For use with the Bunyan logger.

## Docker Usage

```bash
docker run -it --rm -v /var/run/docker.sock:/var/run/docker.sock yerhabe/logprett
```

## Data format

![bunyan CLI screenshot](https://raw.github.com/trentm/node-bunyan/master/tools/screenshot1.png)

Notes
----------------

Please note that this container must be run with the `-it` flag to ensure that the coloring is passed to stdout properly.


## License

MIT
