## Terrario - A Terraria rewrite for Casio calculators

Original by [KBD2](https://github.com/KBD2/terrario).  
SH3 port by [Koharu-Mizuki](https://github.com/Koharu-Mizuki).

### Supported Models

| Model | CPU / RAM | Status |
|---|---|---|
| fx-9860GII / fx-9750GIII | SH4 / 256KB | ✅ Original |
| Graph 35+E / 35+E II | SH4 / 64KB + PRAM | ✅ Original |
| **fx-9860G (original SH3)** | **SH3 / 64KB** | ✅ **SH3 Port** |
| **fx-9750GII (SH3, 9860 firmware)** | **SH3 / 64KB** | ✅ **SH3 Port** |

Thanks to Lephenixnoir for gint and fxSDK.

### Download

Check the [Actions](https://github.com/Koharu-Mizuki/casio-terrario/actions) tab → latest run → scroll down to "Artifacts" → download `TERRARIO-SH3`.

### Build

Requires [fxSDK](https://git.planet-casio.com/lephe/fxsdk) with `sh-elf` toolchain and [gint](https://git.planet-casio.com/lephe/gint).

```bash
fxsdk build-fx
```

Output: `TERRARIO.g1a`

### Licenses

Source code: MIT license.  
Image assets: CC BY 4.0 license.  
See `LICENSE` for details.
