一、文件包结构
    +/charting_library                包含所有的库文件
        + /static                     存储图表库内部内容，不做其他用途
        - charting_library.min.js     Charting Library窗口部件接口。不建议修改该文件
        - charting_library.min.d.ts   窗口小部件界面的TypeScript定义
        - datafeed-api.d.ts           数据接口的TypeScript定义
    + /datafeeds                      
        + /udf                        包含与UDF兼容的datafeed包装器（实现JS API以连接到Charting Library和UDF以连接到datafeed）
    - index.html                      使用的小示例
    - mobile_black.html               自定义实例
    - mobile_white.html               自定义实例
    - test.html                       图表库自定义功能的示例



