# Supported tags and respective `Dockerfile` links

- `lastest`, `7.4`, `7` [(*Dockerfile*)](https://github.com/bezeklik/docker-centos/blob/master/Dockerfile)
- `6.9`, `6` [(*Dockerfile*)]()
- `5.11`, `5` [(*Dockerfile*)]()

# Quick reference

- **Where to get help:**

- **Where to file issues:**

https://github.com/bezeklik/docker-centos/issues

- **Maintained by:**

[Bezeklik](https://github.com/bezeklik/)

- **Supported architectures:**

- **Published image artifact details:**

- **Image updates:**

- **Source of this description:**

- **Supported Docker versions:**

# Difference from the official image

- Delete unnecessary packages for Docker

- 2017/3/31 に EOL を迎え、ミラーサーバーから yum リポジトリが削除された CentOS 5.11 で yum を使えるようにしている。

- CentOS Linux 5 has reached End of Life, as of 31 March 2017.

# How to use this image

## Usage

```
docker run --interactive --tty --name centos bezeklik/centos bash
```

# License

View [license information](https://github.com/bezeklik/docker-centos/blob/master/LICENSE) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `centos/` directory](https://github.com/docker-library/repo-info/tree/master/repos/centos).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
