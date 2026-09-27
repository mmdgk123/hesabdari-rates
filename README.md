# hesabdari-rates

Auto-published live Iranian market rates (gold 18k, dollar, euro, mesghal, ounce)
fetched from tgju.org every 10 minutes by GitHub Actions.

Consumed by the hesabdari-gk PWA:

`https://mmdgk123.github.io/hesabdari-rates/rates.json`

Values from `call.tgju.org/ajax.json`:
- `geram18`, `price_dollar_rl`, `price_eur`, `mesghal` → **ریال** (divide by 10 for تومان)
- `ons` → **USD**
