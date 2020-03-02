---
layout: post
title:  "지킬을 설치해보자"
date:   2020-02-29 23:19:32 +0900
categories: jekyll Setting
---

# Window 에서 스스로 지킬을 설치하기!!


1. 지킬을 설치하기 위해선 Ruby가 필요.   
Link: [Ruby 다운로드](https://rubyinstaller.org/downloads/)   
![다운로드 페이지 이미지]({{ "/assets/images/ruby.png" | relative_url }})

2. 루비를 설치했으면 이제 터미널을 이용하여 jekyll 설치가 가능하다.
본인은 VSCODE를 이용한 터미널로 설치를 하였다!

3. VSCODE에서 터미널을 연후

		> gem install jekyll
		> jekyll -v   // 버전확인
		> jekyll new 폴더명으로 설치
		> cd 설치한 폴더로 이동
		> bundle install
		> bundle exec jekyll server 입력

서버가 기동되면서 http://localhost:4000에 접속하여 동작을 확인한다.