---
layout:     post
title:      Hive：Hive SQL 常用优化方法
subtitle:   
date:       2022-01-26
author:     dex0423
header-img: img/post-bg-os-metro.jpg
catalog: true
tags:
    - Hive
---


# 1. 影响 Hive 效率的因素

#### 1.1. 数据倾斜

#### 1.2. 数据冗余

#### 1.3. JOB / IO 过多

#### 1.4. MapReduce 分配不合理


# 2. 优化思路

#### 2.1. 对 Hive SQL 语句的优化


#### 2.2. Hive 配置项优化


#### 2.3. MapReduce 配置优化


# 3. 优化方法

#### 3.1. 列裁剪 & 分区裁剪

- 列裁剪，就是在查询时只读取需要的列；
- 分区裁剪，就是只读取需要的分区。
>全列扫描和全表扫描，他们的效率都很低。





  ![]({{site.baseurl}}/img-post/es-5.png)

- 这表示安装成、服务已被启动；

