# Odaily RSS

Makes it easier for you to access Web3 information via Odaily RSS subscriptions .

# RSS document

## Odaily RSS introduction

Odaily RSS is an XML-based file format that includes the day's in-depth articles and real-time newsletter updates. Odaily RSS helps you stay up to date with the latest information from the [odaily.news](https://www.odaily.news) website.

We provide rss live links in 7 languages：
- 中文：  www.odaily.news/v1/openapi/odailyrss
- English: www.odaily.news/v1/openapi/odailyrss_en
- 中文繁体: www.odaily.news/v1/openapi/odailyrss_zhtw
- 日本语: www.odaily.news/v1/openapi/odailyrss_ja
- 한국어: www.odaily.news/v1/openapi/odailyrss_ko
- ภาษาไทย: www.odaily.news/v1/openapi/odailyrss_th
- Tiếng Việt: www.odaily.news/v1/openapi/odailyrss_vi

## Response format

The RSS interface returns an XML document containing the following elements:

- `<channel>`: RSS channel information .
  - `<title>`: channel title .
  - `<link>`: channel URL .
  - `<description>`: channel description .
  - `<language>`: current language .
  - `<item>`: Contains information about an article . A `<channel>` can contain multiple `< items >`.
    - `<title>`: title.
    - `<description>`: description .
    - `<author>`: author
    - `<link>`:  URL .
    - `<source>`: source
    - `<pubDate>`: Publication date of article .
    - `<content>`: content.
    - `<guid>`: guid .
    - `<media>`: image link

## Use example

Visit the following URL to get the RSS data:

https://www.odaily.news/v1/openapi/odailyrss

Example response：

```rss
 <rss xmlns:content="http://purl.org/rss/1.0/modules/content/" xmlns:wfw="http://wellformedweb.org/CommentAPI/" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:atom="http://www.w3.org/2005/Atom" xmlns:sy="http://purl.org/rss/1.0/modules/syndication/" xmlns:slash="http://purl.org/rss/1.0/modules/slash/" xmlns:media="http://search.yahoo.com/mrss/" version="2.0">
  <script/>
  <channel>
    <title>Odaily星球日报 | 区块链新闻数据资讯媒体</title>
    <link>http://new.site</link>
    <description>36氪战略合作区块链媒体，致力于客观求是，助力行业发展，报道不收取费用，将新闻资讯、数据行情、技术解读、独家深度一网打尽，探索真实区块链。</description>
    <language>zh-cn</language>
    <item>
      <title>Open Campus ID将于9月14日向EDU与Genesis NFT持有者开放第一阶段白名单</title>
      <author>Odaily</author>
      <link>http://new.site/newsflash/335046</link>
      <pubDate>Fri, 08 Sep 2023 16:04:46 PRC+0800</pubDate>
      <source>Odaily</source>
      <media:content url="https://piccdn.0daily.com/202306/09092228/ft0auhhupnaquqaw.png" medium="image"/>
      <content:encoded>
      <![CDATA[ <p> Odaily星球日报讯 据官方消息，Open Campus ID将于北京时间9月14日18:00向EDU与Genesis NFT持有者开放第一阶段白名单，总量共1000个。 Open Campus ID是SBT，可访问Open Campus提供的教育内容，并拥有与OC ID相关的所有信息。Open Campus ID以.edu为后缀，域名可由用户选择，代表其链上教育身份。 </p> ]]>
      </content:encoded>
      <guid>http://new.site/newsflash/335046</guid>
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
