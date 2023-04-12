# index.html
When making a request is made to a website's server, a particular page needs to be specified. This can be any page, but if no page in particular is requested the server will send the `index.html` file

Because of this behavior, your `index.html` page is effectively your homepage

---

Note the two URLs below and how the first includes `index.html` at the end, but the latter doesn't. This is because without a particular page specified, the browser will serve the `index` file by default

```
http://apollo.occc.edu/User9038/lee/hw1/index.html

http://apollo.occc.edu/User9038/lee/hw1
```