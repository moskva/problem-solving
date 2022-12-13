# What

通过 Github Desktop 上传的时候显示如下错误信息

<img src="github err.png" />

# How-to

1. 将相关目录从 iCloud 云盘中移至本机其他目录，防止 iCloud 云盘自动优化本地空间导致问题。参考：[git - How do I reconcile: "warning: ignoring ref with broken name refs/remotes/origin/HEAD 2"? - Stack Overflow](https://stackoverflow.com/questions/74072548/how-do-i-reconcile-warning-ignoring-ref-with-broken-name-refs-remotes-origin)

2. 进入 `.git/refs/remotes/origin `目录，删除 `HEAD 2`，问题解决。参考：[BitBucket Git Error: did not send all necessary objects - Stack Overflow](https://stackoverflow.com/questions/8788975/bitbucket-git-error-did-not-send-all-necessary-objects)

