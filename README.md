# lawcheck-ig-assets

Картинки постов LawCheck для публикации через Instagram Content Publishing API.

Репозиторий существует по одной причине: серверы Meta не могут скачать файл
с `lawchek.ru` (российский IP `5.129.200.118`) — запросы до сервера не доходят,
в логах Caddy их нет. При этом API требует публичный URL и не принимает файл
с диска. Раздача идёт через CDN jsDelivr, до которого Meta дотягивается.

Формат ссылки:

```
https://cdn.jsdelivr.net/gh/lawcheck/lawcheck-ig-assets@main/posts/<файл>.png
```

Исходники постов и сценарии рилсов — в проекте `lawcheck-reels`.
