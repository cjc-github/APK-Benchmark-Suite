# APK列表

本文档记录了用于测试的APK文件及其特性信息。

---

## APK文件详情

### 1. com.machiav3lli.fdroid_1107.apk

- **来源**: https://f-droid.org/zh_Hans/packages/com.machiav3lli.fdroid/
- **版本**: 1.1.2 (1107)
- **添加理由**: 导出符号JNI_OnLoad存在后缀符号
- **主要so文件**: libandroidx.graphics.path.so

---

### 2. com.looker.droidify_660.apk

- **来源**: https://f-droid.org/zh_Hans/packages/com.looker.droidify/
- **版本**: 0.6.6 (660)
- **添加理由**: 静态导出符号在Smali中没有找到
- **主要so文件**: libdatastore_shared_counter.so

---

### 3. com.aurora.store_70.apk

- **来源**: https://f-droid.org/zh_Hans/packages/com.aurora.store/
- **版本**: 4.7.5 (71)
- **主要so文件**: libandroidx.graphics.path.so

---

### 4. org.fdroid.fdroid_1023051.apk

- **来源**: https://f-droid.org/zh_Hans/packages/org.fdroid.fdroid/
- **版本**: 1.23.1 (1023051)
- **主要so文件**: libandroidx.graphics.path.so

---

### 5. org.fdroid.basic_1023051.apk

- **来源**: https://f-droid.org/zh_Hans/packages/org.fdroid.basic/
- **版本**: 1.23.1 (1023051)
- **主要so文件**: libandroidx.graphics.path.so

---

### 6. de.marmaro.krt.ffupdater_179.apk

- **来源**: https://f-droid.org/zh_Hans/packages/de.marmaro.krt.ffupdater/
- **版本**: 81.0.0 (179)
- **主要so文件**: libandroidx.graphics.path.so

---

### 7. de.readeckapp_800.apk

- **来源**: https://f-droid.org/zh_Hans/packages/de.readeckapp/
- **版本**: 0.8.0 (800)
- **主要so文件**: libandroidx.graphics.path.so, libdatastore_shared_counter.so
- **备注**: 同时包含类别1和类别2的so文件

---

### 8. com.desarrollodroide.pagekeeper_51.apk

- **主要so文件**: libandroidx.graphics.path.so

---

### 9. com.mhss.app.mybrain_15.apk

- **主要so文件**: libandroidx.graphics.path.so

---

### 10. com.sakethh.linkora_44.apk

- **来源**: https://f-droid.org/zh_Hans/packages/com.sakethh.linkora/
- **版本**: 0.14.0 (44)
- **主要so文件**: libandroidx.graphics.path.so, libdatastore_shared_counter.so, libsqlitejni.so
- **备注**: 同时包含类别1和类别2的so文件

---

### 11. nodomain.aditya1875more.stashly_16.apk

- **备注**: 同时包含类别1和类别2的so文件

---

## 分类统计

### 类别1：包含 libandroidx.graphics.path.so 的APK

以下APK文件中使用了 `libandroidx.graphics.path.so` 文件：

1. com.machiav3lli.fdroid_1107.apk
2. com.aurora.store_70.apk
3. org.fdroid.fdroid_1023051.apk
4. org.fdroid.basic_1023051.apk
5. de.marmaro.krt.ffupdater_179.apk
6. de.readeckapp_800.apk
7. com.desarrollodroide.pagekeeper_51.apk
8. com.mhss.app.mybrain_15.apk

### 类别2：包含 libdatastore_shared_counter.so 的APK

以下APK文件中使用了 `libdatastore_shared_counter.so` 文件，其静态导出函数没有找到对应的java函数声明：

1. com.looker.droidify_660.apk
2. de.readeckapp_800.apk
3. com.sakethh.linkora_44.apk (同时还包含 libsqlitejni.so)
4. com.mhss.app.mybrain_15.apk

---

## 注意事项

- `de.readeckapp_800.apk` 文件同时包含类别1和类别2的so文件
- `com.sakethh.linkora_44.apk` 文件同时包含类别1和类别2的so文件
- `nodomain.aditya1875more.stashly_16.apk` 文件同时包含类别1和类别2的so文件