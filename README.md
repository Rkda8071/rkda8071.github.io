Read Only - 테마 사용

https://github.com/old-jekyll-templates/Read-Only-Jekyll-Theme

Header에 Home, Connect, Blog가 있었는데, 내가 사용할 것은 Blog뿐이었기에 Home, Connect를 _include/head.html에서의 해당 항목을 삭제, 또한 테마의 프로필 소개, 사진의 dummy file을 수정하였다.

그런데 github에 업로드한 후 https://rkda8071.github.io/에 접속해봤더니 테마 적용이 제대로 되지 않았다...

_config.yml의 baseurl과 url을 ""으로 수정해주었더니 github.io에서도 정상적으로 작동하였다!

또한 https://chinsun9.github.io/2020/11/20/github-blog-page-google-analytics%EB%A1%9C-%EC%B8%A1%EC%A0%95%ED%95%98%EA%B8%B0/ 름 참고하여 Google Analystics 기능을 추가해주었다.

https://favicon.io/emoji-favicons/thinking-face/
이곳에서 원하는 favicon을 다운받고 /_includes/head.html에 코드를 작성하여 favicon을 적용하였다.
