# p2jb / poopsploit — PS5 WebKit exploit host

Static site. Open `index.html` on the console browser; it detects the firmware and
greys out whichever exploit cannot run.

| exploit    | firmware      | technique                              |
|------------|---------------|----------------------------------------|
| Poopsploit | 9.00 – 12.00  | IPv6 `rthdr` UAF                       |
| P2JB       | 12.00 – 12.70 | `cr_ref` overflow via `kqueueex` (~1 h) |

12.00 is the one firmware both cover.
