# How to use

## homesick のインストール

```bash
sudo gem install homesick
```

## homesick で dotfiles を配置する

clone し, シンボリックリンクを貼る.

```bash
homesick clone ${ユーザー名}/dotfiles
homesick symlink dotfiles
```

## dotfiles が更新されたら

pull してもう一回 symlink を貼ればよい.

```bash
homesick pull dotfiles
homesick symlink dotfiles
```

## References

- [GitHub - homesick を使って dotfiles を管理する！ - Qiita](http://qiita.com/s_tomoyuki/items/650ff995e6906bdecc17)
- [GitHub と homesick を使って複数 Mac 間で dotfiles を同期する ｜ Developers.IO](http://dev.classmethod.jp/etc/github-homesick-dotfiles/)
- [technicalpickles/homesick](https://github.com/technicalpickles/homesick)