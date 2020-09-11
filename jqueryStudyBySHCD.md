# <center>JQUERY "studied by 생활코딩"</center>

## 1. JQUERY 기초
jquery 는 기존에 존재하던 브라우저간의 호환문제, ECMA 가 안착되기 전 난해한 코드등의 문제로 발달하기 시작한 **라이브러리** 이다. jquery 는 밑의 3가지 특징을 가진다.

* 엘리먼트를 선택하는 강력한 방법 제공
* 선택된 엘리먼트들을 효율적으로 제어할 수 있는 다양한 수단 제공
* javascript 의 라이브러리

## 2. jquery 사용방법

### 1. 직접 API 다운

jquery는 기본적으로 javascript의 라이브러리 중 하나로 파일로 저장하여 사용할 수 있다.
밑의 링크에 접속하여 jquery Download the compressed, production jQuery 3.5.1 를 클릭하여 다운하고 컴퓨터에 원하는 경로에 저장을 한다.(제이쿼리 링크 클릭 후 소스파일이 뜨면 ctrl + s 로 저장)

[jquery 다운로드 링크](https://jquery.com/download/)

* html 적용방법
```html
<script type="text/javascript" src="파일경로/jquery-3.5.1.min.js"></script>
```

### 2. CDN 링크 이용

구글에서 제공하는 jquery 링크를 이용하는 방법이다.

* html 적용방법
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
```

### 3. jQeury 최신버전 URL 이용

jquery에서 제공하는 최신 버전을 URL 을 통해 이용하는 방법이다.

* html 적용방법
```html
<script src="http://code.jquery.com/jquery-latest.js"></script>
```

## 3. jQuery 문법

### 1. jQuery의 기본문법

`$(제어대상).method1().method2().method3();`
`$(제어대상)` 부분은 주어 `method1().method2().method3();` 부분은 서술어로 볼 수 있다.

<span style = "font-size:small">**[SOURCE]**</span>

```html
<html>
  <body>
    <div class="welcome"></div>
    <div class="welcome"></div>
    <script src="http://code.jquery.com/jquery-latest.js"></script>
    <script>
      $('.welcome').html('hello world!').css('background-color','red');
    </script>
  </body>
</html>
```
<span style = "font-size:small">**[BROWSER]**</span>

<img src="/imgFolder/jqueryStudyImg1.png">

### 2. 래퍼 <span style="font-size : medium"> Wrapper</span>
