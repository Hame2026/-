OverTheWire Bandit 闯关记录

Level 0
- 任务：找到 readme 文件并读取。
- 使用命令：`ls` (查看目录)、`cat readme` (读取文件内容)。
- 踩坑记录：一开始把 ls 敲成了 is，报错 command not found；输入密码时屏幕不显示，不能按退格键。
- 获取的密码：6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

Level 1
- 任务：读取名为 `-` 的文件。
- 使用命令：`cat ./-`
- 踩坑记录：直接 cat - 会导致终端卡住，因为 - 代表标准输入。需要用 ./ 指定当前路径。
- 获取的密码：PK8fYLZg2hnHSz83plBL1iEPKdD3QToB
