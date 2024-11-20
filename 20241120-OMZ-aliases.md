每次打开 Terminal 都会显示下面的错误信息，但 aliase 还可以使用。

`/Users/steven/.zshrc:108: permission denied: /Users/steven/.oh-my-zsh/custom/aliases.zsh`

今天在 `.zshrc` 中发现我原来是这么写的：
`~/.oh-my-zsh/custom/aliases.zsh`

改写后问题解决：
`source ~/.oh-my-zsh/custom/aliases.zsh`
