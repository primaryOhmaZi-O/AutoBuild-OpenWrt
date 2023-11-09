# AutoBuild-OpenWrt
[我的README](/README.md)  |  [原作者的README](/README.en.md)

1.大麦DW22D刷机 > hiwifi_hc5761
- 点击仓库顶部的[github/workflows]文件夹，你可以看到几个工作流文件，每个文件针对一个特定的架构(设备)，我这里选择 Build_OP_hiwifi_hc5761.yml。
- 点击菜单上的“Action”，点击左侧要运行的工作流，然后转到右侧的“Run workflo”按钮，点击下拉菜单，点击绿色按钮“Run workflow（运行工作流）”。
- 构建自动开始。可以在Actions页面上查看进度。
- 当构建完成后，在Actions页面workflow run列表中点击已完成的工作流，在详情页中下载编译生成的Artifacts文件。
- 默认Web管理IP: 192.168.5.1，用户名root，无登录密码
