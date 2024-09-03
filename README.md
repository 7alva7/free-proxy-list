<p align="center">
  <a href="https://proxifly.dev">
    <img src="https://cdn.itwcreativeworks.com/assets/proxifly/images/logo/proxifly-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Updated_Every_5_Minutes-passing-success">
  <br>
  <a href="https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/all/data.txt">
    <img src="https://img.shields.io/badge/all-313-blue">
  </a>
  <a href="https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.txt">
    <img src="https://img.shields.io/badge/http-58-blue">
  </a>
  <a href="https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks4/data.txt">
    <img src="https://img.shields.io/badge/socks4-132-blue">
  </a>
  <a href="https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks5/data.txt">
    <img src="https://img.shields.io/badge/socks5-123-blue">
  </a>
  <br>
  <!-- <img src="https://img.shields.io/librariesio/release/npm/node-powertools.svg"> -->
  <!-- <img src="https://img.shields.io/bundlephobia/min/node-powertools.svg"> -->
  <!-- <img src="https://img.shields.io/codeclimate/maintainability-percentage/proxifly/free-proxy-list.svg"> -->
  <!-- <img src="https://img.shields.io/npm/dm/node-powertools.svg"> -->
  <!-- <img src="https://img.shields.io/node/v/node-powertools.svg"> -->
  <img src="https://img.shields.io/website/https/proxifly.dev.svg">
  <!-- <img src="https://img.shields.io/github/contributors/proxifly/free-proxy-list.svg"> -->
  <img src="https://img.shields.io/github/last-commit/proxifly/free-proxy-list.svg">
  <img src="https://img.shields.io/github/license/proxifly/free-proxy-list.svg">
  <br>
  <br>
  <a href="https://proxifly.dev">Site</a> | <a href="https://www.npmjs.com/package/proxifly">NPM Module</a> | <a href="https://github.com/proxifly/free-proxy-list">GitHub Repo</a>
</p>

# 🌎 Proxifly's Free Proxy List
Every 5 minutes, **Proxifly** fetches fresh proxies—including **HTTP**, **SOCKS4**, and **SOCKS5** proxies—from around the web.

> Proxifly found **313** working proxies from **33** countries in the latest update.

## 🦄 Features
* ⚡ Extremely fast
* 📝 Validated every 5 minutes
* 📓 Sorted into **HTTP**, **SOCKS4**, & **SOCKS5**
* 🌎 Contains 33 countries
* 📦 Available in **.json**, **.txt**, & **.csv** formats
* 🔐 Supports HTTPS connection
* 😊 No duplicates

### 🛑 Please follow the [GitHub Acceptable Use Policy](https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies) when using this project. You should use these proxies responsibly, without abusing them, and without intent to commit illegal activity.

## 📦 Usage
There are so many ways to get our free proxies.

You can just download the whole list as a `.txt` file, or you can even use the **Proxifly NPM module** to fetch proxies into your application programatically.

Proxifly sorts the proxies by protocol and country, but you can also just get the whole unsorted list too.


### 🔗 Direct Download Links
Click on your preferred file format to get the updated list

|Type|Count|.json|.txt|.csv|
|----|-----|-----|----|----|
|All Proxies|313|[JSON File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/all/data.json)|[Text File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/all/data.txt)|[CSV File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/all/data.csv)|
|HTTP Proxies|58|[JSON File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.json)|[Text File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.txt)|[CSV File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.csv)|
|SOCKS4 Proxies|132|[JSON File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks4/data.json)|[Text File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks4/data.txt)|[CSV File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks4/data.csv)|
|SOCKS5 Proxies|123|[JSON File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks5/data.json)|[Text File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks5/data.txt)|[CSV File](https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks5/data.csv)|


#### Other Sorted Proxies
* [🌎 Get proxies by country](https://github.com/proxifly/free-proxy-list/tree/main/proxies/countries)


### 👑 Download From Our Website
Scrape directly from our website's [free proxy list](https://proxifly.dev/tools/proxy-list/).


### 💎 Download in our Scraping Software
Get proxies with our free [proxy scraper software](https://proxifly.dev/download).

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://proxifly.dev/download?download=windows)
[![MacOS](https://img.shields.io/badge/-MacOS-lightblue.svg?style=for-the-badge&logo=apple)](https://proxifly.dev/download?download=macos)
[![Unix](https://img.shields.io/badge/-Linux/BSD-red.svg?style=for-the-badge&logo=linux)](https://proxifly.dev/download?download=linux)
[![All versions](https://img.shields.io/badge/-All_Versions-lightgrey.svg?style=for-the-badge)](https://proxifly.dev/download?download=null)


### 🙌 Use the Proxifly NPM Module
Easily fetch updated proxies in your application with the official **Proxifly NPM module**.

```shell
npm install proxifly
```

```js
const proxifly = new (require('proxifly'))({
  // Not required, but having one removes limits (get your key at https://proxifly.dev).
  apiKey: 'api_test_key'
});
```

```js
var options = {
  protocol: 'http', // http | socks4 | socks5
  anonymity: 'elite', // transparent | anonymous | elite
  country: 'US', // https://www.nationsonline.org/oneworld/country_code_list.htm
  https: true, // true | false
  speed: 10000, // 0 - 60000
  format: 'json', // json | text
  quantity: 1, // 1 - 20
};

proxifly.getProxy(options)
.then(proxy => {
  console.log('Proxies:', proxy);
})
.catch(e => {
  console.error(e);
})
```


### 🔑 Fetch with cURL
Fetch the latest proxy list with the following command:


#### All Proxies
```shell
curl -sL https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/all/data.txt -o all.txt
```


#### HTTP Proxies
```shell
curl -sL https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.txt -o http.txt
```


#### SOCKS4 Proxies
```shell
curl -sL https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/socks4.txt -o socks4.txt
```


#### SOCKS5 Proxies
```shell
curl -sL https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/socks5.txt -o socks5.txt
```


## 🧸 Contributing
Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.
