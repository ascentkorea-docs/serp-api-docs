---
description: 'field 추가: site_name'
---

# Organic results


## Common

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.json)

![](../../.gitbook/assets/organic\_common.png)

```json
{
    "sequence": 13,
    "type": "organic_results",
    "position": 10,
    "site_name": "kakaobank.com",
    "displayed_link": "https://m.kakaobank.com",
    "title": "카카오뱅크",
    "url": "https://m.kakaobank.com/",
    "snippet": "카카오뱅크 이용안내, 상담하기, 소비자보호, 증명서발급, 회사소개, 인재채용, (주)카카오뱅크."
}
```

## Date

date 값을 100% 보장하지 않음 - GIT_ISSUE 참고
[GIT_ISSUE](https://github.com/ascentkorea/mongttang_google_parser/issues/251)

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.json)

![](../../.gitbook/assets/organic\_date.png)

```json
{
    "sequence": 3,
    "type": "organic_results",
    "position": 3,
    "site_name": "jmtgame.com",
    "displayed_link": "https://jmtgame.com › bbs › board",
    "date": "2012. 4. 21.",
    "title": "눈 몬스터의 침입 (고급) > 쥬니어네이버 - 존맛탱게임",
    "url": "https://jmtgame.com/bbs/board.php?bo_table=NaverGame&wr_id=152",
    "snippet": "2012. 4. 21. — GAME SUBJECT눈 몬스터의 침입 (고급) KEY FEATURES마우스 INSTRUCTION귀여운 몽키 그러니까 원숭이가 나오는 게임인데요, 마우스를 잘 활용을 하셔서 ..."
}
```

## File format

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample10.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample10.json)

![](../../.gitbook/assets/organic\_file_format.png)

```json
{
    "sequence": 2,
    "type": "organic_results",
    "position": 2,
    "site_name": "memory.library.kr",
    "displayed_link": "https://memory.library.kr › o...",
    "title": "경기도사서협의회",
    "url": "https://memory.library.kr/files/original/6cb7fa45b0a2ca4fd33ef19aecebfc6c.pdf",
    "snippet": "이를 위해서 경기도 사서. 협의회는 공공도서관 발전을 위한 조사연구 및 연구물 간행, 회원 연수와 업무 교류, 단위 도서관. 의 모범 사례 발굴 보급을 비롯한 다양한 ...",
    "file_format": "PDF"
}
```

## Thumbnail

#### Image

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.json)

![](../../.gitbook/assets/organic\_thumbnail\_image.png)

```json
{
    "sequence": 2,
    "type": "organic_results",
    "position": 2,
    "site_name": "flashgamemall.tistory.com",
    "displayed_link": "https://flashgamemall.tistory.com › ...",
    "date": "2021. 2. 24.",
    "title": "눈몬스터의 침입 (뭉게뭉게 왕국을 지켜라) - 플래시게임몰",
    "url": "https://flashgamemall.tistory.com/710",
    "snippet": "2021. 2. 24. — 눈몬스터의 침입 조작키 - 마우스 게임방법 : 마우스를 이용하여 캐릭터를 선택하고 클릭을 한 상태로 ... 동물농장 > 초급' 카테고리의 다른 글 ...",
    "thumbnail": {
        "type": "image",
        "url": "https://flashgamemall.tistory.com/710",
        "desc": "동물 농장 눈 몬스터 의 침입(출처: flashgamemall.tistory.com)"
    }
}
```

#### Video

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.json)

![](../../.gitbook/assets/organic\_thumbnail\_video.png)

```json
{
    "sequence": 5,
    "type": "organic_results",
    "position": 5,
    "site_name": "gamegogo.co.kr",
    "displayed_link": "https://gamegogo.co.kr › bbs › board",
    "date": "2021. 3. 21.",
    "title": "눈 몬스터의 침입 (고급) > 추억_쥬니어네이버게임 모음 | 게임고고 [플래시게임 아카이브]",
    "url": "https://gamegogo.co.kr/bbs/board.php?bo_table=game_navergame&wr_id=64",
    "snippet": "2021. 3. 21. — 크라라 공주와 이상한 방 (고급) - 쥬니버 동물농장 … 작성자 최고관리자 작성일 03-21 조회 7258.",
    "thumbnail": {
        "type": "video",
        "url": "https://gamegogo.co.kr/bbs/board.php?bo_table=game_navergame&wr_id=64",
        "desc": "동물 농장 눈 몬스터 의 침입 동영상"
    }
}
```

#### Direct video

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.json)

![](../../.gitbook/assets/organic\_thumbnail\_direct\_video.png)

```json
{
    "sequence": 18,
    "type": "organic_results",
    "position": 16,
    "site_name": "youtube.com",
    "displayed_link": "https://m.youtube.com › watch",
    "title": "돼범이, 무단 주거 침입은 끝! 드디어 생긴 가족 I TV동물농장 (Animal Farm) | SBS Story",
    "url": "https://m.youtube.com/watch?v=9KADe6aVJsU",
    "thumbnail": {
        "type": "direct_video",
        "url": "#fpstate=ive&vld=cid:63c1842e,vid:9KADe6aVJsU",
        "date": "2021. 5. 30."
    }
}
```

## Carousels

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample2.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample2.json)

![](../../.gitbook/assets/organic\_carousels.png)

```json
{
    "sequence": 16,
    "type": "organic_results",
    "position": 13,
    "site_name": "picturethisai.com",
    "displayed_link": "https://www.picturethisai.com › care",
    "title": "은행나무 일상보호(키우기, 가지치기, 파종) - PictureThis",
    "url": "https://www.picturethisai.com/ko/care/Ginkgo_biloba.html",
    "snippet": "30년 이상은 자라야 열매를 맺기 때문에 어린 묘목의 암수를 알 수 없었는데, 현재는 유전자 분석으로 감별할 수 있게 되었다. symbolism. 꽃의 상징. 튼튼하고 부드럽게.",
    "carousels": [
        {
            "url": "https://picturethisai.com/ko/care/Ginkgo_biloba.html#Cultivation:WaterDetail",
            "title": "1. 물을주는 것"
        },
        {
            "url": "https://picturethisai.com/ko/care/Ginkgo_biloba.html#Cultivation:FertilizerDetail",
            "title": "2. 시비"
        },
        {
            "url": "https://picturethisai.com/ko/care/Ginkgo_biloba.html#Cultivation:SunlightDetail",
            "title": "3. 일조"
        }
    ]
}
```

## Site links

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample5.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample5.json)

![](../../.gitbook/assets/organic\_site\_links.png)
```json
{
    "sequence": 2,
    "type": "organic_results",
    "position": 1,
    "site_name": "ent.wsu.ac.kr",
    "displayed_link": "https://ent.wsu.ac.kr",
    "title": ": 우송대학교 입학종합서비스",
    "url": "https://ent.wsu.ac.kr/",
    "snippet": "대전광역시 동구 자양동에 있는 사립 종합대학교.",
    "sitelinks": [
        {
            "url": "https://ent.wsu.ac.kr/board/index.jsp?code=einfo0601",
            "title": "모집요강"
        },
        {
            "url": "https://ent.wsu.ac.kr/page/index.jsp?code=susi1001",
            "title": "합격자조회 및 고지서 출력"
        },
        {
            "url": "https://ent.wsu.ac.kr/board/index.jsp?code=einfo0201",
            "title": "전년도 입시결과"
        },
        {
            "url": "https://ent.wsu.ac.kr/board/index.jsp?code=einfo0701",
            "title": "입학자료실"
        },
        {
            "url": "https://ent.wsu.ac.kr/page/index.jsp?code=susi0101",
            "title": "수시모집 > 모집요강"
        },
        {
            "url": "https://ent.wsu.ac.kr/page/index.jsp?code=susi0101_n",
            "title": "전형일정"
        }
    ]
}
```

## Rating

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample3.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample3.json)

![](../../.gitbook/assets/organic\_rating.png)

```json
{
    "sequence": 21,
    "type": "organic_results",
    "position": 18,
    "site_name": "ko.aliexpress.com",
    "displayed_link": "https://m.ko.aliexpress.com › item",
    "title": "2022 뜨거운 헤어 스타일 빗 내열성 여자 젖은 후크 곱슬 머리 브러쉬 ...",
    "url": "https://m.ko.aliexpress.com/item/1005003930521466.html",
    "snippet": "AliExpress Mobile에서 품질 좋은 2022 뜨거운 헤어 스타일 빗 내열성 여자 젖은 후크 곱슬 머리 브러쉬 프로 살롱 염색 스타일링 도구 거친 와이드 스파이크 치아 ...",
    "rating": {
        "rating_count": "(13)",
        "rating_value": "4.6"
    }
}
```

## Rich snippet

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample4.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample4.json)

![](../../.gitbook/assets/organic\_rich\_snippet.png)

```json
{
    "sequence": 13,
    "type": "organic_results",
    "position": 12,
    "site_name": "korean.alibaba.com",
    "displayed_link": "https://korean.alibaba.com › Blue-to...",
    "title": "파란 이 숫자 키보드 Protable 키패드 쪼개는 도구 안드로이드 전화 아이패드 맥북 Windows를 위한 알루미늄 합금 덮개",
    "url": "https://korean.alibaba.com/product-detail/Blue-tooth-Numeric-Keyboard-Protable-Keypad-60591227877.html",
    "snippet": "파란 이 숫자 키보드 Protable 키패드 쪼개는 도구 안드로이드 전화 아이패드 ... Ios 안드로이드 윈도우,2.4ghz 미니 Usb 무선 숫자 키패드 19 키 숫자 패드 범퍼 ...",
    "properties": [
        {
            "key": "특징",
            "value": "숫자 키패드"
        },
        {
            "key": "유형",
            "value": "Bluetooth 무선"
        }
    ],
    "rating": {
        "rating_value": "3.5"
    }
}
```

## Refinements

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample7.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample7.json)

![](../../.gitbook/assets/organic\_refinements.png)

```json
{
    "sequence": 1,
    "type": "organic_results",
    "position": 1,
    "site_name": "in.or.kr",
    "displayed_link": "https://www.in.or.kr",
    "title": "보험연수원",
    "url": "https://www.in.or.kr/",
    "snippet": "4차산업기술 BIG5! 수강료: 129,360원; 교육기간: 1개월/21시간; 교육형태: 사이버.",
    "refinements": [
        {
            "text": "모집종사자"
        },
        {
            "text": "회원 로그인"
        },
        {
            "text": "자격시험"
        },
        {
            "text": "보험심사역"
        },
        {
            "text": "주요사업"
        },
        {
            "text": "사이버교육"
        },
        {
            "text": "보험연수원"
        }
    ]
}
```

## images

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample8.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample8.json)

![](../../.gitbook/assets/organic\_images.png)

```json
{
    "sequence": 2,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(2).MjjYud > div:nth-child(29) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 1,
    "displayed_link": "https://m.blog.naver.com › king-hong",
    "date": "2018. 6. 4.",
    "title": "세계에서 가장 특이한 건물(건축물) - 네이버 블로그",
    "url": "https://m.blog.naver.com/king-hong/221291311598",
    "snippet": "2018. 6. 4. — '슈틴쉬 잘레브스키'란 건축회사가 지은 건물이다. ... 거인국의 한 장면을 보는듯한 착각이 들게 한다. ... 회사를 알리기 위한 홍보수단으로 만들어졌다.",
    "images": [
        {
            "landing_url": "https://m.blog.naver.com/king-hong/221291311598"
        },
        {
            "landing_url": "https://m.blog.naver.com/king-hong/221291311598"
        },
        {
            "landing_url": "https://m.blog.naver.com/king-hong/221291311598"
        },
        {
            "landing_url": "https://m.blog.naver.com/king-hong/221291311598"
        },
        {
            "landing_url": "https://m.blog.naver.com/king-hong/221291311598"
        }
    ]
}
```

## video

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample11.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample11.json)

![](../../.gitbook/assets/organic\_video.png)

```json
{
    "sequence": 11,
    "type": "organic_results",
    "position": 5,
    "site_name": "YouTube",
    "displayed_link": "https://www.youtube.com · zollotech",
    "title": "iPhone 15, 15 Pro - Hands On First Look - YouTube",
    "url": "https://www.youtube.com/watch?v=93OLveum9Qg",
    "video": {
        "url": "#fpstate=ive&vld=cid:a22ab6c8,vid:93OLveum9Qg",
        "date": "16 hours ago"
    }
}
```

## missing_words

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample12.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample12.json)

![](../../.gitbook/assets/organic\_missing\_words.png)

```json
{
    "sequence": 11,
    "type": "organic_results",
    "position": 9,
    "site_name": "store.nintendo.co.kr",
    "displayed_link": "https://store.nintendo.co.kr › ...",
    "title": "【코스튬】아이루 모자 - 닌텐도 온라인 스토어",
    "url": "https://store.nintendo.co.kr/70050000025920",
    "snippet": "『몬스터헌터』 시리즈로부터 아이루 모자가 등장! 시리즈에서도 익숙한 헌터의 듬직한 동반자 「아이루」가 분위기를 띄운다냥! 둥글고 귀엽고 사랑스러운 아이루가 ...",
    "missing_words": [
        "얽"
    ]
}
```