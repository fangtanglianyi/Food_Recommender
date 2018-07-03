#基于 Spark Streaming + ALS 的餐饮推荐系统

## 概述
  
基于大数据的餐饮推荐系统，整体采用Lambda架构，读取餐饮评分数据并

通过Spark的MLlib中的ALS建立推荐模型之后进行推荐。这里是推荐引擎

的代码，分为离线推荐和实时推荐。