# 웹폰트
무료 폰트를 웹폰트로 사용하기

## 나눔글꼴 
네이버에서 만들어 무료로 배포한 나눔글꼴을 웹폰트로 만들었습니다.
[나눔글꼴이야기 PDF 보기][nanum story]

### 나눔바른고딕
#### 불러오기
**link**
웹사이트 HTML문서의 ``<head>``안에 아래 코드를 넣으면 됩니다.
```
<!-- Regular -->
<link href="https://cdn.rawgit.com/YJSoft/Webfonts/0.1/NanumBarunGothic.css" rel="stylesheet" type="text/css" />
<!-- Bold -->
<link href="https://cdn.rawgit.com/YJSoft/Webfonts/0.1/NanumBarunGothicBold.css" rel="stylesheet" type="text/css" />
```

**@import**
CSS파일 및 ``<head>``안의 스타일 시트에 아래 코드를 넣으면 됩니다.

**Regular**
```
@import url('https://cdn.rawgit.com/YJSoft/Webfonts/0.1/NanumBarunGothic.css');
```
**Bold**
```
@import url('https://cdn.rawgit.com/YJSoft/Webfonts/0.1/NanumBarunGothicBold.css');
```

#### 사용 예
```
<style type="text/css">
.nanumbg{font-family:'NanumBarunGothic','나눔바른고딕', sans-serif; }
</style>
<span class="nanumbg">한나체</span>
```

## 우아한 형제들

### 배달의 민족 한나체
한나체 [라이센스 보기][license1]

#### 불러오기
**link**
웹사이트 HTML문서의 ``<head>``안에 아래 코드를 넣으면 됩니다.
```
<link href="https://cdn.rawgit.com/YJSoft/Webfonts/0.1/BM_HANNA.css" rel="stylesheet" type="text/css" />
```

**@import**
CSS파일 및 ``<head>``안의 스타일 시트에 아래 코드를 넣으면 됩니다.
```
@import url('https://cdn.rawgit.com/YJSoft/Webfonts/0.1/BM_HANNA.css');
```

#### 사용 예
```
<style type="text/css">
.hana{font-family:'BM HANNA','배달의민족 한나', sans-serif; }
</style>
<span class="hana">한나체</span>
```

**배달의 민족 주아체**
주아체 [라이센스 보기][license2]

#### 불러오기
**link**
웹사이트 HTML문서의 ``<head>``안에 아래 코드를 넣으면 됩니다.
```
<link href="https://cdn.rawgit.com/YJSoft/Webfonts/0.1/BM_JUA.css" rel="stylesheet" type="text/css" />
```

**@import**
CSS파일 및 ``<head>``안의 스타일 시트에 아래 코드를 넣으면 됩니다.
```
@import url('https://cdn.rawgit.com/YJSoft/Webfonts/0.1/BM_JUA.css');
```

#### 사용 예
```
<style type="text/css">
.jua {font-family:'BM JUA','배달의민족 주아',sans-serif;}
</style>
<span class="jua">주아체</span>
```

##적용하기
폰트를 적용하려면 폰트 이름을 적용하길 원하는 CSS에 다음과 같이 추가하면 됩니다.
```
font-family: 'NanumBarunGothic', '나눔바른고딕', sans-serif;
```

[nanum]: http://fonts.googleapis.com/earlyaccess/nanumgothic.css
[nanum story]: http://static.campaign.naver.com/0/hangeul/2014/doc/nanum_story.pdf
[license1]: http://www.woowahan.com/license.html?keepThis=true&TB_iframe=true&height=620&width=659&modal=true
[license2]: http://www.woowahan.com/license-jua.html?keepThis=true&TB_iframe=true&height=620&width=659&modal=true
[issues]: https://github.com/YJSoft/Webfonts/issues
