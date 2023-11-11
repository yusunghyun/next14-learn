## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Next learn 후기/메모

next는 한번 써봤고 스터디에서 책도 한바퀴 돌려보고 공식문서도 한바퀴 돌려보았지만 내 자신감의 **기준**에는 달성하지 못했다.(= 강의할 수 있을 정도의 마음가짐) 이번에 **next 14**가 나오면서 next learn 페이지가 나왔는데 다시금 영어공부 + 개발공부 를 도전해보려고 한다.

`영어공부` + `개발공부`를 동시에 하고 싶었는데 별에별거를 했지만 효과가 좋지 못했다… <함께자라기>에서 말하기를 1단계 더 어려워야 `몰입`을 할 수 있다고… 일단 나는 `영어`로 `난이도 올리기`를 진행했는데 어려운 기술이나 난해한 기술로도 `난이도`를 올려버려서 `버거웠다.`

조금 진행해본 소감은.. 너무 좋다! `이미 아는 내용에 디테일`을 얹는 학습과 `영어 리딩 속도`가 점진적으로 증가함이 느껴진다…! 그리고 자진해서(필요한 상황이 아님에도) 공식문서를 `정독`한다는 행위가 나의 경험에 좋은 레퍼런스로 다가왔다..! (한번이 어렵지 두번은 쉬우니)

- 1강
    - 작은 재무대시보드를 만들 것
    - example을 제공함
    - 모든 코드를 이해할 필요 없다
    - next feature을 학습하기 위해 미리 준비했다.
    - 여러분들을 높은 확률로 이미 코드베이스가 있는 곳에서 일할 것
- 2강
    - tailwind 에 대해서
    - 스타일링할 걱정하지마라 우리가 알아서 해준다
    - css module 맛보게 해줌
    - 진짜진짜 처음 하는 사람을 위한 learn 같다 너무 친절하고 하나도 안귀찮게 해서 P에게는 최고이다.
    - 흥미가 멈추지 않는다
- 3강
    - 통신을 태우지 않고 build 때 font최적화를 해준다
    - 귀여운 폰트 사용 실습하는데 기준비된 컴포넌트들이 잘되어있어서 게임을 깨는 느낌이 좋당ㅎㅎ
    - 이미지
        - 동일한 비율의 사이즈를 픽셀로 기선언하는건 좋은 방식이다
        - md:block 이 tailwind의 미디어쿼리였다!
        - 그냥 사용법만 배운다
- 4강
    - 배울것
        - 라우트 파일 시스템을 배워보다
        - 폴더 룰을 배우자
        - 레이아웃 사용법을 배우자
        - 중첩라우팅
    - app route에서 코어 동작들을 배우는데 이미 아는 내용이라 시시할 뻔 했지만 colocate 라는 무슨 뜻인지도 모르는 단어 덕에 ‘몰입’에 도움이 되었다.
    - page.tsx가 있어야 라우트다.
    - 중첩라우팅 해보는 실습. 쉽다.
    - 
    - 여기까지 2시간 소요되었다.
        - 영어해석하고, 진지하게 읽기
    - layout 리랜더링 방지 가능하다
    - 미리 버셀이 만들어준 탭아이콘 등등 덕에 귀찮고 막막한 부분이 모두 해소되고 가닥이 잡혀간다 개뀰
    - 루트 레이아웃은 필수이고 모든 곳에 적용됨

여기까지 2시간 소요

---

- 5강
    - 배울것
        - next/link
        - usePathname
        - How navigation work
    - 대부분의 사람들은 HTML,mdn의 여러 기능들을 외우면서 쓰는데, 앞으로는 Next가 그렇게 되버릴까?(몇몇 아웃라이어 제외)
    - a -> Link
        - without full refresh!
        - 이유는 Automatic code-splitting and prefetching
            - route segments를 바탕으로 자동으로 코드스플리팅을 한다.
            - 이는 격리됨을 의미하고 따라서 에러가 나도 죽지않는다.
            - 백그라운드에서 넘어갈곳을 자동으로 프리패치한다. 그래서 즉각전환처럼 보임ㄷㄷ
    - usePathname
        - client 사이드에서만 가능
        - clsx와 함께 동적으로 랜더링가능
        - layout이라서... 랜더링 이점 또한 있겠지..?
        
    
