# Filters and Topics
- 해당 페이지는 더 이상 사용되지 않습니다. [Confluence](https://ascentkorea.atlassian.net/wiki/spaces/CJHZ/pages/397606925/Features)를 참고해 주세요!
## Common

[HTML](https://ascentkorea-docs.github.io/mobile/features/filters\_and\_topics/sample.html) 
[JSON](https://ascentkorea-docs.github.io/mobile/features/filters\_and\_topics/sample.json)

![](<../../.gitbook/assets/filters_and_topics.png>)

```
{
    "sequence": 1,
    "type": "filters_and_topics",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(4)#appbar.appbar > div:nth-child(1) > div:nth-child(1) > div:nth-child(1)#bqHHPb.bqHHPb",
    "refinements": [
        {
            "type": "filter",
            "text": "이미지"
        },
        {
            "type": "filter",
            "text": "동영상"
        },
        {
            "type": "topic",
            "text": "가성 비",
            "query": "가성비 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "LG",
            "query": "LG 냉장고 추천"
        },
        {
            "type": "filter",
            "text": "쇼핑"
        },
        {
            "type": "topic",
            "text": "1 인",
            "query": "1인 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "일반형",
            "query": "일반형 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "4 도어",
            "query": "4도어 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "2 도어",
            "query": "2도어 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "삼성",
            "query": "삼성 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "소형",
            "query": "소형 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "신혼",
            "query": "신혼 냉장고 추천"
        },
        {
            "type": "topic",
            "text": "디시",
            "query": "냉장고 추천 디시"
        }
    ]
}
```

## Seperated topic


[HTML](https://ascentkorea-docs.github.io/mobile/features/filters\_and\_topics/sample2.html) 
[JSON](https://ascentkorea-docs.github.io/mobile/features/filters\_and\_topics/sample2.json)

![](<../../.gitbook/assets/filters_and_topics_seperated_topic.png>)

```
{
    "sequence": 1,
    "type": "filters_and_topics",
    "refinements": [
        {
            "type": "topic",
            "text": "料金",
            "query": "病院 診断書 料金"
        },
        {
            "type": "topic",
            "text": "もらえない",
            "query": "病院 診断書 もらえない"
        },
        {
            "type": "topic",
            "text": "もらい方 仮病",
            "query": "病院 診断書 もらい方 仮病"
        },
        {
            "type": "topic",
            "text": "後日 いつまで",
            "query": "病院 診断書 後日 いつまで"
        },
        {
            "type": "topic",
            "text": "もらえない 風邪",
            "query": "病院 診断書 もらえない 風邪"
        },
        {
            "type": "topic",
            "text": "種類",
            "query": "病院 診断書 種類"
        },
        {
            "type": "topic",
            "text": "誰に頼む",
            "query": "病院 診断書 誰に頼む"
        },
        {
            "type": "topic",
            "text": "本人以外",
            "query": "病院 診断書 本人以外"
        },
        {
            "type": "topic",
            "text": "電話",
            "query": "病院 診断書 電話"
        },
        {
            "type": "topic",
            "text": "保険証なし",
            "query": "病院 診断書 保険証なし"
        }
    ]
}
```