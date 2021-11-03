# typescript-playground

Quickly write and test **Typescript code in IntelliJ**. 

Built in configuration to run code using `ts-node` or compile and
run using `tsc` and `node`.

Entry point is `src/index.ts`

## Commands

All commands should be available from the IntelliJ configurations menu.

### Run

Uses `ts-node` to run and compile code from `src/index.ts`

### Build

Runs `tsc` and outputs files to `dist`

### Start Build

Runs `src/index.js` using node

### Build + Start

Uses the two configurations above to compile then run