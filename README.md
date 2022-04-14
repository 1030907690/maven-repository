# maven-repository
maven-repository

# 使用
## 先在`pom.xml`增加仓库配置
```

    <repositories>
        <repository>
            <id>maven-repository-main</id>
            <url>https://raw.github.com/1030907690/maven-repository/main/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>

    </repositories>

```

## 引入依赖例子
```
   <dependencies>
      <dependency>
            <groupId>com.springboot.sample</groupId>
            <artifactId>conditional-validate-starter</artifactId>
            <version>0.0.1-SNAPSHOT</version>
      </dependency>
  </dependencies>
```
