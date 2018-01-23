# Adam Stacoviak's ~/.dotfiles

## Installation

He future Adam -- yea you know you forget a ton of stuff and the next time you read this you'll likely hoping that past you told you how to solve your problems.

Well, you should install these `.dotfiles` after you've setup [adamstac/laptop](https://github.com/adamstac/laptop). So do that and come back when you're done.

...

...

...

Done? OK.

Clone this project to your laptop into your root directory.

    git clone git@github.com:adamstac/.dotfiles.git

Now, to refresh your memory -- because you installed [rcm](https://github.com/thoughtbot/rcm) from thoughtbot (via Homebrew) you're able to easily manage the installation of your dotfiles.

But, when you install them for the first time you need to set your `env` variable when you run `rcup`, like so:

    env RCRC=$HOME/.dotfiles/rcrc rcup

After this initial installation, you can simply `cd` to `~/.dotfiles` and run `rcup` any time you want to install any changes.

---

For more information see [thoughtbot/rcm](https://github.com/thoughtbot/rcm) or [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles).