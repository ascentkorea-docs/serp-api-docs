---
description: '신규 field 추가: subtype, fixed_query_desc'
---


# Spell check
- 해당 페이지는 더 이상 사용되지 않습니다. [Confluence](https://ascentkorea.atlassian.net/wiki/spaces/CJHZ/pages/397606925/Features)를 참고해 주세요!
## **Show origin query**

#### Including

[HTML](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample5.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample5.json)

![](https://github.com/ascentkorea-docs/serp-api-docs/assets/111344654/d46c9299-12ad-4872-9d50-1cacf9a463bd)


```
{
    "sequence": 2,
    "type": "spell_check",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(2)#taw > div:nth-child(1) > div:nth-child(1) > p.p64x9c.card-section.KDCVqf.Ww4FFb.vt6azd",
    "subtype": "including",
    "fixed_query_desc": "다음 검색어에 대한 결과 포함: ",
    "fixed_query": "항공권 예약",
    "origin_query": "항공기 예약"
}
```

#### Replacing


[HTML](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample6.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample6.json)

![](https://github.com/ascentkorea-docs/serp-api-docs/assets/111344654/ba5e5c03-9887-4623-bb47-1788a376805c)


```
{
    "sequence": 2,
    "type": "spell_check",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(2)#taw > div:nth-child(1) > div:nth-child(1) > p#fprs.p64x9c.card-section.KDCVqf.Ww4FFb.vt6azd",
    "subtype": "replacing",
    "fixed_query_desc": "수정된 검색어에 대한 결과:",
    "fixed_query": "자바스크립트 컬러피커",
    "origin_query": "자바스크립트 칼라피커"
}
```


## **Show only fixed query**

#### Applying origin

[HTML](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample7.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/spell\_check/sample7.json)

![](https://github.com/ascentkorea-docs/serp-api-docs/assets/111344654/02c2e98f-b38b-47c8-b21e-35c3baa9b70e)

```
{
    "sequence": 2,
    "type": "spell_check",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(10)#center_col.center_col.s6JM6d > div:nth-child(2)#taw > div:nth-child(1) > div:nth-child(1) > p.gqLncc.card-section.KDCVqf.Ww4FFb.vt6azd",
    "subtype": "applying_origin",
    "fixed_query_desc": "Did you mean:",
    "fixed_query": "apple smartphone"
}
```


