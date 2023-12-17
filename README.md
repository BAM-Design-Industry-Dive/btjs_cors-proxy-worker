# cloudflare-cors-anywhere
Cloudflare CORS proxy in a worker.

Deploy workers:
https://workers.cloudflare.com/

Paste index.js into your a new cloudflare worker.
Adjust the blacklist or whitelist to your needs.
Use the regex formatting shown in the example, which is where webflow hosts its files, so if you're using this for webflow, you're almost done!
