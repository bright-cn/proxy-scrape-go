[![促销](https://github.com/bright-cn/Google-News-Scraper/blob/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner%20CN.png?md5=105367-daeb786e)](https://www.bright.cn/?promo=github15)
# Go 代理爬虫

使用代理服务器，通过 Colly、Goquery、Selenium 进行网络爬虫的基础示例程序

本仓库包含两个分支：

- `basic` 分支包含供 [Go Proxy Servers](https://www.bright.cn/blog/how-tos/go-proxy-servers) 这篇文章改动的基础代码。  
- `main` 分支则是该文章教程最终的成果。

该项目展示了在[Go 语言网络爬虫](https://www.bright.cn/blog/how-tos/web-scraping-go)中设置代理服务器的方式。使用代理可以通过他们的 IP 地址保护您的数字身份，从而躲避 IP 封禁和地域限制。

## 安装
要使用此项目，您需要在计算机上安装 Go。您可以从 Go 的官方站点下载并安装：[https://golang.org/](https://golang.org/)

## 快速上手
1. 克隆此仓库：

    ```shell
    git clone https://github.com/shacharbd/proxy-scrape-go.git
    ```
2. 进入项目目录：

    ```shell
    cd proxy-scrape-go
    ```
3. 安装依赖：

    ```shell
    go mod download
    ```

## 使用说明
此项目演示了如何在 Go 中使用代理服务器进行网络爬虫。它使用了以下库：
- [Colly](https://github.com/gocolly/colly) - Go 语言的爬虫框架
- [Goquery](https://github.com/PuerkitoBio/goquery) - Go 语言的 HTML 解析库
- [Selenium](https://github.com/tebeka/selenium) - 浏览器自动化工具

要运行此项目，请确保您拥有可用的代理服务器。您可以从像 [Bright Data](https://www.bright.cn/) 这样的服务商获取代理服务器信息。获取到代理服务器信息后，修改 `main.go` 文件以设置合适的代理配置。

## 贡献
欢迎贡献！如果您发现任何问题或有改进建议，请提交 issue 或 pull request。

## 许可证
本项目基于 MIT 许可证开源。详见 [LICENSE](LICENSE) 文件。
