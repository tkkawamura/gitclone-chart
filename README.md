# gitclone-chart
ローカルにgithubのファイル/フォルダをダウンロードする手順

### 手順1 ダウンロードしたいrepositoryページを開く

![image](https://user-images.githubusercontent.com/77152807/108450352-689b1c00-72a8-11eb-9ffb-0b341366b3cb.png)

### 手順2 右上にある"Code"ボタンをクリックし、展開された中のHTTPS URLをコピーする

![image](https://user-images.githubusercontent.com/77152807/108450807-1eff0100-72a9-11eb-9682-377546db38eb.png)

### 手順3 ダウンロードしたいwindowsやlinuxでダウンロードする
ダウンロードしたいwindows(CMD)やlinuxで、  
ダウンロード先のディレクトリに移動し、  
"git clone <https url>"コマンドでダウンロードする。  
  ※初回gitアクセス時は、githubのユーザー名、パスワード入力が必要

 下記実行例
```
C:\20210219_gitclone手順作成>git clone https://github.com/tkkawamura/vdbench.git
Cloning into 'vdbench'...
Username for 'https://github.com': tkkawamura
Password for 'https://tkkawamura@github.com':
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (20/20), done.
remote: Total 22 (delta 4), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (22/22), 10.52 KiB | 897.00 KiB/s, done.
Resolving deltas: 100% (4/4), done.
```
