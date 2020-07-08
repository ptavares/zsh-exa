# zsh-exa

zsh plugin for installing and loading [exa](https://github.com/ogham/exa.git)

## Table of content

- [zsh-exa](#zsh-exa)
  - [Usage](#usage)
  - [Updating exa](#updating-exa)
  - [License](#license)

## Usage

Once the plugin installed, `exa` will be available

- Using [Antigen](https://github.com/zsh-users/antigen)

Bundle `zsh-exa` in your `.zshrc`

```shell
antigen bundle ptavares/zsh-exa
```

- Using [zplug](https://github.com/b4b4r07/zplug)

Load `zsh-exa` as a plugin in your `.zshrc`

```shell
zplug "ptavares/zsh-exa"
```

- Using [zgen](https://github.com/tarjoilija/zgen)

Include the load command in your `.zshrc`

```shell
zget load ptavares/zsh-exa
```

- As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin

Clone `zsh-exa` into your custom plugins repo and load as a plugin in your `.zshrc`

```shell
git clone https://github.com/ptavares/zsh-exa.git ~/.oh-my-zsh/custom/plugins/zsh-exa
```

```shell
plugins+=(zsh-exa)
```

Keep in mind that plugins need to be added before `oh-my-zsh.sh` is sourced.

- Manually

Clone this repository somewhere (`~/.zsh-exa` for example) and source it in your `.zshrc`

```shell
git clone https://github.com/ptavares/zsh-exa ~/.zsh-exa
```

```shell
source ~/.zsh-exa/zsh-exa.plugin.zsh
```

## Updating exa

The plugin comes with a zsh function to update [exa](https://github.com/ahmetb/exa.git) manually

```shell
# From zsh shell
update_zsh_exa
```

## License

[MIT](LICENCE)
