## 如何使用jedis-spring-boot-starter

* 引入依赖
```
<dependency>
    <groupId>ink.akira</groupId>
    <artifactId>jedis-spring-boot-starter</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

* 增加配置
```
jedis.host=localhost
jedis.port=6379
jedis.db=1
```

* 在Spring中使用
```java
@Autowired
private JedisDAO jedisDAO;
```