ssm
===============
###### 程序定位
1. 熟悉使用idea开发工具
2. 在idea中使用maven创建ssm项目
3. 学习mybatis-generator-maven-plugin自动生成mybatis代码
4. 学习编写规范的README.md文件
5. 完成IDEA配合GitHub管理本地代码，实现更新本地代码到GitHub上
代码供个人学习使用  

###### 环境依赖
1. JDK 1.8
2. mysql 8.0.11
3. apache-maven-3.3.9
4. mybatis 3.4.6

###### TABLE
```sql
-- ----------------------------
-- Table structure for `user`
-- ----------------------------
DROP TABLE IF EXISTS `ssm_user`;
CREATE TABLE `ssm_user` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(255) DEFAULT NULL,
  `loginName` varchar(255) DEFAULT NULL,
  `passWord` varchar(255) DEFAULT NULL,
  `sex` varchar(255) DEFAULT NULL,
  `age` int(11) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

-- ----------------------------
-- Records of user
-- ----------------------------
INSERT INTO `ssm_user` VALUES ('1', '枫', 'admin', 'admin', '男', '21');

```
