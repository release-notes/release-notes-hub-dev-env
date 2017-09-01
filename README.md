# Release Notes Hub dev setup

A docker compose setup for hacking the [release notes hub][ReleaseNotesHub]

## Installation

Make sure you have [docker compose][InstallDockerCompose] installed.

```sh
$ git clone git@github.com:release-notes/release-notes-hub.git
$ git clone git@github.com:release-notes/release-notes-hub-dev-env.git
$ cd ./release-notes-hub-dev-env
$ docker-compose up -d
```

[InstallDockerCompose]: https://docs.docker.com/compose/install
[ReleaseNotesHub]: https://github.com/release-notes/release-notes-hub
