---
layout: post
title: Git 사용법
excerpt: Git 제대로 알고 사용하자!
date: 2021-03-13
updatedDate: 2021-03-13 
tags:
  - post
  - programming
  - productivity
---

## Git 로컬 리포에 리모트 추가하기

```shell
git remote add origin <github_url>

```

## Branch

- Branch 리스트 출력하기

```shell
git branch // local branch 
git branch -a // 모든 branch
git branch -r // remote branch
git show-branch // 현재 branch
```

- Branch 이름 변경

```shell
git branch -m <new_name>
```