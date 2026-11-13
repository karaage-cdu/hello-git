# hello-git

我的第一个 GitHub 仓库，用来练 Git 工作流。

## 环境

- Windows 11 + Git 2.56.1（`D:\Git`）
- SSH 认证：`~/.ssh/id_ed25519`
- 默认分支：`main`

## 常用命令

```bash
git status                 # 看当前状态
git add .                  # 暂存全部改动
git commit -m "说明"        # 提交
git push                   # 推到 GitHub
git log --oneline --graph  # 看提交历史
```

## 第一个 C 程序

```c
#include <stdio.h>

int main(void) {
    printf("Hello, Git!\n");
    return 0;
}
```
