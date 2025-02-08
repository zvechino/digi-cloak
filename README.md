# Digi-Cloak

A web app that hides secrets in plain sight securely in images with the help of AES encryption and LSB steganography technique.

Live version is deployed at [https://kaushalmeena.github.io/digi-cloak/](https://kaushalmeena.github.io/digi-cloak/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

### Requirements

To install and run this project you need:

- [Node.js](https://nodejs.org/ "Node.js")
- [yarn](https://classic.yarnpkg.com/lang/en/docs/install/ "yarn") 
- [git](https://git-scm.com/downloads "git") (only to clone this repository)

### Installation

To set up everything in your local machine, you need to follow these steps:

sudo apt update 

Clone this repo and then change directory to the `digi-cloak` folder:

```bash
git clone https://github.com/kaushalmeena/digi-cloak.git
cd digi-cloak
```

Install project dependencies using npm:

curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -

sudo apt install -y nodejs

## check versions

node -v
npm -v

## Install Yarn

sudo corepack enable

sudo corepack prepare yarn@stable --activate

```bash
sudo yarn install
```

### Running

To run the project simply run:

```bash
sudo yarn run ng serve --host 0.0.0.0
```

Your app should now be running on [localhost:4200](http://localhost:4200/).
"ip a" to check the VM IP and use for example http://192.168.99.8:4200/#/

