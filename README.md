# Odaily RSS

Makes it easier for you to access Web3 information via Odaily RSS subscriptions .

# RSS document

## Odaily RSS introduction

Odaily RSS is an XML-based file format that includes the day's in-depth articles and real-time newsletter updates. Odaily RSS helps you stay up to date with the latest information from the [odaily.news](https://www.odaily.news) website.

We provide rss live links：
- 快讯： https://rss.odaily.news/rss/newsflash
- 文章： https://rss.odaily.news/rss/post

## Response format

The RSS interface returns an XML document containing the following elements:

- `<channel>`: RSS channel information .
  - `<title>`: channel title .
  - `<link>`: channel URL .
  - `<description>`: channel description .
  - `<item>`: Contains information about an article . A `<channel>` can contain multiple `< items >`.
    - `<title>`: title。
    - `<description>`: description .
    - `<link>`:  URL .
    - `<pubDate>`: Publication date of article .
    - `<guid>`: guid .

## Use example

Visit the following URL to get the RSS data:

https://rss.odaily.news/rss/newsflash

Example response：

```rss
<rss xmlns:dc="http://purl.org/dc/elements/1.1/" version="2.0">
  <channel>
    <title>Odaily</title>
    <link>https://www.odaily.news/zh-CN/</link>
    <description>Odaily</description>
    <image>
      <title>Odaily</title>
      <url>https://oss.odaily.top/share-icon.png</url>
      <link>https://www.odaily.news/zh-CN/</link>
    </image>
    <item>
      <title>Vitalik：“我只支持开源”应该是一个更常见的观点</title>
      <link>https://www.odaily.news/zh-CN/newsflash/443019</link>
      <description><p>Odaily星球日报讯 以太坊联合创始人 Vitalik Buterin 在 X 平台发文表示：“我只支持开源”应该是一个更常见的观点，反对开源强大技术的一个主要论据是有时被提起是零和行为的风险，在现代混乱的世界中，最有可能坚持的方法很容易公开理解的保证，即事情正在公开发生任何人都可以去了解正在发生的事情并参与其中。</p></description>
      <category>Odaily</category>
      <pubDate>Tue, 12 Aug 2025 11:30:41 GMT</pubDate>
      <author>Odaily</author>
      <guid>https://www.odaily.news/zh-CN/newsflash/443019</guid>
      <dc:creator>Odaily</dc:creator>
    </item>
  </channel>
</rss>
```

## Contact

For business cooperation, please email：marketing@odaily.email。

If you need business cooperation, please add us on WeChat for business

WeChat of our business QR code :
<img width="100" alt="496bd829f51cda8f4c8027daf0e6b543" src="https://piccdn.0daily.com/202212/02073313/n38zo2eckiajkarj.png">
<img width="100" alt="496bd829f51cda8f4c8027daf0e6b543" src="https://piccdn.0daily.com/202212/02073318/whh64xdbamdlspu2.png">

At the same time, we also have some communities, if you are interested, you can join our community.

	- Telegram: https://t.me/Odaily_CryptoPunk
	- Discord: https://discord.com/invite/nQrCTu9Ekd
	- twitter: https://twitter.com/OdailyChina
