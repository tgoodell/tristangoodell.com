# tristangoodell.com

---

This repository houses the website files for [tristangoodell.com](https://tristangoodell.com). 

![html5](https://img.shields.io/badge/code-HTML5-orange.svg)
![css3](https://img.shields.io/badge/code-CSS-blue.svg)
![js](https://img.shields.io/badge/code-JS-yellow.svg)
![avh](https://img.shields.io/badge/web-Apache%20Virtual%20Hosts-critical.svg)

## Installation

---

As noted [here](https://blog.tgoodell.com/guide-to-apache-virtual-hosts/), Apache Virtual Hosts are needed. Follow the guide if you have not already installed it on a web server. 

Then, log into your web server: 

`ssh root@xxx.xxx.xxx.xxx`

Make sure that you have already created the target domain and the neccessary configs for Apache Virtual Hosts. Naviagte to the proper directory:

`cd /path/to/tristangoodell.com`

Remove the current files:

`rm -r public_html`

Then, clone this github repo to create a new `public_html`:

`git clone https://github.com/tgoodell/tristangoodell.com public_html`

## License

TBD
