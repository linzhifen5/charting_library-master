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


二、设置查询时间
    time_frames: [   // Y/M/D 年月日，W表示周
        { text: "2y", resolution: "6M", description: "2 Years" },  // 表示从现在到2年前的、k柱间隔是6个月
        { text: "1y", resolution: "1M", description: "1 Years" },  // 表示从现在到1年前的、k柱间隔是1个月
    ],



