# mvn-repo

# 在pom.xml中添加
  	<repositories>
	    <repository>
	        <id>mvn-repo</id>
	        <!-- https://raw.github.com/用户名/仓库名/分支名 -->
	        <url>https://raw.github.com/zhanghaif/mvn-repo/master</url>
	        <snapshots>
	            <enabled>true</enabled>
	            <updatePolicy>always</updatePolicy>
	        </snapshots>
	    </repository>
	</repositories>
  
# 如何引用
      	<dependency>
	        <groupId>com.github.haifeng</groupId>
	        <artifactId>serve-core-common-response</artifactId>
		<version>1.0</version>
	</dependency>
