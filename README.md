# CAPTCHA Monitor's Web Component

The files in this repository are the files used during the measurements.

`index.html` is the file that is located at [https://captcha.wtf](https://captcha.wtf)
and [https://exit11.online](https://exit11.online). `index.html` is used for the 
measurements where a simple page that requires a single HTTP request to fetch. 
It is a simple "Hello World!" example.

`complex.html` is the file that is located at 
[https://captcha.wtf/complex.html](https://captcha.wtf/complex.html)
and [https://exit11.online/complex.html](https://exit11.online/complex.html).
`complex.html` is used for measurements
where a complex page that requires multiple HTTP requests to fetch. This page
also contains external links to widely used Bootstrap and jQuery libraries.
Additionally, `complex.html` has a few images. `complex.html` tries to
simulate an ordinary web page that can be found on the internet.

`captchamonitor.conf` is the configuration file used to configure the Nginx server.

Feel free to create an issue if you have any suggestions.

_Note:_ Both [https://captcha.wtf](https://captcha.wtf) and [https://exit11.online](https://exit11.online)
are the fronted by Cloudflare. [https://bypass.captcha.wtf](https://bypass.captcha.wtf)
and [https://bypass.exit11.online](https://bypass.exit11.online) are not proxied by
Cloudflare. See the screenshots below:

![captcha.wtf configuration](./docs/captcha.wtf.png)
![exit11.online configuration](./docs/exit11.online.png)

See https://gitlab.torproject.org/woswos/CAPTCHA-Monitor/-/wikis/home for the 
main project and further details.