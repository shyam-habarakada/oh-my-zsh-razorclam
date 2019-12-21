# oh-my-zsh-razorclam
A minimal theme optimized for remote development

## Shorter git branch names

If your git branch names take the forms of `personal/yournamehere/...` or `feature/...`, this theme will truncate the branch names like `P|...` and `F|...` respectively, saving you space from an otherwise lengthy and redundent text taking up your prompt.

## Custom hostnames when connected to a SSH host

Many oh-my-zsh themes don't give you an offerdance to easily tell when you are on your local terminal vs a remote development machine that you connect to regularly (and have the same .dotfiles installed). This theme will use your `${HOST}` value or a custom `${HOST_PREFIX}` you can define as a prefix for your prompt when connected via SSH.

## Usage

Copy the theme file into your `${ZSH_CUSTOM/themes}` folder and set your theme to `razorclam`.

To use a custom `HOST_PREFIX` for SSH, set that value in your environment _before_ you initialize oh-my-zsh.

## And

Enjoy!
