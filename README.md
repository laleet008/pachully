# Pachully Extension

This is Pachully VPN extension.

## Prerequisites

- Node v18
- pnpm for package management

## Getting Started

Install the required packages

```
    pnpm install

```

Install husky, see the troubleshoot section in case husky does not work

```
    pnpm prepare
```

To add the extension on your local browser

```
    pnpm run build
```

Go to the browser and load the dist folder which was just built.

### Development Cycle

```
   pnpm run watch
```

Keep in mind if you have which is not chrome or firefox, like brave, you need to find executable
path of your browser and set enviroment variable of it. And, run again development cycle again.
