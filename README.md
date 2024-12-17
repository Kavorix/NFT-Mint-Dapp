# Rage Trade

Rage is a liquidity and treasury management protocol.

## Usage

1. Clone this project:

```sh
git clone https://github.com/Kavorix/rage-trade
```

2. Change into the directory:

```sh
cd rage-trade
```

3. Install the dependencies:

```sh
npm install
```

4. Set up some configurations:

Set the values of environment variables in the `.env.development`, `.env.production`, and `.env` files to yours.

5. Add your **ABI**:

Copy your contract **ABI** from the [Remix](https://remix.ethereum.org/) and paste it into `contract/abi.json`.

6. Run the server:

```sh
npm run dev
```