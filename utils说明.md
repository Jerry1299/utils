每个工具类的作用：

- BeanHelper：实现Bean属性的拷贝，把一个Bean的属性拷贝到另一个Bean，前提是其属性名一致或部分一致
- CookieUtils：实现cookie的读和写
- IdWorker：生成Id
- JsonUtils：实现实体类与Json的转换
- RegexUtils：常用正则校验
- RegexPattern：常用正则的字符串

要引的依赖:
    <dependencies>
        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-beans</artifactId>
            <scope>compile</scope>
        </dependency>
        <dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>javax.servlet-api</artifactId>
            <version>3.1.0</version>
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-logging</artifactId>
        </dependency>
        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-databind</artifactId>
            <version>2.9.8</version>
            <scope>compile</scope>
        </dependency>
    </dependencies>



