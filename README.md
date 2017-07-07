# Adam Stacoviak's ~/.dotfiles

## Install

You should install these `.dotfiles` after you've setup [adamstac/laptop](https://github.com/adamstac/laptop).

---

Clone to your laptop.

    hub clone adamstac/.dotfiles

Install the dotfiles.

    env RCRC=$HOME/.dotfiles/rcrc rcup

After the initial installation, you can run `rcup` without the one-time variable `RCRC` being set (`rcup` will symlink the repo's `rcrc` to `~/.rcrc` for future runs of `rcup`).

For more information see [thoughtbot/rcm](https://github.com/thoughtbot/rcm) or [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles).