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

Feel free to create an issue if you have any suggestions.

See https://gitlab.torproject.org/woswos/CAPTCHA-Monitor for the main project.