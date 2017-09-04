# gearmand

`paladintyrion/gearmand` packages recent versions of gearmand using Alpine Linux as the base image.

## Supported tags and respective `Dockerfile` links

- [`1.1.16-alpine`, `latest` (*Dockerfile*)](https://github.com/paladintyrion/docker-gearmand/tree/master/1.1.16/Dockerfile)

## Supported gearmand backends

- `builtin` (default)

## Usage

Print help:

```bash
docker run -d -v /data0/log/supervisor:/data0/log/supervisor -v /data0/gearmand:/data0/gearmand paladintyrion/docker-gearmand:latest
```

You can also inject a new version of `/etc/gearmand.conf` as needed. See the [default](https://github.com/paladintyrion/docker-gearmand/blob/master/1.1.16/gearmand.conf).
