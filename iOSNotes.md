# FileManager

新建路径：
1. 获取目录：FileManager.default.urls[0]
2. 目录添加路径：URL(fileURLWithPath：路径名，relativeTo：目录地址)
3. .appendingPathComponent(or Extension)

数据写入指定路径：Try object.write(to:路径)
读取数据从指定路径：Try object(contentsOf:路径)
