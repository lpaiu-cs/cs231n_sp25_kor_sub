# cs231n spring 2025 한글번역 (korean subtitles)
Stanford cs231n 2025년 봄학기 유튜브 영상의 한글 자막 번역입니다.

영상 플레이리스트: [CS231N Spring 2025 Playlist](https://youtube.com/playlist?list=PLoROMvodv4rOmsNzYBMe0gJY2XS8AQg16&si=usJZq4ZMXOzC0GtE)

학업계획서, 과제, 강의 슬라이드는 사이트 참고: [CS231n Website](http://cs231n.stanford.edu/)

---------
## 알려드립니다 (Announcements)
> cs231n sp25의 한글 자막 번역입니다.
> 자막번역은 gpt4o-mini api를 이용하였습니다.
> 앞으로 영어 실력의 중요성은 점차 낮아질 것이라 생각합니다. 학문적 맥락을 이해할 수 있는 정도의 언어 능력은 여전히 필요하겠지만, 앞으로 보다 기술혁신에 의해 언어장벽이 점차 낮아지길 기원합니다.
> 또한 아직도 너무 많은 사람들이 영어가 주는 지나치게 높은 지식 장벽 때문에 학업에 어려움을 겪고 있습니다. 그러한 분들께 이 번역 프로젝트가 도움이 되길 바랍니다.

버그 문의는 lpaiu.cs@gmail.com 으로 부탁드립니다. (2025.09.09)

----------
## Update

### 2025.09.29

전체 번역본 재업로드 (프롬프트 수정)
> sys_prompt = "You are a precise subtitle translator. Translate English to Korean succinctly, preserving meaning and tone. Do NOT add, remove, merge, split, or reorder items. If an input item is an empty string, return an empty string in the same position. Return a JSON array of strings with EXACTLY one Korean translation per input item. Context: These subtitles are the Stanford CS231n lecture on computer vision and deep learning. If certain English words (e.g., technical terms, names, acronyms) would lose meaning when translated, keep those words in English. Translate in a spoken, explanatory lecture style (like a professor talking to students). Use polite Korean sentence endings consistently (e.g. 습니다체; '~입니다', '~할 수 있습니다'), but allow occasional softer variations such as '~하는 거죠', '~라는 겁니다' to sound natural in lecture context."

----------
## 교수자 (Instructors)
    Fei-Fei Li    : https://profiles.stanford.edu/fei-fei-li 
    Ehsan Adeli   : https://stanford.edu/~eadeli/  
    Justin Johnson: https://web.eecs.umich.edu/~justincj/
    Zane Durante  : https://zanedurante.github.io/

----------
## 필요사항 (Requirements)
    강의 수강을 위해서는 강의영상과 자막을 싱크할 플레이어가 필요합니다
        추천 플레이어
            Windows : PotPlayer(kakao)
            Linux   : SM Player
            MacOS   : VLC 미디어 재생기

----------
## 사용법 (Usage)

1. 유튜브에서 영상을 다운로드 해야 합니다
    - 다음과 같은 비디오 다운로더가 필요합니다 [4k video downloader](https://www.4kdownload.com/ko/products/product-videodownloader)
    - 다음 플레이리스트의 강의를 다운로드 하세요 [cs231n sp25 Playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rOmsNzYBMe0gJY2XS8AQg16)
    
2. 해당 프로젝트 파일을 다운로드 합니다. (주의: 영상과 같은 곳에 자막파일 .srt를 놓아야 합니다. mp4 파일과 이름이 같아야합니다.)

        root
        └── eng
            └── Subtitles in English
        └── kor 
            └── 한글 자막       <-- 한글 자막이 나오기 원하면 영상을 이곳에 넣어야 합니다. (vlc 기준)

----------
## LICENSE
MIT
