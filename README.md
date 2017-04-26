# headless_chrome
通过 chrome 59 的 unstable 版本来在服务端运行一个浏览器

---


### build
docker build -t="fghpdf/headless_chrome" .

---

### run
docker run -i -t --shm-size=256m --rm --name=headlessChrome_image -p=127.0.0.1:9222:9222 fghpdf/headless_chrome
