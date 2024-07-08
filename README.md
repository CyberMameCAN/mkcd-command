# mkcd-command

mkdirとcdを同時に実行するシェルスクリプトです。Bashで動作確認しています。

## mkcd.sh

  #!/bin/sh  
  mkdir $1 && cd $_

## 設定

### mkcd.chを適当な場所へコピー

  (例)~/bin/mkcd.sh

### 実行権限を付加

  $ chmod u+x ~/bin/mkcd.sh

### .bashrc に alias を定義

  alias mkcd='source ~/bin/mkcd.sh'

### 設定を反映

  $ source ~/.bashrc
  
## 使い方

  $ mkcd [Folder name]

## 参照

- [mkdirとcdを同時に実行したい時](https://blog.tstylestudio.com/2013/06/26/mkdir%e3%81%a8cd%e3%82%92%e5%90%8c%e6%99%82%e3%81%ab%e5%ae%9f%e8%a1%8c%e3%81%97%e3%81%9f%e3%81%84%e6%99%82/)
