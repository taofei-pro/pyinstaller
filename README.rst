同步命令
git remote add upstream https://github.com/pyinstaller/pyinstaller.git
git fetch upstream --tags
git merge v6.14.1


打包命令

1. cd bootloader
2. python ./waf all


安装命令

pip install git+https://github.com/taofei-pro/pyinstaller@64-bit
