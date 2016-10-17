# What is CPUMiner-Multi?

CPUMiner-Multi is a multi-threaded CPU miner, [Wolf](//github.com/wolf9466)'s fork of [LucasJones](//github.com/lucasjones)' cpuminer-multi.

Currently supported algorithm is cryptonight.

## Links

- [Discussion](https://bitcointalk.org/index.php?topic=632724)
- [Source Code](https://github.com/wolf9466/cpuminer-multi)
- [Dockerfile](https://github.com/minecoins/docker-wolf-cpuminer-multi)

# How to use this image

Run in background:

```console
$ docker run -d --name some-wolf-cpuminer-multi minecoins/wolf-cpuminer-multi -a cryptonight -o stratum+tcp://mine.moneropool.com:3333 -u 49TfoHGd6apXxNQTSHrMBq891vH6JiHmZHbz5Vx36nLRbz6WgcJunTtgcxnoG6snKFeGhAJB5LjyAEnvhBgCs5MtEgML3LU -p x
```

Get wolf-cpuminer-multi options with:

```console
$ docker run --rm minecoins/wolf-cpuminer-multi --help
```

Fetch logs of a container:

```console
$ docker logs some-wolf-cpuminer-multi
```

# Donations

Donations for work on dockerizing are accepted at:

- BTC: `1NUMFM6UTv9iRVVzjsfhzbAGjwNxQRA8Qz`
- XMR: `49TfoHGd6apXxNQTSHrMBq891vH6JiHmZHbz5Vx36nLRbz6WgcJunTtgcxnoG6snKFeGhAJB5LjyAEnvhBgCs5MtEgML3LU`
