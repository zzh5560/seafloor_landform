# awesome-seafloor-dataset-method
## 我们的海底调研工作

**Seafloor海底数据集研究综述** 海底数据集在海洋研究中具有重要意义。通过分析这些数据，我们可以深入了解海底地形、海洋生物分布以及环境变化等方面的信息。主要的数据集来源包括GEBCO、NOAA和SRTM等，它们提供了高分辨率的全球海底地形数据以及海洋水文和气象数据。

---

根据海洋环境特征，我们可以将海洋数据分为水文数据、气象数据、地质数据和生物数据等几大类。

> 水文数据：盐度、温度、浊度
>
> 气象数据：风速和风向、气压、气温
>
> 地质数据：海底地形、沉积物组成、海底地壳活动
>
> 生物数据：浮游植物、浮游动物、鱼类以及其他海洋生物

### 海洋水文数据的调研
#### **全球0.5度海洋盐度格点数据产品（Global ocean salinity grid data product with 0.5-degree spatial resolution）**

**数据集摘要** ：全球0.5度海洋盐度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括CTD, Argo, Bottle, Glider, mooring等观测仪器。该数据集主要基于大气所提出的集合最优插值方法对数据进行空间插值，该方法利用CMIP5多模式的历史模拟和高分辨率样本提供动力集合样本。

**基本信息** ：

时间范围：1960/01-2020/12	 水平分辨率：$0.5°\times0.5°$

空间区域：全球			      垂直分辨率：0-2000米，共41层

经度范围：180°W~180°E	      时间分辨率：月平均

纬度范围：90°S~90°N		   储存格式：nc

要素信息：盐度			      关键词：盐度；全球；全球变化

![2014年12月全球0.5度海表盐度](https://applet.casodc.com//files/metadata/images/salinity_in_IAP_05_sss_year_2014_month_12-1636567603715.png)

**下载链接** ：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456516931682066433&otherId=1456516931803701249

#### **全球0.5度海洋温度格点数据产品(Global ocean temperature grid data product with 0.5-degree spatial resolution)**

**数据集摘要**：全球0.5度海洋温度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括XBT, CTD, Argo, Bottle, MBT, Glider, mooring等观测仪器。该数据应用了大气所提出的XBT数据偏差订正方案（CH14方案）对历史XBT数据进行偏差订正。同时，使用了大气所提出的插值方法（Mapping：改进的集合最优插值）对数据进行空间插值，该方法利用CMIP5多模式的历史模拟和高分辨率样本提供动力集合样本。

**基本信息**：

时间范围：1960/01-2020/12			水平分辨率：0.5°x0.5°

空间区域：全球					    垂直分辨率：0-2000米，共41层

经度范围：180°W~180°E			     时间分辨率：月平均

纬度范围：90°S~90°N				  存储格式：nc

要素信息：温度					     关键词：温度；全球；全球变化

<img src="./Temp_10m_2020_01-1636567791928.png" alt="img" style="zoom:80%;" />

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456577680076988418&otherId=1456577680144097281

#### **全球0.1度高分辨率海洋环流模式HYCOM数据产品（HYCOM Global 0.1-degree high-resolution ocean circulation model data products）**

**数据集摘要**：该数据集是基于HYCOM2.3.01高分辨率准全球海洋模式，对全球温度、盐度、环流的模拟结果。该模式的空间范围为75°S-75°N，纬向与经向分辨率均为0.1°，垂向50层，时间分辨率为30日平均。采用ETOPO1数据改进模式地形，利用ERA5逐时大气变量驱动CTRL实验。

**基本信息：** 

时间范围：2013/01-2022/09			水平分辨率：0.1°

空间范围：准全球					垂直分辨率：3m~500m

经度范围：180°E~180°E				时间分辨率：30日

纬度范围：75°S~75°N				储存格式：NC

要素信息：温度；盐度；海流			关键词：海流；模式；全球；高分辨率；温度

![img](./Fig1a-new-1712694428181.png)

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1777794551860174850&otherId=1777794551939866626

#### **Sea Surface Salinity, Miras SMOS, Near Real-Time, Global 0.25°, 2010-present, 3 Day Composite**

**数据集摘要**：该数据集提供了自2010年以来的全球海表盐度（Sea Surface Salinity, SSS）的近实时观测数据，分辨率为0.25°。数据来源于欧洲航天局（ESA）的微波辐射成像卫星MIRAS（Microwave Imaging Radiometer with Aperture Synthesis），该卫星是土壤湿度和海洋盐度（SMOS, Soil Moisture and Ocean Salinity）任务的一部分。数据集通过每3天合成一次，提供了全球海表盐度的时空分布信息，适用于气候研究、海洋循环模式分析以及与海洋和大气过程相关的各类应用。这些数据可以帮助研究者深入了解全球水循环、海洋动态及其对气候变化的响应。

**可视化图片**：第一个时间点为例

![image-20240816151044461](./image-20240816151044461.png)

**下载链接**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/coastwatchSMOSv662SSS3day/2023/

### 海洋气象数据的调研

#### 中国近海台风路径集合数据集（A dataset of typhoon tracks in offshore China）

**数据集摘要**：1945-2023年度，中国近海台风路径数据集，包含每个台风的真实路径信息、台风强度、气压、中心风速、移动速度、移动方向。

**基本信息**：

时间范围：1944/12-2023/12		水平分辨率：-

空间范围：中国近海			     垂直分辨率：-

经度范围：100°E~180°E		      时间分辨率：6小时

纬度范围：0°N~40°N  			  储存格式：csv

要素信息：台风路径信息、台风强度、气压、移动速度、移动方向

关键词：台风路径信息；气压；中心风速；中国近海；物理海洋

![img](./Snipaste_2021-08-04_10-11-17-1628047390898.png)

**下载地址**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1422759994058625025&otherId=1422760211214520321

### 海洋地质数据的调研

**ETOPO1全球地形模型** 

**数据集摘要**：ETOPO全球地势模型整合了来自区域和全球数据集的地形、测深和海岸线数据，以实现地球表面地球物理特征的全面、高分辨率渲染。该模型旨在支持海啸预报、建模和预警，以及海洋环流建模和地球可视化。当前版本ETOPO 2022有冰面和基岩版本，描绘了覆盖格陵兰岛和南极洲的冰盖顶层，或下面的基岩。

![img](./picture2.jpg)

图1  ETOPO1冰盖全球地形模型（Ice Surface Global Relief Model）

![img](./picture3.jpg)

图2  ETOPO1基岩全球地形模型（Bedrock Global Relief Model）

**数据集下载**：

#### 多金属结核主量元素数据(Major elements of polymetallic nodule)

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成多金属结核主量元素标准数据集。数据量共计1018站,2551个样品，空间范围覆盖全球大部分海域（-180°～180°E，-65.62°～66.68°N），数据要素项包括Mn、Fe、Co、Ni、Cu、Zn、Pb、Al、Si等元素百分含量。

**下载链接** ：https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=1&did=&dataSetId=30

#### 富钴结壳主量元素数据（Major elements of cobalt-rich crust）

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成富钴结壳主量元素标准数据集。数据量共计1203站,3286个样品，空间范围覆盖全球大部分海域（-180°～180°E，-64.18°～56.17°N），数据要素项包括Cu、Ni、Fe、Co、Si、Pb、Al、Mn、Zn等元素百分含量。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=21

### 海洋生物数据的调研

#### COPEPOD海洋生物数据集(COPEPOD marine biology dataset)

**数据集摘要**：数据来源于美国国家海洋渔业中心海岸带与海洋浮游生态、生产和观测数据库，数据集区域为全球。西边经度：-180.0，东边经度：180.0，南边纬度：-78.5，北边纬度：89.0。数据起始时间为：1913.08.30-2013.08.29。共213821个站次。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=59

#### 10米高分辨率全球红树林分布数据集(HGMF_2020)

**数据集摘要**：可持续发展大数据国际研究中心（SDG中心）在高精度全球红树林制图研究方面取得进展，研制了首套高空间分辨率（10米）的全球红树林分布数据集（HGMF_2020）。利用遥感大数据和Google Earth Engine（GEE）云平台，集成影像最大值合成算法（MSIC）以及面向对象随机森林算法（OBRF），提出了一种高效、高精度、高鲁棒性的红树林制图方法体系，构建了首套高空间分辨率（10米）的全球红树林分布数据集，命名为HGMF_2020。

![image-20240816174057030](./image-20240816174057030.png)

**论文** ：https://doi.org/10.1016/j.scib.2023.05.004

**下载链接**：https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PKAN93

#### GLOBEC NEP MOCNESS Plankton (MOC1) Data, 2000-2002

**数据集摘要**：该数据集来源于GLOBEC（Global Ocean Ecosystem Dynamics）项目的东北太平洋（NEP）子计划，具体收集时间为2000年至2002年。MOCNESS（Multiple Opening/Closing Net and Environmental Sensing System）是一种用于收集不同深度的浮游生物样本的系统。通过MOC1设备，研究人员能够获取分层的浮游生物数据，包括生物量、物种组成和丰度等关键信息。

该数据集的核心是通过多次海洋采样，了解浮游生物的垂直分布特征以及其对环境变化的响应。数据可以用于研究海洋生态系统的动态变化、食物网结构、以及与气候变化相关的生态学问题，帮助深入理解海洋生态系统对环境变化的适应机制。

![img](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/tabledap/erdGlobecMoc1.png?longitude,latitude,cast_no&time%3E=2000-05-24T00%3A00%3A00Z&time%3C2002-05-31T00%3A00%3A00Z&longitude%3E=-128.01&longitude%3C=-120.01&latitude%3E=40.94&latitude%3C=48.94&.draw=markers&.marker=5%7C5&.color=0x000000&.colorBar=%7C%7C%7C%7C%7C&.bgColor=0xffccccff)

**数据集下载**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/erdGlobecMoc1/

