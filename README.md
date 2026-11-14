# Shadow server

The mailbox server of the Shadow messenger (a Cloudflare Worker + D1 database).
It only stores encrypted messages for a few days. It never sees keys or readable text.

[

![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)

](https://deploy.workers.cloudflare.com/?url=https://github.com/YOUR-USERNAME/shadow-server)

## After the deploy
1. Open `https://<your-worker>.workers.dev/ping`. You must see `sh-so`.
2. In the Shadow app: Online settings → server address = that address (without /ping), server password = the SERVER_KEY you typed.

## راهنما
دکمه‌ی بالا را بزن، وارد Cloudflare شو، یک رمز سرور (SERVER_KEY) بنویس و Deploy را بزن.
بعد آدرس Worker و همان رمز را در برنامه‌ی Shadow وارد کن.
