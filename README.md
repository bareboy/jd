# jd
青龙面板  青龙v2.8.0 最新文件

=> 互助功能可以直接将自己生成的互助码写入task_before.sh文件
=> 互助功能可实现方法很多，其中一种就是把互助码文件内容拷贝到task_before.sh中，最下面添加部分代码，具体参考附件
   还有就是你可以在环境变量管理或者config.sh或者task_before.sh任意文件中export脚本需要的环境变量
=> 可以自己添加附件的 code.sh 的定时任务，新建 task code.sh 即可，然后修改 task_before.sh 中的内容，code.sh 中的 name_js 如果不一样，自行修改作者前缀
=> 请更新最新的 code.sh 和 task_before.sh，点击查看最新 code.sh, task_before.sh，更新完请手动执行一次 task code.sh 的任务，防止日志结束标记影响互助
=> 如助力有问题，请使用最新文件，code.sh看你存放的目录，如果是/ql/scripts，可使用task code.sh，如果是/ql/config，可使用task /ql/config/code.sh
