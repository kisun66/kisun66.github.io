---
title: "Git 롤백"
strapline: "Git 롤백"
description: 
header:
 overlay_image: /assets/images/top_2.png
categories:
  - "Git"
tag:
  - "Git"
toc: true
last_modified_at: 2021-04-09
comments: true
---

### Git 롤백
---
reset과 revert는 원하는 커밋까지 롤백시키는 명령어로 다음과 같은 차이점이 있다.

- reset은 커밋 이력(Histroy)을 남기지 않고 특정 커밋까지 되돌린다.
- revert는 커밋 이력을 남기고 특정 커밋까지 되돌린다.
- `{헤시값}` 바로 전(이전)까지 되돌린다.

```bash
git reset --hard {해시값}

git push -f origin {브랜치}
```
<br>

### 참고
---
[Git 롤백 실습](https://unity3dstudy.com/2020/05/08/Git-Reset-Revert/)