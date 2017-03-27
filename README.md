# 爬虫 ip 池


1. 抓取免费代理，以 list 类型保存到 redis 中。

2. 定期 ping ，删除失效 ip。

3. 抓取页面时，从 redis pop 一个 ip，用完之后再 push 回去。
