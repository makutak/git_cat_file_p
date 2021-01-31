# git_cat_file_p

https://engineering.mercari.com/blog/entry/2015-09-14-175300/ これと同じことをRustでやってみただけ。

# 使い方
```sh
$ cargo run .git/objects/3b/18e512dba79e4c8300dd08aeb37f8e728b8dad 
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/git_cat_file_p .git/objects/3b/18e512dba79e4c8300dd08aeb37f8e728b8dad`
hello world

$ cargo run .git/objects/a4/940ec3db4cd24542203a9447c4259c96294c09 | nkf -w
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/git_cat_file_p .git/objects/a4/940ec3db4cd24542203a9447c4259c96294c09`
坊っちゃん
夏目漱石

-------------------------------------------------------
【テキスト中に現れる記号について】
~~~~~
省略
~~~~~
```
