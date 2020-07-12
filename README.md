# Sass Git Vue的知识点补充
q
### 基于vue-cli v4.4.6的自建框架（商城实战）
##### webpack 配置 
##### package.json 配置及优化

### git 回退分支版本 （本地库（工作区） -- 暂存区 -- 分支仓库）
  git reset --hard HARD^ 回退到上个版本
  git reset --hard HARD^^ 回退到上上个版本
  git reset --hard HARD~2 同上
  git reflog 查看每一次命令

  git commit只提交经过add的修改内容，本地库（工作区） -add- 暂存区 -commit- 分支仓库

  git reset回退分支和暂存区   git checkout -- <file> 回退工作区