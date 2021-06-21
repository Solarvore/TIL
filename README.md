# GIT BASIC

git의 기초를 배워요



## WARNIG

1. HOME 폴더(~)를 리포로 업그레이드 하지 않는다. 
2. 리포 안의 폴더에서 git init 하지 않는다. (리포의 하위 폴더에서 git init 하지 않는다.)

## 저장소 초기화 하기

```
$ git init
```

## 저장소를 일반 디렉토리로 되돌리기

``` 
$ rm -rf .git
```

## stage 에 올리기(staging)

``` 
$ git add <filename>
```



## 저장소 초기화 하기

```
$ git init
```

## 저장소를 일반 디렉토리로 되돌리기

```
$ rm -rf .git
```

## stage에 올리기(staging)

````
$ git add <file name>
````

## commit을 통해 스냅샷

```
$ git commit -m "MESSAGE"
```



## 현재 상태 확인하기

```
$ git status
```

- 빨간색으로 표시되는 파일은 commit에 포함되지 않음
- 초록색으로 표시되는 파일은 commit에 포함 됨
- 변경사항이 없는 파일은 표시되지 않음



## 커밋 로그 확인하기

```
$ git log
```

