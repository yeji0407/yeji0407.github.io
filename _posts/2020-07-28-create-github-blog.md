---
title: "Github Blog 만들기"
date: 2020-07-28 18:43:28 -0400
categories: open source
---


<br/><br/>
참고링크: .[https://dreamgonfly.github.io/blog/jekyll-remote-theme/](https://dreamgonfly.github.io/blog/jekyll-remote-theme/)

<br/><br/><br/><br/>

1. 새로운 Repository 생성

    이때 repository 의 이름은 [아이디].github.io 로 설정한다.

<br/><br/>

2. 테마 고르기

    https://github.com/topics/jekyll-theme
    
    위 링크에서 마음에 드는 테마를 고른다.
    
<br/><br/>

3. 내 repository 에 _config.yml 파일을 생성하고 위에서 고른 프로젝트의 _config.yml 파일 복붙하기

    해당 파일에 remote_theme : [제작자이름]/[저장소이름]
    
    한 줄을 추가한다.
    </br>
    url : "https://[아이디].github.io"
    
    한 줄을 위와 같이 수정한다.
    
<br/><br/>

4. 원본 프로젝트의 index.md 등 폴더 밖에 있는 md 파일들을 내 저장소에 가져온다. (내가 고른 테미는 어떤 파일을 가져와야 하는지 모르겠어서 다 가져왔다..)

<br/><br/>

5. 글 올리기

    create new file 을 클릭하고 파일 이름을 _posts/2020-07-28-first-post.md 와 같이 입력한다. 이렇게 하면 자동으로 _posts 폴더가 생성되고 앞으로 이 폴더 안에 글을 쓰면 된다.
    
    깃허브 블로그에 글을 올릴 땐 마크다운 (.md) 파일 형태로 올려야 한다.
