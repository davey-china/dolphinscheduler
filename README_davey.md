整个海豚调度器的启动步骤：
1. 启动zk：执行文件： D:\zookeeper\apache-zookeeper-3.8.5-bin\start.bat；
1. 启动对象存储： D:\minio\start.bat；
1. 需要注意WSL中的元数据库mysql是否运行，如果没有运行，需要启动，参考启动备注：/service/mysql/start_note.text;
1. 启动海豚的 MasterServer 、 WorkerServer 、 ApiApplicationServer 三个服务；
1. 进入海豚项目根目录下面的 dolphinscheduler-ui 模块，执行 `pnpm run dev` 启动ui界面；
1. 登录海豚的界面就行了
海豚的账号密码：
admin/dw1234  
davey/dw1234
