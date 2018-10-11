This is my first git.
--查看日志
git log  输出信息较多，包含版本号、注释、时间、提交人
git log --pretty=oneline 信息相对较短
git reflog用来记录你的每一次命令：（如果发生版本回退，git log 有些记录会看不到）
--版本回退
git reset --hard commitid 
git reset --hard HEAD~num num标识需要回退的前几个版本 ，例如上一个版本 num就为1