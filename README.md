---
title: 어바웃파이썬
tags: ["aboutpython", "psygrammar", "psychopy", "github"]
notebook: 3_pending_from_me
---

## NextStep

  * [x] **오늘 발표한 내용을 요약하여 깃허브로 스터디 멤버들에게 공유하여 본다.**
  * [x] **무성님한테 담주 20170909에 for문과 함수와 클래스를 이어서 진행할지 물어본다.**
  * [ ] It will be helpful to practice for loop for my future. #backlog
  * [ ] It will be helpfull to practice file management methods #backlog
  * [x] opening and seeing each jupyter notebook takes huge effort and take time, so I think it's more efficient to upload jupyter notebook on github.
    * [x] [you should know how to upload folders or files to remote repository.](https://help.github.com/articles/adding-a-file-to-a-repository-using-the-command-line/)(If you don't know how to upload files with command line, then do it on github console until you know command line.) 
    * [x] [you should know how to upload files to a remote repository you want to upload.](https://www.evernote.com/Home.action?login=true&prompt=none&authuser=1#n=c1bcab42-6c06-4d2e-aa13-a7034ba8d1a6&ses=4&sh=2&sds=5&)
    * [x] I've completed this activity. check `- how to upload files in local dir to remote repository` at the bottom of this document. 

## 2017-09-04

- [점프투파이썬 초기버전](https://wikidocs.net/90) : 재귀호출, lambda, map, filer, reduce에 대한 개념이 친절하게 설명되어있다.
  
## 2017-09-02

### Summary

- while & if 문을 발표함.
- 주피터 노트북의 개념과 cheet sheet를 학습함.


### Action Items

- [if 문을 학습하였다.](https://wikidocs.net/20)
- [while 문을 학습하였다](https://wikidocs.net/21)
- [오늘 학습한 예제](https://github.com/sungyongkim/psygrammar_aboutpython_basic/blob/master/aboutpython_basic_jumptopython_20170902.ipynb)
- [김성근님이 주피터노트북의 개념과 cheet sheet를 발표해주심.](https://github.com/sungyongkim/psygrammar_aboutpython_basic/blob/master/JupyterNotebook.ipynb)

### Lesson Learned

* **Good**
 * 시간에 쫓기며 2시간 안에 끝내려 하기 보다는, 개념을 확실하게 학습하고 공유하자는 생각으로 거의 line by line으로 발표하여 스터디 멤버들로부터 긍정적 반응을 받음.
 * 타스크립트를 호출해서 함수로 사용해서 좋았음.

* **Bad**
 * 발표할 내용을 따로 준비안하고, 진행하다 보니, 선택과 집중하여 발표하는 것이 다소 힘들었다.
  * 사전에 발표할 내용만 추려서 진행하면 선택과 집중의 효율이 좀 더 좋아질 것 같다.

* **Other**
 * 데이터 사이언스 스쿨 교재가 개념설명 및 예제가 부족해보여서 점프투파이썬으로 스터디 진행.




## 2017-08-26

  * [I’ve learned ](https://github.com/sungyongkim/psygrammar_aboutpython_basic/blob/master/about_python_basic.ipynb)[for loop](https://github.com/sungyongkim/psygrammar_aboutpython_basic/blob/master/about_python_basic.ipynb)
  * [I’ve learned file management](https://github.com/sungyongkim/psygrammar_aboutpython_psychopy/blob/master/aboutpython_psychopy/aboutpython_psychopy/setup.ipynb)

## 2017-08-13


### aboutpython_basic

- [데이터사이언스 스쿨](https://datascienceschool.net/view-notebook/661128713b654edc928ecb455a826b1d/)

### psychopy

#### KeyActivity

  * ~~Xcode를 설치하자. 참조자료:<https://mikebeach.org/2012/09/29/how-to-install-wget-in-mac-os-x/>
  * about python_psychopy에서 ‘hello world’를 성공시키자. 
  * 03_Creating_and_presenting_stimuli에서 무성님이 만들어준 코드를 하나씩 실행하고, 유용한 것은 python library에 추가하자. 

#### KeyReference

  * [aboutpython_psychopy](http://localhost:8891/notebooks/psygrammar/aboutpython_psychopy-master/aboutpython_psychopy.ipynb)

### PythonDataScienceHandbook

#### KeyReference

  * [aboutpyothon_pdsh](http://localhost:8890/notebooks/psygrammar/aboutpython_pdsh/aboutpython_pdsh.ipynb)
  * [교재 : PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook)
  * how to upload files in local dir to remote repository
```python
Last login: Sun Aug 27 14:25:19 on console  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git init  
Initialized empty Git repository in /Users/pingonfefalas/Dropbox/python/psygrammar/aboutpython_python_basic/.git/  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ touch README.md  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git add README.md  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git commit -m "first commit"  
[master (root-commit) b0ea32e] first commit  
 1 file changed, 2 insertions(+)  
 create mode 100644 README.md  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git remote add origin https://github.com/sungyongkim/psygrammar_aboutpython_basic.git  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git push -u origin master  
Counting objects: 3, done.  
Delta compression using up to 4 threads.  
Compressing objects: 100% (2/2), done.  
Writing objects: 100% (3/3), 268 bytes | 0 bytes/s, done.  
Total 3 (delta 0), reused 0 (delta 0)  
To https://github.com/sungyongkim/psygrammar_aboutpython_basic.git  
 * [new branch]      master -> master  
Branch master set up to track remote branch master from origin.  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git status  
On branch master  
Your branch is up-to-date with 'origin/master'.  
Untracked files:  
  (use "git add file..." to include in what will be committed)  
  
    .DS_Store  
    .ipynb_checkpoints/  
    about_python_basic.ipynb  
    hello.ipynb  
    signal.txt  
  
nothing added to commit but untracked files present (use "git add" to track)  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ ls  
README.md           hello.ipynb  
about_python_basic.ipynb    signal.txt  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git add .  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git commit -m "Add existing file"  
[master 54e3e52] Add existing file  
 6 files changed, 1806 insertions(+)  
 create mode 100644 .DS_Store  
 create mode 100644 .ipynb_checkpoints/about_python_basic-checkpoint.ipynb  
 create mode 100644 .ipynb_checkpoints/hello-checkpoint.ipynb  
 create mode 100644 about_python_basic.ipynb  
 create mode 100644 hello.ipynb  
 create mode 100644 signal.txt  
  
#PINGONui-MacBook-Pro:aboutpython_python_basic pingonfefalas$ git push origin  
Counting objects: 8, done.  
Delta compression using up to 4 threads.  
Compressing objects: 100% (8/8), done.  
Writing objects: 100% (8/8), 4.56 KiB | 0 bytes/s, done.  
Total 8 (delta 1), reused 0 (delta 0)  
remote: Resolving deltas: 100% (1/1), done.  
To https://github.com/sungyongkim/psygrammar_aboutpython_basic.git  
   b0ea32e..54e3e52  master -> master  
```
