# 온 사전처리기

## 사전처리기란?

이름에서 알 수 있듯이, 사전 처리기는 스크립트가 실행되기 전에 실행된다.  
그들은 디버그 모드 또는 억제 대괄호 오류와 같은 다양한 작업을 수행할 수 있다.

## 사전 처리기 호출

사전처리기는는 #comment 함수를 사용하여 호출할 수 있다.  
사전처리기 키워드로 시작할 수 있으므로 주의하십시오.

```JAVA
#debug 는 내가 가장 좋아하는 단어다. 나는 그것을 주석으로 어디에나 덧붙이고 싶다.
```

↑` modedebug `이 발견되면 디버그 모드를 활성화할 것이다. 이런 희귀한 사례가 발생하지 않도록 하려면, 코멘트는 `//`을 사용하십시오.