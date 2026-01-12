# Nezha 数据备份

## 最新备份信息
- **文件名**: `data-2026-01-13-04-37-09.zip`
- **备份时间**: 2026-01-13 04:37:10
- **文件大小**: 12.0K

## 恢复说明
设置环境变量后容器会自动恢复最新备份。

## 手动触发备份
将此文件内容修改为 `backup` 即可触发手动备份。

## 环境变量
- `GITHUB_REPO_OWNER`: GitHub 用户名
- `GITHUB_REPO_NAME`: GitHub 仓库名称
- `GITHUB_TOKEN`: GitHub Token
- `GITHUB_BRANCH`: GitHub 备份分支
- `ZIP_PASSWORD`: 备份密码
