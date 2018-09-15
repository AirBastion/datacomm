# Reaction Commerce

Preferred method update for our core application.

To get the latest updates via:
`git pull --recurse-submodules`


### Install and create your first store

First,

```bash
git clone https://github.com/AirBastion/reaction.git
cd reaction
git  submodule update --init --recursive
```

Now install dependencies via the cli tool.

```bash
npm install -g reaction-cli
```

Create your store:

```bash
reaction init
cd reaction
reaction
```

You can also run the app locally using [`docker-compose`](https://docs.docker.com/compose/) by running:

```sh
docker-compose up
```

This will use the `docker-compose.yml` file. This can be used to evaluate the app locally (on all Operating Systems supported by Docker),
however, for active local development or customization, it is better to run `reaction` outside of Docker for faster app builds.

Learn more on how to [configure your project](https://docs.reactioncommerce.com/reaction-docs/master/configuration).
