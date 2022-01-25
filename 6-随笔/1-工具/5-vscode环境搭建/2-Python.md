---
sort: 2
---

# Python

## Python解释器

### 安装python环境

![image-20220123093416506](2-Python.assets/image-20220123093416506.png)

### 创建vscode-python文件夹

<img src="2-Python.assets/image-20220123093921230.png" alt="image-20220123093921230" style="zoom:67%;" />

#### 裸配置

<img src="2-Python.assets/image-20220123094715834.png" alt="image-20220123094715834" style="zoom: 50%;" />

如图，与在命令行运行无区别

### 安装vscode-python插件

### code插件运行.py

![image-20220123100607753](2-Python.assets/image-20220123100607753.png)

#### 添加配置文件

![image-20220123100627944](2-Python.assets/image-20220123100627944.png)

##### program

>   设置启动文件

```
"program": "${file}",
```

code宏定义：选中那个文件 *F5* 运行那个文件

#### code调试功能

-   设置断点后， *F5* 运行至断点处

![image-20220123101910568](2-Python.assets/image-20220123101910568.png)

-   *F10* 从断点处逐行执行

    ![image-20220123102101638](2-Python.assets/image-20220123102101638.png)

    ![image-20220123102117563](2-Python.assets/image-20220123102117563.png)

## 跨文件夹调用

![image-20220123105703824](2-Python.assets/image-20220123105703824.png)

```python
import sys
sys.path.append("./") # 将当前文件夹添加到系统目录中
```

![image-20220123105921463](2-Python.assets/image-20220123105921463.png)

## conda管理python环境

### 查看已有环境

```shell
conda info -e
```

![image-20220123121403098](2-Python.assets/image-20220123121403098.png)

### 新建环境conda

```shell
conda create -n [env_name] python=3.xx
```

<img src="2-Python.assets/image-20220123121541983.png" alt="image-20220123121541983" style="zoom:67%;" />

### 使用conda环境

```shell
conda activate [env_name]
```

<img src="2-Python.assets/image-20220123121740761.png" alt="image-20220123121740761" style="zoom:67%;" />![image-20220123121906318](2-Python.assets/image-20220123121906318.png)



