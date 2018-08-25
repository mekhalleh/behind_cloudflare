# behind_cloudflare

This module can help you to discover the real IP address behind the Cloudflare service.

This can be useful if you need to test the security of your server and your website 
behind Cloudflare by discovering the real IP address.

![alt text][module_info]

![alt text][module_advanced]

More precisely, I use multiple data sources (DNS enumeration, SEO PrePost, Censys) to collect
assigned (or have been) IP addresses from the targeted site or domain that uses the 
Cloudflare WAF as a service.

![alt text][module_demo]

[module_info]: https://raw.githubusercontent.com/mekhalleh/behind_cloudflare/master/pictures/01-demo.png "Module: info"
[module_advanced]: https://raw.githubusercontent.com/mekhalleh/behind_cloudflare/master/pictures/02-demo.png "Module: advanced"
[module_demo]: https://raw.githubusercontent.com/mekhalleh/behind_cloudflare/master/pictures/03-demo.png "Module: demo"