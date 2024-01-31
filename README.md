# account_book

### Gitflow 적용하기
```
PS C:\Users\qaz77\Documents\GitHub\account_book> git clone --recursive git://github.com/nvie/gitflow.git
Cloning into 'gitflow'...
fatal: unable to connect to github.com:
github.com[0: 20.200.245.247]: errno=Unknown error

PS C:\Users\qaz77\Documents\GitHub\account_book> git config --global url.https://github.com/.insteadOf git://github.com/
```

에러 발생시 위 방법으로 포트를 열어주어야 클론이 정상적으로 작동한다. 
