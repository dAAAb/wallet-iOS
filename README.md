# wallet
[![Build Status](https://travis-ci.org/blockchain-certificates/wallet-iOS.svg?branch=master)](https://travis-ci.org/blockchain-certificates/wallet-iOS)


Blockcerts mobile app for iOS to receive and share certificates that are verifiable via the blockchain.

# inatall

You need Git Submodule to recursively download/clone all external dependencies.

You may need to register computer's SSH Key to GitHub to use recursive clone:

```
git config --global user.name "yourname"
git config --global user.email "youremail" 
```

[Reference](https://www.jianshu.com/p/3b56f4e6ac77)

在github上添加ssh密鑰，這要添加的是「id_rsa.pub」裡面的公鑰。打開github在設置中添加密鑰。

[GitHub 設定頁](https://github.com/settings/keys)

然後就不會出現類似這樣的錯誤

git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

執行

```
$ git clone --recursive git@github.com:[Your GitHub Username]/[GitHub Project Name]
```

## Contact

Contact us at [the Blockcerts community forum](http://community.blockcerts.org/).

