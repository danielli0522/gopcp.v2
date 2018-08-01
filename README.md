
#### 目标

- 熟悉go语言语法
    - defer函数
    - 指针
    - 特殊语法
        - if 语句：不用括号;一个if可以有两个语句
    - interface的使用
    - 如何进行继承功能
   

- 掌握开发一个后台程序需要的相关go技术
    - 并发编程
    - 协程概念
    - 包结构
    - 单元测试编写
    - 爬虫程序的基本架构
    - 日志系统

- 三大语言之对比
    - C/C++
    - Java
    - Go

- 该代码业务
    - 基本架构
        - 调度器
        - 下载器
        > 在main函数中启动后，使用go协程进行数据处理

        - 分析器
        > 在main函数中启动后，使用go协程进行数据处理

        - 条目处理器
        > 在main函数中启动后，使用go协程进行数据处理
        
- go语言如何调用C语言
    - 环境准备
        - windows 需要按照gcc命令，如C:\mingw64\bin
    - 编写C代码
        - 参考grammear的go2c目录
     
    - 编写go语言代码
        - 参考grammear的go2c目录,一定需要类似语句（import “C”必须紧跟注释）
        ```
            // #cgo LDFLAGS: -L .
            // #include "util.h"
            import "C"
        ```
    - 编写main.go，运行指令
            
