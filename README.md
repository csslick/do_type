# do_type plug-in 
- version: 0.1
- 2020.06.02 By csslick

## Demo Page  
https://csslick.github.io/do_type/

## 사용법
- 적용할 요소에 클래스명 do_type을 추가
- 요소 내의 title 속성에 텍스트 값을 입력
- 중간에 특수문자(*)를 추가하면 줄내림 처리됨

```
<body>

  <h1 class="do_type" title="Hello, my name is Hong Gil Dong.*I do creative">title</h1>
  <p title="hello,* my name is kwon">type</p>
  
  <!-- Plug-in Here(플러그인) -->
  <script src="./do_type.js"></script>
  
  <!-- Your Script(작성 스크립트) -->
  <script>
    // Initailize
    do_type.init();
    
    // run auto type
    do_type.type('element name');  
  </script>
  
</body>
```
