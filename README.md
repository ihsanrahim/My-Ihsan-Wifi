# My Ihsan · backup address

**https://ihsanrahim.github.io/My-Ihsan-Wifi/** is an exact copy of **https://myihsan.app**.

Use it when myihsan.app does not open on a Wi-Fi network (for example an office firewall shows "Your connection is not private"). The main address is still the right one everywhere else.

- Web app: https://ihsanrahim.github.io/My-Ihsan-Wifi/app/
- Split bill: https://ihsanrahim.github.io/My-Ihsan-Wifi/split/

How it works: `.github/workflows/mirror.yml` copies the `main` branch of [ihsanrahim/My-Ihsan-Web](https://github.com/ihsanrahim/My-Ihsan-Web) every hour (or when run by hand) and publishes it with GitHub Pages. Nothing here is edited by hand. The My Ihsan Android app tries myihsan.app first and switches to this address by itself when myihsan.app does not answer.

One-time setup: Settings › Pages › Build and deployment › Source: **GitHub Actions**.
