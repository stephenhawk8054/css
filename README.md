# css
CSS for broken sites

## Filters

```adb
-load.com/loader.min.js^$script,3p,domain=smsonline.cloud
smsonline.cloud##+js(trusted-replace-argument, HTMLScriptElement.prototype.setAttribute, 1, json:"(function(){let link=document.createElement('link');link.rel='stylesheet';link.href='https://cdn.jsdelivr.net/gh/stephenhawk8054/css@latest/smsonline.cloud.css';document.head.appendChild(link)})()", condition, error-report.com)

-load.com/loader.min.js^$script,3p,redirect=noopjs,domain=dogdrip.net|slashdot.org|dash.infinityfree.com|www.infinityfree.com
dogdrip.net##+js(rpnt, script, window.dataLayer =, '(function(){let link=document.createElement("link");link.rel="stylesheet";link.href="https://cdn.jsdelivr.net/gh/stephenhawk8054/css@latest/dogdrip.net.css";document.currentScript.insertAdjacentElement("afterend",link)})();window.dataLayer =', sedCount, 1)

slashdot.org##+js(rpnt, script, window.SD =, '(function(){let link=document.createElement("link");link.rel="stylesheet";link.href="https://cdn.jsdelivr.net/gh/stephenhawk8054/css@latest/slashdot.org.css";document.currentScript.insertAdjacentElement("afterend",link)})();')

dash.infinityfree.com##+js(rpnt, script, window.dataLayer =, '(function(){const url="https://cdn.jsdelivr.net/gh/stephenhawk8054/css@latest/dash.infinityfree.com.css";fetch(url,{method:"GET"}).then((response=>response.text())).then((text=>{let style=document.createElement("style");style.innerHTML=text;document.head.appendChild(style)}))})();window.dataLayer =', sedCount, 1)

www.infinityfree.com##+js(rpnt, script, window.dataLayer =, '(function(){const url="https://cdn.jsdelivr.net/gh/stephenhawk8054/css@latest/www.infinityfree.com.css";fetch(url,{method:"GET"}).then((response=>response.text())).then((text=>{let style=document.createElement("style");style.innerHTML=text;document.head.appendChild(style)}))})();window.dataLayer =', sedCount, 1)
```

Click on uBO icon > ⚙ [Dashboard button](https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface#the-tools) > Add the filter(s) in ["My filters" pane](https://github.com/gorhill/uBlock/wiki/Dashboard:-My-filters) > **Turn on `Allow custom filters requiring trust`** > ✓ Apply changes > Open new tab and test again.