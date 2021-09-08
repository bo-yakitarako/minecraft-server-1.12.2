# みねくらの1.12.2のさーばーだよ
`mods`フォルダと`config`フォルダだけ追跡して、MODの変更に簡単に対応するよ

## やり方
- どこでもいいのでこのリポジトリを`clone`する
```
git clone https://github.com/bo-yakitarako/minecraft-server-1.12.2.git
```
- Minecraftの1.12.2をいったんプレイして、起動したら閉じる
  - 下記設定でプレイし、すぐ閉じる感じ

起動構成の設定|起動後(この画面になったら閉じる)
----|----
<img width="552" alt="first" src="https://user-images.githubusercontent.com/55777096/132514234-c9475b31-a651-4ae2-9dbd-030c5f7c9def.png">|<img width="852" alt="first_minecraft" src="https://user-images.githubusercontent.com/55777096/132514496-70ca1ad2-c2e5-43d9-a7ac-e779701ae346.png">

- <a href="https://maven.minecraftforge.net/net/minecraftforge/forge/1.12.2-14.23.5.2855/forge-1.12.2-14.23.5.2855-installer.jar" target="_blank" rel="noopener noreferrer">Forgeのインストーラー</a>をダウンロードする(クリックすればダウンロードされるよ)
- ダウンロードしたForgeのインストーラーを開いて、特になにも考えずにOKする

<img width="490" alt="forge_installer" src="https://user-images.githubusercontent.com/55777096/132515997-14868544-45cf-4cbc-9035-c47c07bf405e.png">

- Minecraftのランチャーを開いて、起動構成を以下のように設定してプレイする
  - バージョン: `release 1.12.2-Forge~`
  - ゲームディレクトリ: **このリポジトリをcloneしたフォルダ**(`minecraft-server-1.12.2`フォルダ)

起動構成の設定|起動後(modが認識されている)
----|----
<img width="513" alt="mod_setting" src="https://user-images.githubusercontent.com/55777096/132518105-88267bfd-3922-42c1-872b-682e395c906c.png">|<img width="963" alt="mod_minecraft" src="https://user-images.githubusercontent.com/55777096/132518129-d4668e08-f5e2-41f8-a650-2b0ca801bf31.png">

- あとはサーバー入って終わり！閉廷！

## MODやconfigを変えたら
**絶対pushしてくれよな！**

## MODやconfigが変わったら
このリポジトリのフォルダ開いて`git pull`すればすぐ適用できるな！
