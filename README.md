# ps4webkit

PS4 WebKit exploit host and GoldHEN v2.4b18.14 offline AppCache autoloader for firmware `5.05-14.02`.

- **Host:** https://laroping.github.io/ps4webkit/

## Firmware Support

| Firmware | Exploit Chain | Manifest |
| --- | --- | --- |
| `5.05`, `5.07` | WebKit + Kernel Exploit | `505.manifest` |
| `7.00-8.52` | PSFree + Lapse | `700.manifest` |
| `9.00-9.60` | PSFree + Lapse | `900.manifest` |
| `10.00-11.02` | CSS FontFace + Lapse | `css.manifest` |
| `11.50-11.52` | SlopKit (`chain_lapse.js`) | `slopkit.manifest` |
| `12.00-14.02` | SlopKit (`jb.js` + `afterglow.js`) | `slopkit.manifest` |

## Usage

1. Open `https://laroping.github.io/ps4webkit/` in the PS4 Web Browser.
2. Wait for AppCache download to reach `100%` (`cache*.html` redirects to `index.html`).
3. Reopen the URL offline to load GoldHEN.
