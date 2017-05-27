# UnitusFrontendHandsOn

## Homebrew,Node.jsのインストール

- (Mac)
 - http://mmorley.hatenablog.com/entry/2016/11/22/233034 
```Shell
$ /usr/bin/ruby -e /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install nodebrew
$ nodebrew setup
$ echo 'export PATH=$HOME/.nodebrew/current/bin:$PATH' >> ~/.bash_profile
$ source ~/.bash_profile

$ nodebrew install-binary stable
$ nodebrew use stable
$ node -v
// ここでversionが表示されればok
``` 

- Windows
  - http://qiita.com/taipon_rock/items/9001ae194571feb63a5e
