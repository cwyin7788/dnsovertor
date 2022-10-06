# DNSOverTor

### 为什么要用 DNSOverTor ？

保障上网的匿名性

###  DNSOverTor 的优点:

墙外域名DNS的解释走tor，保障匿名性

墙内域名交回给墙内dns 119.29.29.29 / 223.5.5.5解释，令使用墙内应用增加DNS解释速度

绝不纪录解释日志

不使用EDNS，不会把用户IP网段往上游发

去广告、钓鱼网站

国外域名的DNS解释走tor虽然会有点慢，但保障了匿名，而由于使用了Cloudflare CDN，Cloudflare有它自己的Anycast技术，只要本地线路对Cloudflare友好，DoH的解释分别有Cloudflare的CDN缓存以及AdGuardHome的缓存，可以做到双加速效果。

### DNSOverTor 的缺点:

走tor的，可能会比其他DNS解释器慢一些，但这都只是可能，因为Cloudflare和AdGuardHome都有缓存，只要线路对cloudflare友好，其实都可以很快。

当然还是那一点，如果本地线路对Cloudflare 不友好，可能就会比较慢了。

本DNSOverTor 详细说明[网站](https://www.dnsovertor.tk)

本DNSOverTor [电报群](https://t.me/+5VnHsxjgKYUzMTVl)

项目进一步说明 [V2ex](https://v2ex.com/t/883994#reply16)