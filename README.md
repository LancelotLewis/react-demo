# React Demo

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), it's a simple demo purpose [Blocklet](https://www.arcblock.io/en/blocklets) that runs on [ABT Node](https://www.arcblock.io/en/platform).

## Install on my ABT Node

[![Install on my ABT Node](https://raw.githubusercontent.com/blocklet/development-guide/main/assets/install_on_abtnode.svg)](https://install.arcblock.io/?action=blocklet-install&meta_url=https%3A%2F%2Fgithub.com%2Fblocklet%2Freact-demo%2Freleases%2Fdownload%2F0.1.8%2Fblocklet.json)

## Run and debug in the cloud with Gitpod

Click the "Open in Gitpod" button, Gitpod will start ABT Node and the blocklet.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/blocklet/react-demo)

## Run and debug locally

If you have not installed ABT Node locally, you can do it using the following:

```shell
yarn global add @abtnode/cli
```

You can get more details from [Get started with ABT Node](https://www.arcblock.io/en/get-started) page or if you need help installing ABT Node.

Clone the repo and start development using a debug mode ABT Node instance inside this project:

```shell
git clone git@github.com:blocklet/react-demo.git
cd react-demo
yarn
abtnode init --mode debug
abtnode start
blocklet dev
```

### Bundle and Package

(Coming Soon)

### Install to your ABT Node

If you have your own ABT Node and just want to try out this blocklet, simply click the following button to install:
[Install on My ABT Node]()

Or alternatively, you can find install this demo blocklet in [Blocklets Marketplace](https://blocklet.arcblock.io) or from the "Blocklet/Marketplace" menu in your ABT Node console.

## Learn more about ABT Node and Blocklet

- [ABT Node Overview](https://docs.arcblock.io/en/abtnode/introduction/abtnode-overview)
- [Get started with ABT Node](https://www.arcblock.io/en/get-started)
- [ABT Node CLI](https://docs.arcblock.io/en/abtnode/developer/abtnode-cli)
- [Blocklet Development Documents](https://docs.arcblock.io/en/abtnode/developer/blocklet-spec)

## License

The code is licensed under the MIT license found in the
[LICENSE](LICENSE) file.

test
