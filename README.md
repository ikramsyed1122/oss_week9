# oss2025_intro
## Task-1: Checkout your branch. 
Note that, there are 10 branches (5-6 students per branch).
The branch assignment is as follows:\
intro1 --> 강동혁, 강병규, 고홍규, 곽민준 ,구윤찬 
intro2 --> 김규민, 김근유, 김다니엘, 김성은, 김성훈
intro3 --> 김시현(22학번), 김시현(24학번), 김유호, 김윤재, 김은주
intro4 --> 김재영, 김준엽, 노하진, 박정원, 박주용, 박현민
intro5 --> 박현빈, 배지희, 서승덕, 서여진, 소재일, 송주한
intro6 --> 양진혁, 엄윤상, 우강식, 유승열, 유윤지, 유재동
intro7 -->  윤소영, 이동제, 이서현, 이석태, 이승희, 이의현
intro8 --> 이태준, 장성진, 장예령, 장인극, 장재훈
intro9--> 장주연, 장채원, 조예원, 조윤아
intro10--> 최규민, 현서우, 홍성호, 홍태민
(command: `$ git checkout intro<N>`)\

## Task-2: Open the intro.txt file, and write your name and department in it.
(format: 이름, 학과)\
Commit the changes.\
[Therefore, intro<N> branch is updated while origin/intro<N> is still in the previous commit]

## Task-3: Now push your branch to origin.\
command: `git push origin intro<N>`\
[With a successful push, We expect that origin/intro<N> would be updated.\
However, the push will be unsuccessful if your friend has pushed to the same branch first. If so, do the following]

## Task-3.1: Do the following only if the push was unsuccessful.
Fetch-Merge-Push\

Fetch the updated origin\
`git fetch origin`\

Merge the remote branch into your branch\
`git merge origin/intro<N>`\

Push again.
`git push origin intro<N>`\
