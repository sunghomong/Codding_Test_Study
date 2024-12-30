[문제 링크](https://school.programmers.co.kr/learn/courses/30/lessons/181863)

## 문제 인식

1. rny_string : 문자열
2. 'm' 을 'rn' 으로 변환

## 문제 접근

- .replace 메서드 활용

## 코드

```java
class Solution {
    public String solution(String rny_string) {
        return rny_string.replace("m","rn");
    }
}
```