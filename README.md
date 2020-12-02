# 강의 순서
이론 - 웹스크래퍼 제작 - Django 개발

# 질문할 때 중요한 4가지
1. 무엇을 해내고 싶은지
2. 무엇을 해봤는지
3. 어느 부분이 안되는지
4. error 메시지가 뭔지

# NOTE
## Python variable type
string, number, float, bool, none, list, tuple, dictionary
## Check a built in function
## How to make funcion
def say_hello(who):
## How to make loop
for in
## How to make condition
if, elif, else
## How to import module
import (module name)
from (module name) import (function) as (custom name)

# WebSrapping Process
1. 페이지 이동
2. 페이지 개수 구분
3. 타이틀 확인

# Install packages
requests, beautifulsoup4

# *args, **kwargs
## args
args: 무한하게 넣을 수 있는 parameter
### ex
def plus(*args) - plus(1,1,1,1,1,1)

## kwargs
kwargs: 무한하게 넣을 수 있는 키워드 parameter
### ex
def plus(**kwargs) - plus(hello=True, bye=False, wow="good")

# Extensions
## Flask
Web application framework