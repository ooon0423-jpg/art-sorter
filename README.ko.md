<p align="center"><img src="docs/icon.png" width="96" alt="Art Sorter 아이콘"></p>

<h1 align="center">Art Sorter</h1>

<p align="center"><b>일러스트, 팬아트, AI 생성 그림 수천 장을 캐릭터와 장면별로 줄 세우는 윈도우 프로그램. 그림 파일은 올리지 않습니다.</b></p>

<p align="center">
<a href="https://orilabs.studio/artsorter/ko/?utm_source=github">홈페이지</a> ·
<a href="https://orilabs.studio/artsorter/ko/get/?utm_source=github">Windows용 내려받기</a> ·
<a href="https://orilabs.studio/artsorter/ko/guides/?utm_source=github">가이드</a> ·
<a href="README.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.zh.md">简体中文</a>
</p>

<p align="center"><img src="docs/before-after.jpg" alt="같은 그림들. 왼쪽은 뒤섞인 상태, 오른쪽은 Art Sorter가 캐릭터와 장면별로 세운 줄" width="820"></p>

폴더를 끌어다 놓으면 파일 이름이 아니라 그림을 보고 한 줄로 세웁니다. 같은 캐릭터끼리, 그다음 같은 장면끼리, 그다음 이어지는 순서로. 크기만 다른 사본까지 따로 모아 둡니다. 전부 내 PC에서 돕니다.

> 이 저장소는 설명서와 공개 문의 게시판입니다. Art Sorter 자체는 무료 체험이 있는 비공개 소스 PC 프로그램입니다.

## 할 수 있는 것

- **캐릭터별로 묶기.** 일러스트로 학습한 모델이 다른 날, 다른 작가의 그림이라도 같은 캐릭터를 한데 모읍니다.
- **그다음 장면과 순서.** 캐릭터 안에서 장면별로, 그다음 이어지는 순서로 세웁니다.
- **중복은 따로.** 똑같은 사본, 크기를 줄이거나 형식을 바꾸거나 다시 저장한 사본을 따로 모아 비교하게 합니다. 아무것도 지우지 않습니다.
- **다시 정리 없이 추가.** 새 그림은 닮은 그림 옆에 끼웁니다. 손봐 둔 순서는 그대로입니다.
- **어디서 왔는지도 봅니다.** 한 폴더, 또는 같은 이름 꼴의 그림이 대부분 한 무리에 모이면 떨어져 나간 몇 장을 되찾아 옵니다.
- **이름은 한 번만.** 그림을 고르고 이름을 넣으면 한꺼번에 바뀝니다. 건드리면 안 되는 묶음은 고정합니다.
- **전부 되돌리기.** 모든 단계를 되돌릴 수 있고, 옮긴 파일은 한 번에 원래 폴더로 돌아갑니다.
- **태그 내보내기.** Hydrus 사이드카, digiKam·XnView MP용 XMP, Eagle, CSV. 원본은 바뀌지 않습니다.
- **큰 모음도.** 한 번에 수만 장, 멈췄다 이어서 할 수 있습니다.
- **화면 언어 18개.**

[![2분 30초 시연 영상](docs/sort-animation-poster.jpg)](https://youtu.be/OSMyfuTyGz8)

실제 결과: 시연용 113장(캐릭터 3명, 장면 4개씩)을 노트북에서 약 2분 30초 만에 정리했고, 끝에 2장이 어긋났습니다.

## 누구를 위한 프로그램인가
- **패트리온·팬박스·판티아**에서 작가 여러 명을 후원하고 작품을 전부 받아 두는 분: 작가별 폴더는 있지만, 그 안은 세트·차분·다시 받은 중복이 섞여 있습니다.
- **Stable Diffusion, NovelAI, Midjourney, ComfyUI**로 많이 뽑고 결과물을 캐릭터별·장면별로 나누고 싶은 분.
- **X·픽시브·디스코드**에서 저장한 이름 제각각인 그림이 수천 장인 분.
- **만화 컷, CG 세트, 스크린샷**을 모으고 정한 순서대로 두고 싶은 분.
- 폴더가 압축 안의 압축이 되어 버린 모든 분.

## 개인정보

Art Sorter는 웹 서비스가 아니라 PC 프로그램입니다. 가입이 없고, 그림 파일은 올리지 않습니다. 캐릭터와 장면 인식은 내 PC에서 합니다. 순서를 맞출 때는 그림 자체가 아니라 그림을 설명하는 숫자 정보를 정리 서버로 보내고, 서버는 이를 메모리에서만 처리하고 저장하지 않습니다. 그래서 정리할 때는 인터넷 연결이 필요합니다. 자세한 내용은 [개인정보 처리방침](https://orilabs.studio/artsorter/privacy.html)에 있습니다.

그 밖에 인터넷을 쓰는 것: 업데이트 확인, 처음 켤 때 한 번 받는 분석 모델, 익명 PC 코드로 하는 라이선스 확인.

## 사양

| | |
|---|---|
| 운영체제 | Windows 10 / 11 (64비트) |
| 메모리 | 8GB (3만 장 넘으면 16GB 권장) |
| 디스크 | 약 1.5GB. 설치 파일 200MB, 분석 모델 840MB는 처음 한 번 받음 |
| 그래픽카드 | 없어도 됨. DirectX 12 그래픽카드가 있으면 알아서 씀 |

## 가격

- **무료 체험이 폴더 전체를 정리해** 결과를 보여 줍니다. 300장은 원본으로 남기고, 나머지는 구매 전까지 저해상도 미리보기입니다. 원본 파일은 옮기거나 바꾸지 않습니다. 가입도 카드도 필요 없습니다.
- [Microsoft Store](https://apps.microsoft.com/detail/9MSZX5KNTVR0?cid=github)에서도 받을 수 있습니다(Windows 경고 화면 없이 설치).
- 그 뒤에는 **한 번 구매**(구독 아님). 키 하나에 PC 한 대, 업데이트 전부 포함.
- 지금 가격은 [홈페이지 가격 칸](https://orilabs.studio/artsorter/ko/?utm_source=github#pricing)에서 보실 수 있습니다.

## 가이드

- [AI 그림 수천 장 정리하는 법](https://orilabs.studio/artsorter/ko/guides/organize-ai-images/?utm_source=github)
- [크기만 다른 사본까지 중복 이미지 찾기](https://orilabs.studio/artsorter/ko/guides/find-duplicate-images/?utm_source=github)
- [애니·팬아트 그림을 캐릭터별로 자동 정리하기](https://orilabs.studio/artsorter/ko/guides/sort-by-character/?utm_source=github)
- [Eagle 대신 쓸 만한 프로그램](https://orilabs.studio/artsorter/ko/guides/eagle-alternative/?utm_source=github)
- [Hydrus 대신 쓸 만한 프로그램](https://orilabs.studio/artsorter/ko/guides/hydrus-alternative/?utm_source=github)
- [gallery-dl로 받은 그림 정리하기](https://orilabs.studio/artsorter/ko/guides/organize-gallery-dl-downloads/?utm_source=github)
- [패트리온·팬박스 후원 팩 정리하기](https://orilabs.studio/artsorter/ko/guides/organize-patreon-fanbox-packs/?utm_source=github)
- [픽시브에서 저장한 그림 정리하기](https://orilabs.studio/artsorter/ko/guides/organize-pixiv-collection/?utm_source=github)

## 문의와 오류 제보

틀리게 정리되는 폴더를 찾으셨다면 그게 가장 도움이 되는 제보입니다. [문의 게시판](../../issues/new/choose)에 몇 장이었는지, 대략 어떤 그림이었는지, 무엇이 틀렸는지 적어 주세요. 캡처도 좋지만 공개되어도 괜찮은 그림만 올려 주세요.

메일: contact@orilabs.studio

---

한국의 1인 스튜디오 오리랩스(OriLabs Studio)가 만듭니다.
