# seckill
接触并学习高并发。后台框架采用SSM，前台框架采用bootstrap，数据库采用mysql，项目管理工具maven，接口设计采用restful风格

并发优化点：
  1.前端控制：避免重复按钮点击请求
  2.动静态数据分离：CDN缓存，后端缓存（redis）
  3.事务竞争优化：减少事务锁时间（存储过程）
