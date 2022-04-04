# NFT Generator

## Moralis video tutorials

Aim: Save time and resources for artists and developers by allowing them to generate and host NFT art, across blockchains, in one place (utilising Moralis).

These tutorial videos are a great introduction.
Part 1: [Link to Moralis YouTube Video](https://youtu.be/KBV4FrCv4ps)
Part 2: [Link to Moralis YouTube Video](https://youtu.be/FcH7qXnOgzs)

## Quick Launch 🚀

Via terminal, navigate to root directory:

```sh
npm install

```

Go to [Moralis.io](https://moralis.io/) to create your server instance. Then rename .env-example file to .env and add your Moralis server credentials.

_Note_: To find your xAPI key: https://deep-index.moralis.io/api-docs/#/storage/uploadFolder

Create your layered artwork and split into folders in `./input` and configure your collection to match your layer structure and preferences accordingly by editing `./input/config.js`:

Finally, via terminal in the project directory run:

```sh
node index.js

```

## Config

- Make individual folders in the input folder for every layer.
- Now add all these folder names in the layers array in the `config.js` file.
-
