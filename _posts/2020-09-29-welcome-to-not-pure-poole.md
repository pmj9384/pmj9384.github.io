---
layout: post
title: 주로 사용하는 GitHub 명령어 모음 
date: 2023-06-11 03:44 +0800
last_modified_at: 2023-06-11 03:44:44 +0800
tags: [GitHub,command]
toc:  true
---
주로 사용하는 **GitHub 명령어** 에 대해 알아보자!
{: .message }

## GitHub 기본 명령어

현재 상태 확인 
{% highlight text %}
git status
{% endhighlight %}

전체 로그 확인
{% highlight text %}
git log
{% endhighlight %}

git 저장소 생성
{% highlight text %}
git init
{% endhighlight %}

저장소 복제 
{% highlight text %}
git clone [https: ~~]
{% endhighlight %}

저장소에 코드 추카
{% highlight text %}
git add 
{% endhighlight %}
{% highlight text %}
git add * 
{% endhighlight %}

커밋 파일의 변경 부분 한번에 포함 
{% highlight text %}
git add -A 
{% endhighlight %}

커밋 생성 
{% highlight text %}
git commit -m "message"
{% endhighlight %}

변경사항 push
{% highlight text %}
git push origin master 
{% endhighlight %}

원격 저장소 변경내용 가져오기 (pull)
{% highlight text %}
git pull
{% endhighlight %}

## Git Branch 

git 파일 생성
{% highlight text %}
git init
{% endhighlight %}

github  주소 연결
{% highlight text %}
git remote add origin [github 주소]
{% endhighlight %}

브랜치 생성
{% highlight text %}
git branch [브랜치 명]
{% endhighlight %}

해당 브랜치 이동
{% highlight text %}
git checkout [브랜치 명]
{% endhighlight %}

원하는 브랜치 이동 확인
{% highlight text %}
git branch
{% endhighlight %}

파일 폴더 add
{% highlight text %}
git add.
{% endhighlight %}

커밋
{% highlight text %}
git commit -m "commit message" 
{% endhighlight %}

원하는 브랜치로 push 원격 서버로 전송
{% highlight text %}
git push origin [브랜치명]
{% endhighlight %}

브랜치 삭제
{% highlight text %}
git branch -d [브랜치 이름]
{% endhighlight %}

현재 브랜치에 다른 브랜치 수정사항 병합
{% highlight text %}
git merge [다른 브랜치 명]
{% endhighlight %}

## Git Config

전체 config 리스트 확인
{% highlight text %}
git config --list
{% endhighlight %}

git config 설정 
{% highlight text %}
git config --global user.name "아무개"
git config --global user.email "name@naver.com"
{% endhighlight %}

git config 삭제

{% highlight text %}
git config --unset user.name
git config --unset user.email
{% endhighlight %}

참고 자료 
https://eehoeskrap.tistory.com/666