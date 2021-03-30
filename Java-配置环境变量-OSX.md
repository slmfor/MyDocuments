# OSX管理JDK
现存Java版本为Java 10，spring initializr提供的JDK版本为16、11、8，由是产生整理JDK的想法。

查看当前存在的各版本JVM  
`/usr/libexec/java_home -V`

删除多余的JDK
```
ls /Library/Java/JavaVirtualMachines/
sudo rm -rf /Library/Java/JavaVirtualMachines/jdk-9.0.1.jdk
```  

常规的配置环境变量
```

```

