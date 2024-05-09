# このページについて
これは，橋本研究室@東京理科大学のGithub Organization(β版)です．研究で使っているコードの管理や，メンバーとのディスカッションに利用してください．


# CheatSheet

## Local PC Setup
最初だけでいいので，必ずやる．
```Bash
cd ~/<workspace>
git init
git remote add origin <Repository URL>
```

## Github Setup
・Repository 作成 __(必ずPrivateで！！)__

## pushまでのながれ

```Bash
cd ~/<workspace>
git add <file name>
git commit -m "<commit message>"
git push origin main
```
github側に反映されているか確認

## その他
・.gitignore を書いて，画像などの大きなファイルをあげないようにする  
記述方法→https://qiita.com/inabe49/items/16ee3d9d1ce68daa9fff  
・ほかのPC環境で開発することがある人は，まずpullしてから始める



