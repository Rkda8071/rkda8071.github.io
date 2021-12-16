Read Only - 테마 사용

[https://github.com/old-jekyll-templates/Read-Only-Jekyll-Theme](https://github.com/old-jekyll-templates/Read-Only-Jekyll-Theme)

Header에 Home, Connect, Blog가 있었는데, 내가 사용할 것은 Blog뿐이었기에 Home, Connect를 _include/head.html에서의 해당 항목을 삭제, 또한 테마의 프로필 소개, 사진의 dummy file을 수정하였다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3e72061-4802-4c3f-93c7-4e4c774d9832/Untitled.png)

그런데 github에 업로드한 후 [https://rkda8071.github.io/](https://rkda8071.github.io/)에 접속해봤더니 테마 적용이 제대로 되지 않았다...

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b494249a-f6fc-475f-9aba-a51411a85da1/Untitled.png)

_config.yml의 baseurl과 url을 ""으로 수정해주었더니 [github.io](http://github.io)에서도 정상적으로 작동하였다!
