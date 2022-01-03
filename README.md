# Inkdrop Power Plugin

> Inkdrop plugin that turns on power mode

![](https://inkdrop-plugin-badge.vercel.app/api/version/power) ![](https://inkdrop-plugin-badge.vercel.app/api/downloads/power) ![](https://img.shields.io/github/license/Luke-1220/inkdrop-power?style=plastic)

![demo](./demo.gif)

This is a Inkdrop plugin that turns on power modes with shake and particles.

Most codes of this plugin are from [chinchang/code-blast-codemirror](https://github.com/chinchang/code-blast-codemirror).

## Install

```shell
ipm install power
```

## Config

Preferences -> Plugins -> power -> Settings

| Title | Default Value | Description |
| ---- | ---- | ---- |
| Enable Effect | On | Select if you enable particles effects. |
| Effect Type | 1 | Select effect types to use. |
| Enable Shake | Off | Select if you enable shake. |

## Known Issues

- After you have turned off the plugin, you will need to reload the window to enable it again.

## Changelog

### 1.0.1

* Fixed a bug that tried to getComputedStyle from a non-existent node.

### 1.0.0 - First Release
* Every feature added
* Every bug fixed