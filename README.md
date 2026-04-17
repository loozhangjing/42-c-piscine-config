## Setup
1. install neovim (if not already installed)
2. in your shell, run `curl https://raw.githubusercontent.com/42paris/42header/refs/heads/master/plugin/stdheader.vim > ~/.config/nvim/plugin/stdheader.vim` (copies the 42 header .vim plugin file to your local nvim config folder)
3. open `~/.config/nvim/plugin/stdheader.vim` (the newly created file) and replace `$USER` with `$_42USER` and `$MAIL` with `$_42MAIL`*
4. add the lines in the `.bashrc` file in this repository to your `.zshrc` file

*I renamed the variables to avoid conflicts with the `$USER` environment variable on my local machine (neovim doesn't work when my `$USER` variable is not the same as my actual Ubuntu username)
