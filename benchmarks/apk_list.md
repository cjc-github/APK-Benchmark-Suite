# apk列表

apk 列表如下：


| 序号 | 名称                            | 来源                                                         | 添加理由                       | 主要的so文件 | 
| ---- | ------------------------------- | ------------------------------------------------------------ | ------------------------------ | ------------------------------ |
| 1    | com.machiav3lli.fdroid_1107.apk | https://f-droid.org/zh_Hans/packages/com.machiav3lli.fdroid/ <br/> 版本1.1.2 （1107） | 导出符号JNI_OnLoad存在后缀符号 | libandroidx.graphics.path.so文件 |
| 2    | com.looker.droidify_660.apk   |  https://f-droid.org/zh_Hans/packages/com.looker.droidify/ <br/> 版本0.6.6（660）  |             静态导出符号在Smali中没有找到    | libdatastore_shared_counter.so文件 |
| 3    |                                 |                                                              |                                |  |
| 4    |                                 |                                                              |                                |  |
| 5    |                                 |                                                              |                                |  |
| 6    |                                 |                                                              |                                |  |
| 7    |                                 |                                                              |                                |  |
| 8    |                                 |                                                              |                                |  |
| 9    |                                 |                                                              |                                |  |
| 10    |                                 |                                                              |                                |  |
| 11   |                                 |                                                              |                                |  |
| 12    |                                 |                                                              |                                |  |
| 13    |                                 |                                                              |                                |  |
| 14    |                                 |                                                              |                                |  |
| 15    |                                 |                                                              |                                |  |
| 16    |                                 |                                                              |                                |  |
| 17    |                                 |                                                              |                                |  |
| 18    |                                 |                                                              |                                |  |
| 19    |                                 |                                                              |                                |  |
| 20    |                                 |                                                              |                                |  |
| 21    |                                 |                                                              |                                |  |


<br/>


## 分类统计：

1、libandroidx.graphics.path.so文件在多个apk中被使用到, 例如：

```bash
[1] com.machiav3lli.fdroid_1107.apk
https://f-droid.org/zh_Hans/packages/com.machiav3lli.fdroid/    <br/> 版本1.1.2 （1107）

[2] com.aurora.store_70.apk
https://f-droid.org/zh_Hans/packages/com.aurora.store/      <br/> 版本4.7.5 （71）

[3] org.fdroid.fdroid_1023051.apk
https://f-droid.org/zh_Hans/packages/org.fdroid.fdroid/ <br/> 版本1.23.1 （1023051）

[4] org.fdroid.basic_1023051.apk
https://f-droid.org/zh_Hans/packages/org.fdroid.basic/ <br/> 版本1.23.1 （1023051）

[5] de.marmaro.krt.ffupdater_179.apk
https://f-droid.org/zh_Hans/packages/de.marmaro.krt.ffupdater/ <br/> 版本81.0.0 （179）

[6] de.readeckapp_800.apk
https://f-droid.org/zh_Hans/packages/de.readeckapp/ <br/> 版本0.8.0（800）

[7] com.desarrollodroide.pagekeeper_51.apk

[8] com.mhss.app.mybrain_15.apk

```

<br>

2、libdatastore_shared_counter.so文件，其静态导出函数没有找到对应的java函数声明。
类似的apk如下

```bash
[1] de.readeckapp_800.apk
https://f-droid.org/zh_Hans/packages/de.readeckapp/ <br/> 版本0.8.0（800）

[2] https://f-droid.org/zh_Hans/packages/com.sakethh.linkora/
https://f-droid.org/zh_Hans/packages/com.sakethh.linkora/  <br/> 版本0.14.0（44）
存在libdatastore_shared_counter.so文件和libsqlitejni.so文件

[3] com.mhss.app.mybrain_15.apk

[4] 

```

<br>

注意：

- de.readeckapp_800.apk 文件包含类别1和2
- com.sakethh.linkora_44.apk 文件包含类别1和2
- nodomain.aditya1875more.stashly_16.apk 文件包含类别1和2

<br>

