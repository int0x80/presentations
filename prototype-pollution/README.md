# Prototype Pollution

Recently learned about prototype pollution and wanted to better understand it. The target app in this repo is a Dockerized version of https://github.com/Kirill89/prototype-pollution-explained.

## Target App

```D
git clone --depth=1 https://github.com/int0x80/presentations.git
cd presentations/prototype-pollution/vulnerable-prototype-pollution/
docker build -t vulnpp .
docker run --rm -d -p 3000:3000 vulnpp
```

## Credits

* [PortSwigger](https://portswigger.net/web-security/prototype-pollution)
* [Vulnerable app from Kirill](https://github.com/Kirill89/prototype-pollution-explained)
* [Snyk](https://learn.snyk.io/lesson/prototype-pollution/)
* [Gadgets from Sergey Bobrov](https://github.com/BlackFan/client-side-prototype-pollution)

