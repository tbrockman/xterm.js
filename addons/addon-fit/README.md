## @jsnix/addon-fit

An addon for [xterm.js](https://github.com/xtermjs/xterm.js) that enables fitting the terminal's dimensions to a containing element. This addon requires xterm.js v4+.

### Install

```bash
npm install --save @jsnix/addon-fit
```

### Usage

```ts
import { Terminal } from "@jsnix/xterm";
import { FitAddon } from "@jsnix/addon-fit";

const terminal = new Terminal();
const fitAddon = new FitAddon();
terminal.loadAddon(fitAddon);
terminal.open(containerElement);
fitAddon.fit();
```

See the full [API](https://github.com/xtermjs/xterm.js/blob/master/addons/addon-fit/typings/addon-fit.d.ts) for more advanced usage.
