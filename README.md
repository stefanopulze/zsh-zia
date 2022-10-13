# ZSH is awesome

Plugin for zsh that add a shortcut for most developer commands for 
`docker`, `kubectl`, `terraform`

## Installation
### Oh My Zsh
1. Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)
    ```bash
    git clone https://github.com/stefanopulze/zsh-zia ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-zia
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):
    ```
    plugins=( 
        # other plugins...
        zsh-zia
    )
    ```

3. Start a new terminal session.