# 🪲 My Libraries

Created by [`Abolade Greatness`](https://github.com/thegrtnx)

## 👌 Requirement

Node.js should be installed in your system. If not, you can download and install from [`Node.js Website`](https://nodejs.org/en/download)

## 🔧 Installation

Install the required modules:

```bash
npm install

```

## ⏲️ Execute

- To compile :

```bash
 npm run build

```

## 🛠️ Project Build

This project includes build scripts for both CommonJS and ECMAScript modules.

#### CommonJS Build

To compile the CommonJS module, use the following script:

```bash
npm run build:commonjs
```

This script utilizes the TypeScript compiler with the -m commonjs flag.

#### ECMAScript Module Build

To compile the ECMAScript module, run the following script:

```bash
npm run build:esm
```

This script uses the TypeScript compiler with the [`-m esnext --outDir dist/esm`] flags.
The [`--outDir`] flag specifies the output directory for the ECMAScript module.

## ▶️ Start the application

To compile and start the application:

```bash
 npm start

```

- Type 1 to run application in CommonJS
- Type 2 to run application in ESM

## 👋 Issues and Contributions

You can submit issues [here](https://github.com/thegrtnx/internet-speed-check/issues) - your feedback and contributions are welcome!
