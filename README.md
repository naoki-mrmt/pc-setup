# Add homebrew

1. brewをインストールする
  ```shell
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
2. pathの追加
  ```shell
  (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/foxhound/.zprofile
  eval "$(/opt/homebrew/bin/brew shellenv)"
  ```
3. .Brewfileをダウンロード
4. ツールをインストールする
  ```shell
  brew bundle --global
  ```



