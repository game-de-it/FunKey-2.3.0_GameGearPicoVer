# FunkeyOS 2.3.0 Game Gear picodrive バージョン  

## 特徴
---  
これは[picodrive-funkey](https://github.com/DrUm78/picodrive-funkey)を利用して新たなエミュレータとして「Game Gear pico」を作成し、既存のGame Gear(mednafen)と共存させたFunkeyOSのイメージファイルです。
また、[システムステータス表示にてバッテリー残量を表示する機能](https://github.com/game-de-it/RGnano/blob/main/battery.md)と[ゲーム中のスナップショットがゲームのサムネイルになる機能](https://github.com/game-de-it/RGnano/blob/main/snapshot.md)を搭載しています。  
- **__注意__**  
  - GMenu2xでのみGame gear picoは動作します(RETROFEでの動作は調査中です)  
  - このアップデートイメージファイルはFunkeyOSにのみ適用できます  
(AnbernicOSにこのファイルを置いてもアップデートは動作しません)  
  - ROMファイル、サムネイル画像、セーブデータはそのまま保持されます
  - このアップデートイメージを適用した上で公式のアップデートイメージを適用した場合、本機能は全て削除されてしまいます

## 手順  
---
###  ●OSイメージを使ってアップデートする場合
1. リリースページ下部にある **「FunKey-rootfs-2.3.0_GameGearPicoVer.fwu」** ファイルをダウンロードします  
2. PCとRG nanoをUSBケーブルで接続し、本体側面にある電源ボタンを1回押して 「MOUNT USB」 を選択して実行します  
  <img src="https://github.com/game-de-it/RGnano/blob/main/asset/IMG_2218.jpeg" width="800">  

3. RG nanoのルートフォルダに「FunKey-rootfs-2.3.0_GameGearPicoVer.fwu」ファイルをコピーします  
 <img src="https://github.com/game-de-it/RGnano/blob/main/asset/sc8.png" width="800">  

4. RG nanoで 「EJECT USB」　を実行してPCから切断すると、自動的にOSアップデートが実行されます  
(SDカードの速度にもよりますが大体3分以内には作業が終了します)  
  <img src="https://github.com/game-de-it/RGnano/blob/main/asset/IMG_2219.jpeg" width="800">  
  <img src="https://github.com/game-de-it/RGnano/blob/main/asset/IMG_2271.jpg" width="800">  

5. 「Game Gear pico」 が追加されていることを確認できたら作業は終了です 
    <img src="https://github.com/game-de-it/RGnano/blob/main/asset/IMG_2269.jpg" width="800">  
  
以上  

---
###  ●OSイメージを使ってアップデートする場合  
1. このページ下部にある **「FunKey-sdcard-2.3.0_GameGearPicoVer.img」** ファイルをダウンロードします  
2. balenaEtcherなどのお好きなイメージ書き込みツールを使って、SDカードにOSイメージを書き込んでください  
  

以上
