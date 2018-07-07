# 默认配置(非常重要)
## 配置路径
    正确->File -> Other Settings -> Default Settings
    错误->Preferences
## 说明
    只有在这里配置了才会是所有的Project都生效,不然新开的Project还要重新配置一遍
    
    
# 性能配置
## 编译堆内存
### 配置路径
    Preferences -> Build, Execution, Deployment -> Compile
### 配置内容
    Build process heap size (Mbytes): 1500
## idea启动JVM参数
### 配置路径
    Help -> Edit Custom VM Options...
### 配置内容:
    -Xms1g
    -Xmx4g
    -XX:ReservedCodeCacheSize=1g
#插件配置
## checkstyle
### 配置路径
    Other Settings | Checkstyle
### 配置内容
    导入 idea-checkstyle.xml
    如果有supperssions的过滤,修改idea-checkstyle.xml
## Eclipse Code Formatter
### 配置路径
     Other Settings | Code Formatter
### 配置内容
    选 "Use the Eclipse code formatter"
    导入idea-formatter-1.4.xml
    
# 其他
## 自动生成
### 配置路径
    Editor -> File and Code Templates -> Includes -> File Header
### 配置内容
    /**
     * @author name 
     * Created on ${YEAR}-${MONTH}-${DAY}
     */
## properties配置
### 配置路径
    Preferences -> Editor -> File encodings
### 配置内容
    勾选 transparent native-to-ascii conversion
## Inspection 配置
### 配置路径
    Editor -> Inspections -> Imports
### 配置内容
    导入配置文件idea_inspection.xml
## ImportOrder
### 配置路径
    Preferences -> Editor -> Code Style -> Java -> Imports
### 配置内容
    导入配置文件idea_import_order.xml


    
    

 