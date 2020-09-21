### 美化 PowerShell

#### 安装 posh-git，oh-my-posh

``` powershell
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

#### 配置PowerShell 启动读取的配置文件(notepad $PROFILE 打开)

``` powershell
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Robbyrussell
```

> 如果无法导入，可以使用`get-executionpolicy`查看执行策略，再使用`set-executionpolicy remotesigned` 命令解除限制

