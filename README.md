# TimeTill

A small [Neutralino.js](https://neutralino.js.org/) desktop app that shows the time
remaining between two clock times.

- **From / Until** time inputs; result shown on a retro amber LED-style readout
- Preset chips: `+15m`, `+30m`, `+1h`, `+2h`
- Live clock in the title bar area

## Develop

```sh
npm install -g @neutralinojs/neu
neu update   # fetch the Neutralino runtime binaries (first time only)
neu run      # run locally
```

Prototype: `resources/index.html` also opens fine in a plain browser.

Known issues: chips past midnight leave `Until` blank; `Until` earlier than `From` isn't handled yet.
