# Minimal-mistakes를 이용하여 github 블로그 만들기

기존에는 티스토리 블로그를 사용하고 있었다. Notion을 이용하면서 마크다운이 얼마나 편한지 새삼 느끼게 되어 github 블로그로 옮길까 말까 고민하다가 너무 마음에 드는 테마를 발견하여 github 블로그로 옮기기로 마음 먹었다. 

# Minimal Mistakes

Jekyll을 기반으로 만들어진 테마이다. 해당 [링크](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)로 가면 데모와 이용하는 방법을 알 수 있다. 

![Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled.png](Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled.png)

구조도 깔끔하고 무엇보다 오른쪽에 TOC가 있는게 마음에 들었다. 내가 보던 블로그에 TOC가 있으니 훨씬 글이 구조 있게 잘 읽혔다.

# 블로그 생성

Github 블로그를 만들 예정이라면 간단하다. 해당 테마의 github 디렉터리를 fork 하기만 하면 일단 만들어진다. 설치 가이드에 보면 친절하게 자동으로 해당 디렉터리를 fork해서 만드는 링크를 올려놨다.  

## Starter 버전

좀 더 간단하게 github 블로그를 만들 수 있다. 정말 필요한 기능만 깔끔하게 있어서 사용하기 편하다. 다만 제공되지 않는 기능도 있다. [사이트](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)에서 아래 사진에서 보이는 링크를 클릭하면 자동으로 저장소를 만들어준다. 

![Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%201.png](Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%201.png)

위 링크를 클릭하면 아래와 같은 화면이 뜬다. 여기서 `username.github.io`로 이름을 바꾸고 생성해주면 된다. 

![Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%202.png](Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%202.png)

이러면 끝이다. 블로그가 잘 개설되었는지 github 저장소 setting에 들어가서 확인해본다. (`username/username.github.io`)

![Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%203.png](Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%203.png)

## 일반 버전

Starter 버전은 설명서와 좀 다르기도 하고 지원하지 않는 기능들도 있는 것 같다. 일반 버전으로 만들고 싶다면 해당 [링크](https://github.com/mmistakes/minimal-mistakes)에서 fork를 한다. 나머지 과정은 위와 동일하다. 

[https://jeonghwarr.github.io/](https://jeonghwarr.github.io/) 이 링크로 내 블로그가 만들어졌다. 

![Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%204.png](Minimal-mistakes%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%8B%E1%85%A7%20github%20%E1%84%87%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%209e39c4a312654bcc80b1c37872511809/Untitled%204.png)

블로그가 만들어졌다. 이제 이 블로그를 커스터마이징 해야 한다.

관련해서 참고할만한 좋은 사이트가 있어서 추천한다. 

[하우투: 같이 따라하기 시리즈](https://devinlife.com/howto/)