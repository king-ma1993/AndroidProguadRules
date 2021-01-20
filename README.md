# AndroidProguadRules
Android超级变态的混淆词典

常规abcd等混淆方式对逆向的干扰程序并不是很大，所以需要一个变态的字典,使用方法如下：

**根据自己需要在proguard-rules.pro文件中进行配置**

```
-obfuscationdictionary bt-proguard.txt
-classobfuscationdictionary bt-proguard.txt
-packageobfuscationdictionary bt-proguard.txt
```

