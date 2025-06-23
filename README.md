# git_test

修改内容：
1.程序运行定时设计
2.argparse库指定测试环境参数设计（数据库环境，Kafka环境）

程序运行方式：
# 使用测试环境
python main.py --env test
# 使用验收环境
python main.py --env staging
# 使用生产环境（默认）
python main.py --env prod
