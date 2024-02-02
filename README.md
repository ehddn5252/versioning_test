# versioning_test

## Git log format

```
%H
커밋 해시

%h
짧은 길이 커밋 해시

%T
트리 해시

%t
짧은 길이 트리 해시

%P
부모 해시

%p
짧은 길이 부모 해시

%an
저자 이름

%ae
저자 메일

%ad
저자 시각 (형식은 –-date=옵션 참고

%ar
저자 상대적 시각

%cn
커미터 이름

%ce
커미터 메일

%cd
커미터 시각

%cr
커미터 상대적 시각

%s
요약
저자(%an)와 커미터(%cn)구분하는 것은 자료룰 수정한 사람과 직접 커밋을 한 사람이 다를 경우에 의미를 가집니다.
```

## 예시

git log --pretty=format:"%h - %an, %ar : %s"










https://creampuffy.tistory.com/129#1.%20%EC%BB%A4%EB%B0%8B%20%EB%A9%94%EC%8B%9C%EC%A7%80%20%EC%BB%A8%EB%B2%A4%EC%85%98%EC%9D%98%20%ED%95%84%EC%9A%94%EC%84%B1-1

Conventional Commits(https://www.conventionalcommits.org/ko/v1.0.0-beta.4/)


https://docs.github.com/ko/repositories/releasing-projects-on-github/automatically-generated-release-notes