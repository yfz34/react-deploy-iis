# IIS佈署SPA網站
SPA屬於單頁式HTML，Client端只需載入一次，其餘靠JS控制(Router、Render Components)

## IIS軟體

- 屬於微軟內建軟體，能夠快速佈署網頁服務及ASP.NET

## 佈署說明
### 安裝

Step1. [安裝 URL Rewrite](https://www.iis.net/downloads/microsoft/url-rewrite)

Step2. 若要放置某個路徑底下做SPA，router記得加入路由

```sh
$ <BrowserRouter basename="/calendar" />
```

Step3. 將"web.config"檔案加入至佈署完資料夾

Step4. 完成

# 參考
https://blog.miniasp.com/post/2017/01/17/Angular-2-deploy-on-IIS
https://www.linkedin.com/pulse/hosting-vue-js-spa-build-microsoft-iis-zainul-zain
