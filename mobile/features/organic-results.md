---
description: '[field 추가]: file_format'
---

# Organic results


## Common

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.json)

![](../../.gitbook/assets/organic\_common.png)

```
{
    "sequence": 13
    "type": "organic_results"
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(12).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe"
    "position": 8
    "displayed_link": "https://m.kakaobank.com"
    "title": "카카오뱅크"
    "url": "https://m.kakaobank.com/"
    "snippet": "카카오뱅크 이용안내, 상담하기, 소비자보호, 증명서발급, 회사소개, 인재채용, (주)카카오뱅크."
}
```

## Date

date 값을 100% 보장하지 않음 - GIT_ISSUE 참고
[GIT_ISSUE](https://github.com/ascentkorea/mongttang_google_parser/issues/251)

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample9.json)

![](../../.gitbook/assets/organic\_date.png)

```
{
    "sequence": 3,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(3).MjjYud > div:nth-child(4) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 3,
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

```
{
    "sequence": 2,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(2).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 2,
    "displayed_link": "https://memory.library.kr › o...",
    "title": "경기도사서협의회",
    "url": "https://memory.library.kr/files/original/6cb7fa45b0a2ca4fd33ef19aecebfc6c.pdf",
    "snippet": "이를 위해서 경기도 사서. 협의회는 공공도서관 발전을 위한 조사연구 및 연구물 간행, 회원 연수와 업무 교류, 단위 도서관. 의 모범 사례 발굴 보급을 비롯한 다양한 ...",
    "file_format": "PDF"
}
```

## Thumbnail

#### Image

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.json)

![](../../.gitbook/assets/organic\_thumbnail\_image.png)

```
{
    "sequence": 2,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(2).MjjYud > div:nth-child(4) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 2,
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

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample.json)

![](../../.gitbook/assets/organic\_thumbnail\_video.png)

```
{
    "sequence": 5,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(5).MjjYud > div:nth-child(5) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 5,
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

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample6.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample6.json)

![](../../.gitbook/assets/organic\_thumbnail\_direct\_videopng2.png)

```
{
   "sequence": 14
   "type": "organic_results"
   "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(12).MjjYud > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.PHap3c.NfHzb"
   "position": 11
   "displayed_link": "https://m.timesofindia.com › tamil"
   "title": "Best Children Tamil Nursery Song 'Kokkupaaru' - Kids Nursery Songs In Tamil | Entertainment - Times of India Videos"
   "url": "https://m.timesofindia.com/videos/entertainment/kids/tamil/best-children-tamil-nursery-song-kokkupaaru-kids-nursery-songs-in-tamil/videoshow/71370233.cms"
   "thumbnail": {
    "type": "direct_video"
    "url": "https://m.timesofindia.com/videos/entertainment/kids/tamil/best-children-tamil-nursery-song-kokkupaaru-kids-nursery-songs-in-tamil/videoshow/71370233.cms"
    "date": "2019. 9. 30."
   }
}
```

## Carousels

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample2.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample2.json)

![](../../.gitbook/assets/organic\_carousels.png)

```
{
    "sequence": 9,
    "type": "organic_results",
    "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(1)#rso > div:nth-child(1).kp-wholepage.pEZBSb.kp-wholepage-osrp.EyBRub > div:nth-child(2).fKw1wf > div:nth-child(2)#_Jlp8Yrr0FMqFoAS48aLQDQ11.osrp-blk > sticky-header.pA48Db > div:nth-child(3) > div:nth-child(1) > div:nth-child(2).V734yf.eXEBMb.Znsfnf > div:nth-child(1).GhpATe.pttBJc > div:nth-child(1)#kp-wp-tab-cont-overview > div:nth-child(2).aoPfOc > div:nth-child(1) > div:nth-child(1) > div:nth-child(3)#kp-wp-tab-overview > div:nth-child(29).TzHB6b.mnr-c.UBoxCb.K7khPe > div:nth-child(1) > div:nth-child(1).sATSHe > div:nth-child(1) > div:nth-child(1).wXlZre.TjcfIc.eE3xqf.B03h3d.P6OZi.V14nKc.ptcLIOszQJu__wholepage-card.wp-ms > div:nth-child(1).UDZeY > div:nth-child(1) > div:nth-child(1).mnr-c.xpd.O9g5cc.uUPGi",
    "position": 3,
    "displayed_link": "https://www.cbssports.com › nfl",
    "title": "NFL Football - News, Scores, Stats, Standings, and Rumors - CBS Sports",
    "url": "https://www.cbssports.com/nfl/",
    "snippet": "CBS Sports has the latest NFL Football news, live scores, player stats, standings, fantasy games, and projections.",
    "carousels": [
        {
            "url": "https://www.cbssports.com/nfl/news/nfl-2022-schedule-release-one-mans-zany-format-for-leagues-newest-must-see-event-plus-some-real-questions/amp/",
            "title": "NFL 2022 schedule release: One man's zany format for league's newest \nmust-see event, plus some real questions",
            "date": "4 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/howie-roseman-addresses-eagles-needs-in-secondary-after-nfl-draft-we-just-have-to-keep-working/amp/",
            "title": "Howie Roseman addresses Eagles' needs in secondary after NFL Draft: 'We \njust have to keep working'",
            "date": "6 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/agents-take-determining-a-fair-deal-for-rams-cooper-kupp-in-an-exploding-receivers-market/",
            "title": "Agent's Take: Determining a fair deal for Rams' Cooper Kupp in an exploding \nreceivers market",
            "date": "7 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/steelers-mike-tomlin-leads-active-nfl-head-coaches-in-significant-category-including-bill-belichick/amp/",
            "title": "Steelers' Mike Tomlin leads active NFL head coaches in significant \ncategory, including Bill Belichick",
            "date": "7 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/2022-nfl-schedule-release-broncos-opponents-previews-full-list-of-teams-on-regular-season-schedule/amp/",
            "title": "2022 NFL schedule release: Broncos opponents, previews, full list of teams \non regular-season schedule",
            "date": "8 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/veterans-who-could-be-facing-chopping-block-plus-nfl-schedule-leaks-and-2023-top-offensive-prospects/amp/",
            "title": "Veterans who could be facing chopping block, plus NFL schedule leaks and \n2023 top offensive prospects",
            "date": "8 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/2022-nfl-draft-chris-carson-nelson-agholor-and-other-veterans-who-could-be-replaced-by-rookies/amp/",
            "title": "2022 NFL Draft: Chris Carson, Nelson Agholor and other veterans who could \nbe replaced by rookies",
            "date": "12 hours ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/2022-nfl-schedule-release-team-by-team-opponents-previews-dates-times-tv-live-streaming/",
            "title": "2022 NFL schedule release: Team-by-team opponents, previews, dates, times, \nTV, live streaming",
            "date": "1 day ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/tom-brady-reveals-his-nfl-retirement-plan-is-in-the-broadcast-booth-but-has-unfinished-business-with-bucs/amp/",
            "title": "Tom Brady reveals his NFL retirement plan is in the broadcast booth, but \nhas 'unfinished business' with Bucs",
            "date": "1 day ago"
        },
        {
            "url": "https://www.cbssports.com/nfl/news/nfl-2022-schedule-release-cbs-reveals-champion-rams-will-host-russell-wilson-broncos-on-christmas-day/amp/",
            "title": "NFL 2022 schedule release: CBS reveals champion Rams will host Russell \nWilson, Broncos on Christmas Day",
            "date": "1 day ago"
        }
    ]
}
```

## Site links

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample5.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample5.json)

![](<../../.gitbook/assets/image (1) (1).png>)

```
{
    "sequence": 1,
    "type": "organic_results",
    "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.xpd.EtOod.pkphOe",
    "position": 1,
    "displayed_link": "https://namu.wiki › 올림픽",
    "title": "올림픽 - 나무위키",
    "url": "https://namu.wiki/w/%EC%98%AC%EB%A6%BC%ED%94%BD",
    "snippet": "또한 월드컵은 개최기간이 대략 1달 정도이지만 올림픽은 개최기간이 개막 전 경기를 포함해서 대략 19일이다. 다만 경기종목이 늘어나고 한 도시에 모든 경기장을 다 지을 ...",
    "sitelinks": [
        {
            "url": "https://namu.wiki/w/2022%20%EB%B2%A0%EC%9D%B4%EC%A7%95%20%EB%8F%99%EA%B3%84%EC%98%AC%EB%A6%BC%ED%94%BD",
            "title": "2022 베이징 동계올림픽",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(1).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        },
        {
            "url": "https://namu.wiki/w/%EC%98%AC%EB%A6%BC%ED%94%BD/%EC%A2%85%EB%AA%A9",
            "title": "올림픽/종목",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(3).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        },
        {
            "url": "https://namu.wiki/w/2032%20%EB%B8%8C%EB%A6%AC%EC%A6%88%EB%B2%88%20%EC%98%AC%EB%A6%BC%ED%94%BD",
            "title": "2032 브리즈번 올림픽",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(5).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        },
        {
            "url": "https://namu.wiki/w/%EC%98%AC%EB%A6%BC%ED%94%BD/%EC%A2%85%EB%A5%98",
            "title": "올림픽/종류",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(7).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        },
        {
            "url": "https://namu.wiki/w/%ED%94%BC%EC%97%90%EB%A5%B4%20%EB%93%9C%20%EC%BF%A0%EB%B2%A0%EB%A5%B4%ED%83%B1",
            "title": "피에르 드 쿠베르탱",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(9).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        },
        {
            "url": "https://namu.wiki/w/1896%20%EC%95%84%ED%85%8C%EB%84%A4%20%EC%98%AC%EB%A6%BC%ED%94%BD",
            "title": "1896 아테네 올림픽",
            "_selector": "div:nth-child(1)#cnt > div:nth-child(9)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).mnr-c.g > div:nth-child(2).BYM4Nd > div:nth-child(2) > div:nth-child(2).E8hWLe.SVMeif.BmP5tf > div:nth-child(11).MUxGbd.v0nnCb.lyLwlc > a.q8U8x.tNxQIb.ynAwRc.nEWj3b.OMVs0e.gpHVGb.pj92yd.Cxb6Wc.gsrt > div:nth-child(1).lKeYrd.O45XLd"
        }
    ]
}
```

## Rating

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample3.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample3.json)

![](../../.gitbook/assets/organic\_rating.png)

```
{
    "sequence": 21,
    "type": "organic_results",
    "_selector": "div:nth-child(1)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(21) > div:nth-child(1).mnr-c.xpd.O9g5cc.uUPGi",
    "position": 16,
    "displayed_link": "https://www.justonecookbook.com › ...",
    "title": "Stir-Fried Vegetables (Yasai Itame) (Video) 野菜炒め - Just One Cookbook",
    "url": "https://www.justonecookbook.com/stir-fry-vegetables/",
    "snippet": "Many Japanese home cooks also use a frying pan to cook Yasai Itame. This recipe when cooked on a standard stove may not taste the same as a stir fry vegetable ...",
    "thumbnail": {
        "type": "video",
        "url": "https://www.justonecookbook.com/stir-fry-vegetables/",
        "desc": "stir-fried 동영상"
    },
    "rating": {
        "rating_count": "(68)",
        "rating_value": "4.6"
    }
}
```

## Rich snippet

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample4.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample4.json)

![](../../.gitbook/assets/organic\_rich\_snippet.png)

```
{
    "sequence": 13,
    "type": "organic_results",
    "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(12).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe",
    "position": 11,
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

```
{
   "sequence": 1
   "type": "organic_results"
   "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe"
   "position": 1
   "displayed_link": "https://www.in.or.kr"
   "title": "보험연수원"
   "url": "https://www.in.or.kr/"
   "snippet": "4차산업기술 BIG5! 수강료: 129,360원; 교육기간: 1개월/21시간; 교육형태: 사이버."
   "refinements": [
    {
     "text": "모집종사자"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "회원 로그인"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "자격시험"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "보험심사역"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "주요사업"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "사이버교육"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
    },
    {
     "text": "보험연수원"
     "_selector": "div:nth-child(2)#cnt > div:nth-child(8)#center_col.center_col.s6JM6d > div:nth-child(4) > div:nth-child(2)#rso > div:nth-child(1).MjjYud > div:nth-child(1) > div:nth-child(1) > div:nth-child(1).Ww4FFb.vt6azd.xpd.EtOod.pkphOe > div:nth-child(1).kvH3mc.BToiNc.UK95Uc > div:nth-child(3).Z26q7c.UK95Uc > div:nth-child(1).RXaYnd > div:nth-child(1).Gcxb4e > div:nth-child(1).HTOhZ > div:nth-child(1).EDblX.JpOecb > a.GqbEwc.unhzXb > div:nth-child(1).QRcbWb"
   }
  ]
}
```

## images

[HTML](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample8.html) [JSON](https://ascentkorea-docs.github.io/mobile/features/organic\_results/sample8.json)

![](../../.gitbook/assets/organic\_images.png)

```
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