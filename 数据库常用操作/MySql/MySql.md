# 一、删除表中数据(有自增id字段)
1. DELETE FROM 表名 WHERE 条件;
ALTER TABLE `库名`.`表名` AUTO_INCREMENT = 重置的id值;  //重置自增id字段
2. TRUNCATE TABLE `库名`.`表名`;    //表中的所有数据会被删除，而且如果是自增字段，其计数也会被重置为初始值