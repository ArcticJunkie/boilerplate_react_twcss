# integrating different tools and technologies into one project can be troublesome

I'm creating boilerplate repositories that you can clone, get your working version of multiple technologies integrated into one environment (=

This repo contains a working mix of TailwindCSS and React 16.X (you can upgrade/downgrade to any react version in node_modules)

The environment "listens" to changes in the code-base, updating the Tailwind source code in real-time

## Available Scripts

### `npm run start`

sets up a localhost server that listens to any changes in the codebase, including tailwindcss config changes and autoupdates with decent performance (2-3s latency, depending on your system)
