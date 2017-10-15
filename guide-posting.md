---
layout: entry
---

# 블로그 포스팅 가이드

> 업데이트 이력  
> 
> 2017.10.15 - 초안 작성  

## Front Matter

아래 Front Matter에서 ***title, description, author.github, cover_image***를 포스팅 목적에 맞게 수정하면 됩니다.  

- title  
  - 글 제목  
- description   
  - 글 부제  
- author.github  
  - 작성자의 github id  
- cover_image  
  - 포스팅 커버이미지
  - 작성하지 않으면 여개모각코 블로그 사이트의 대표 이미지가 표시됨  
  - 이미지 url을 작성하거나(권장)  
  - 블로그의 images에 업로드하여 이용함  

### Front Matter 작성 예시  

```markdown
---
layout: entry 
category: blog
publish: true
title: 1기 알파팀 세미나 후기
description: 알파팀이 지난 9월 30일, 완주하여 세미나를 개최하였습니다.
author:
  github: kaylais
cover_image: https://c1.staticflickr.com/5/4462/37333521080_c7ceeb35c6_b.jpg
---
```

## 포스팅 작성 정책

### 이미지  

이미지는 캡션을 작성  
![여개모각코 1기 알파팀 세미나](https://c1.staticflickr.com/5/4462/37333521080_c7ceeb35c6_b.jpg)  
![여개모각코 로고](/images/logo.png)    
  
```markdown
![여개모각코 1기 알파팀 세미나](https://c1.staticflickr.com/5/4462/37333521080_c7ceeb35c6_b.jpg)  
![여개모각코 로고](/images/logo.png)  
```

### 이미지 크기  

markdown 형태의 이미지 작성 방법은 크기를 조절할 수 없음  
이때는 html ***img*** tag로 작성을 해야함  

<img src="/images/logo.png" alt="여개모각코 로고" width="150">  

```markdown
<img src="/images/logo.png" alt="여개모각코 로고" width="150">  
```

### 내부 링크  

내부 링크는 markdown에서 제공하는 방식으로 작성    
[1기 알파팀 소개 링크](/teams/1st-alpha)  

```markdown 
[1기 알파팀 소개 링크](/teams/1st-alpha)  
```  

### 외부 연결 링크

외부 연결 링크는 html ***a*** tag를 이용하고, ***target="_blank"***를 필수로 작성

```markdown
- 신청 날짜에 <a href="http://cafe.naver.com/womendevel" target="_blank">여자개발자모임터 카페</a>에 작성 된 글 참고  
```

### 타이틀 태그

포스팅 자체의 글 제목이 ***h1*** tag이므로 포스팅의 문단별 타이틀 시작은 ***h2*** tag부터 시작함  
***#*** 기호 개수 만큼 ***h*** tag에 대응함  
 

```markdown
## 2기 운영 계획
  
운영 일자
- 2017년 11월 04일 ~ 2018년 01월 06일  
- 총 8회 모임  
- 2017년 12월 23일과 30일은 연말을 고려하여 공식적인 모임은 없음

### 목표 작성 예시2
```text
목표 : 코세라 스칼라(Functional Programming Principles in Scala) 강의 week1 ~ week6 수강 완료 및 과제 풀이   
```  

### 문장 개행  

markdown은 문장 개행을 ***공백 2개*** 또는 ***&lt;br&gt;*** tag로 함  

```text
안녕하세요?  
여개모각코 케일라입니다.  
```
