---
layout: post
title: 주로 사용하는 MySQL 명령어
author: minjae Park
tags:
- MySQL
- commends
date: 2023-06-11 13:00 +0800
---
주로 사용하는 **MySQL 명령어** 에 대해 알아보자!
{: .message }

## MySQL 기본 명령어

DB, 테이블 보기
{% highlight text %}
SHOW
{% endhighlight %}

DB 테이블 만들기
{% highlight text %}
CREATE
{% endhighlight %}

레코드 삽입
{% highlight text %}
INSERT
{% endhighlight %}

데이터 업데이트 
{% highlight text %}
UPDATE
{% endhighlight %}

레코드 삭제
{% highlight text %}
DELETE
{% endhighlight %}

DB,테이블 삭제 
{% highlight text %}
DROP
{% endhighlight %}

각종 정보 수정
{% highlight text %}
ALTER
{% endhighlight %}

cmd창에서 Mysql 접속 명령어
{% highlight text %}
[mysql -u 아이디명 -p] 입력 후
Enter password: 패스워드 입력 
{% endhighlight %}

Database 생성
{% highlight text %}
CREATE DATABASE 데이터베이스명;
{% endhighlight %}

DATAbase 사용 명령어
{% highlight text %}
USE 데이터 베이스 명;
{% endhighlight %}

-Table 생성 명령어
{% highlight text %}
CREATE TABLE 테이블명(
    필드명1 자료형 NOT NULLAUTO_INCREMENT
    필드명2 자료형 NOT NULL
    필드명3 자료형
);
{% endhighlight %}

모든 Table 보여주기
{% highlight text %}
SHOW TABLES;
{% endhighlight %}

Table 구조 보기
{% highlight text %}
1. DESC 테이블명;
2. DESCRIBE 테이블명;
3. EXPLAIN 테이블명;
{% endhighlight %}

Table 데이터 삽입 명령어
{% highlight text %}
INSERT INTO 테이블명() VALUES();
{% endhighlight %}

삽입한 TABLE 모든 데이터 보기
{% highlight text %}
SELECT*FROM 테이블명;
{% endhighlight %}

Database 삭제 
{% highlight text %}
DROP DATABASE 데이터베이스명;
{% endhighlight %}

Table 삭제
{% highlight text %}
DROP TABLE 테이블명;
{% endhighlight %}

필드 추가
{% highlight text %}
ALTER TABLE 테이블명 ADD 필드명 필드타입;
{% endhighlight %}

필드 삭제 
{% highlight text %}
ALTER TABLE 테이블명 DROP 필드명;
{% endhighlight %}

필드 수정 
{% highlight text %}
ALTER TABLE 테이블명 CHANGE 필드명 새필드명 새 필드 타입;
{% endhighlight %}

필드타입 수정 
{% highlight text %}
ALTER TABLE 테이블명 MODIFY 필드명 새 필드타입;
{% endhighlight %}

테이블 이름 수정
{% highlight text %}
ALTER TABLE 테이블명 RENAME 새 테이블명;
{% endhighlight %}

Data 수정 
{% highlight text %}
UPDATE 테이블명 SET 수정될 필드명="값"WHERE 검색 필드명="값";
{% endhighlight %}

DATA 삭제
{% highlight text %}
DELETE FROM 테이블명 WHERE 필드명="값";
{% endhighlight %}

Data 검색 명령어
{% highlight text %}
SELECT볼 필드명 테이블명 WHERE 검색 필드명 ="값";
{% endhighlight %}

 참고 자료 
https://developer88.tistory.com/20