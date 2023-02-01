# MaxGrade-E

名称：MaxGrade-E
类型：Win可执行程序
版权声明：Copyright (c) 2023 Hung
程序描述：最大等级-E，指获取最大等级的易语言程序

## 一、全局变量

	- Start_check （运行状态，用于防止运行中手动关闭程序）
	- Epath （易语言程序路径）

## 二、启动窗口

### 1. 菜单
- 启动
- 执行
- 5.93 版本
- Linker
- VC++ 6.0
- 设置
- 启始页
- 程序位置
- 关于
- 开发文档
- 关于 MaxGrade-E

### 2. 组件
- 编辑框_输出
- 标签_位置
- 编辑框_路径
- 图片框_状态
- ZIP压缩

### 3. 子程序
- run_check（运行前检查）
- 菜单程序位置 （设置易语言位置）
- 菜单启始页（打开Start_Page窗口）
- 窗口可否被关闭（防止运行中手动关闭程序）
- 菜单关于MaxGradeE（打开About_Page窗口）
- 菜单版593（运行StartE593）
- StartE593 （写入易语言5.93程序）
- Output_time（输出显示时间）
- VC6linker （写入VC6linker编译器）
- 菜单VC6（运行VC6linker）
- 开发文档（打开Help_Page窗口）

## 三、Start_Page 窗口

### 1. 组件
- 分组框_启始页
- 单选框_开启
- 单选框_关闭

### 2. 子程序
- run_check（运行前检查）
- 单选框_开启（易语言启始页开启）
- 单选框_关闭（易语言启始页关闭）
- UI （子窗口窗口位置）

## 四、About_Page 窗口

### 1. 组件
- 标签_标题
- 标签_副标题
- 标签_版本
- 标签_说明1
- 标签_说明2
- 图片框_logo
- 编辑框_版本
- 按钮_确认

### 2. 子程序
- Copyright （版权信息）
- Ctime （版权时间）
- UI （子窗口窗口位置）
- 按钮_确认（关闭窗口）

## 五、Help_Page 窗口

### 1. 组件
- 编辑框_说明
- 按钮_了解

### 2. 子程序
- 按钮_了解（关闭窗口）
- help（开发文档）

## 六、资源表
- E5931（易语言5.93有启动页）
- E5930（易语言5.93无启动页）
- VC6linker （VC6linker编译器）
- linker_ini（易语言默认linker.ini）
- normal （正常图标）
- error（错误图标）
- load（加载图标）

## 七、常量表
- help_page （开发文档）
