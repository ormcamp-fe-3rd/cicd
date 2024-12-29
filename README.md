# CI/CD

![cd workflow](https://github.com/ormcamp-fe-3rd/cicd/actions/workflows/github-actions-cd.yml/badge.svg?branch=main)
![ci workflow](https://github.com/ormcamp-fe-3rd/cicd/actions/workflows/github-actions-ci.yml/badge.svg)

## GitHub actions 테스트

1. repository 클론

```bash
git clone git@github.com:ormcamp-fe-3rd/cicd.git
# or
git clone https://github.com/ormcamp-fe-3rd/cicd.git
```

2. 패키지 설치 & 새로운 브랜치 생성

```bash
npm install
git switch -c [브랜치 이름]
```

3. 코드 수정 후 커밋 & 푸시

```bsh
git commit -m '커밋 메세지'
git push -u origin [브랜치 이름]
```

4. PR 생성
