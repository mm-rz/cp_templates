# cp_templates

ぼくが競プロで使ってるテンプレ集

[![Actions Status](https://github.com/Memories-of-Sun-and-Moon/cp_templates/workflows/verify/badge.svg)](https://github.com/Memories-of-Sun-and-Moon/cp_templates/actions)

[リンク](https://memories-of-sun-and-moon.github.io/cp_templates/)


Github Actions が落ちたときに 

>"fatal: could not read Password for 'https://***@github.com': No such device or address"
> "subprocess.CalledProcessError: Command '['git', 'push', 'https://***@github.com/Memories-of-Sun-and-Moon/cp_templates.git', 'HEAD']' returned non-zero exit status 128.

のようなエラーが見られたら、トークンの有効期限が切れている可能性があります。

# requre

## pip install

- ``online-judge-verify-helper``

# usage

1. require 欄の導入事項を導入する
2. ここの親ディレクトリに ``__template.cpp`` をコピーし実装する
3. 提出時には(wsl 上の ubuntu であれば) ``B (file)`` コマンドでコピーができる

