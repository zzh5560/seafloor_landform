# awesome-seafloor-dataset-method
## 我们的海底调研工作

**Seafloor海底数据集研究综述** 海底数据集在海洋研究中具有重要意义。通过分析这些数据，我们可以深入了解海底地形、海洋生物分布以及环境变化等方面的信息。主要的数据集来源包括GEBCO、NOAA和SRTM等，它们提供了高分辨率的全球海底地形数据以及海洋水文和气象数据。

---

根据海洋环境特征，我们可以将海洋数据分为水文数据、地质数据和生物数据等几大类。

> 水文数据：盐度、温度、浊度
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

### **IAP全球海洋温度1°格点数据集(IAP Global Ocean Temperature 1° Gridded Dataset)**
**基本信息** :

时间范围:1940/01-2023/12          水平分辨率:  1° 

空间区域:  全球               垂直分辨率:  0-6000m; 119层

经度范围:  180°W~180°E         时间分辨率:  逐月

纬度范围:  90°S~90°N          存储格式:  NetCDF

要素信息:  温度               关键词:  温度;全球 

![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/IAP%20temp-1705313270219.png)
**下载链接** ：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1746836580808540162&otherId=1746836581001478146

#### **全球0.5度海洋温度格点数据产品(Global ocean temperature grid data product with 0.5-degree spatial resolution)**

**数据集摘要**：全球0.5度海洋温度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括XBT, CTD, Argo, Bottle, MBT, Glider, mooring等观测仪器。该数据应用了大气所提出的XBT数据偏差订正方案（CH14方案）对历史XBT数据进行偏差订正。同时，使用了大气所提出的插值方法（Mapping：改进的集合最优插值）对数据进行空间插值，该方法利用CMIP5多模式的历史模拟和高分辨率样本提供动力集合样本。

**基本信息**：

时间范围：1960/01-2020/12			水平分辨率：0.5°x0.5°

空间区域：全球					    垂直分辨率：0-2000米，共41层

经度范围：180°W~180°E			     时间分辨率：月平均

纬度范围：90°S~90°N				  存储格式：nc

要素信息：温度					     关键词：温度；全球；全球变化

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/Temp_10m_2020_01-1636567791928.png)

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456577680076988418&otherId=1456577680144097281

#### **全球0.1度高分辨率海洋环流模式HYCOM数据产品（HYCOM Global 0.1-degree high-resolution ocean circulation model data products）**

**数据集摘要**：该数据集是基于HYCOM2.3.01高分辨率准全球海洋模式，对全球温度、盐度、环流的模拟结果。该模式的空间范围为75°S-75°N，纬向与经向分辨率均为0.1°，垂向50层，时间分辨率为30日平均。采用ETOPO1数据改进模式地形，利用ERA5逐时大气变量驱动CTRL实验。

**基本信息：** 

时间范围：2013/01-2022/09			水平分辨率：0.1°

空间范围：准全球					垂直分辨率：3m~500m

经度范围：180°E~180°E				时间分辨率：30日

纬度范围：75°S~75°N				储存格式：NC

要素信息：温度；盐度；海流			关键词：海流；模式；全球；高分辨率；温度

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240818103408.png)

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1777794551860174850&otherId=1777794551939866626

#### **Sea Surface Salinity, Miras SMOS, Near Real-Time, Global 0.25°, 2010-present, 3 Day Composite**

**数据集摘要**：该数据集提供了自2010年以来的全球海表盐度（Sea Surface Salinity, SSS）的近实时观测数据，分辨率为0.25°。数据来源于欧洲航天局（ESA）的微波辐射成像卫星MIRAS（Microwave Imaging Radiometer with Aperture Synthesis），该卫星是土壤湿度和海洋盐度（SMOS, Soil Moisture and Ocean Salinity）任务的一部分。数据集通过每3天合成一次，提供了全球海表盐度的时空分布信息，适用于气候研究、海洋循环模式分析以及与海洋和大气过程相关的各类应用。这些数据可以帮助研究者深入了解全球水循环、海洋动态及其对气候变化的响应。

**可视化图片**：第一个时间点为例

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/image-20240816151044461.png)

**下载链接**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/coastwatchSMOSv662SSS3day/2023/

### 海洋地质数据的调研

#### **GEBCO海洋数据** 

**数据集摘要**GEBCO数据的全称是General Bathymetric Chart of the Oceans (全球海洋通用水深数据) ，是由国际海道测量组织 (IHO) 和政府间海洋学委员会 (IOC) 联合发布的最全面的世界大洋海底地形数据，也是当今海洋模式中最常用的海洋水深数据之一。 GEBCO的数据主要来源于多波束声呐测深、卫星测高和其他海洋测量技术。这些数据经过处理和整合，生成了详细的海底地形图。

**基本信息**

- **分辨率**：GEBCO提供的地形数据分辨率高达30米。
- **覆盖范围**：全球海洋，包括深海和沿海区域。
- **数据格式**：NetCDF、GeoTIFF等多种格式，便于不同应用场景使用。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240819193559.png)

**数据下载**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=3&did=&dataSetId=86-1

#### **ETOPO1全球地形模型** 

**数据集摘要**：ETOPO全球地势模型整合了来自区域和全球数据集的地形、测深和海岸线数据，以实现地球表面地球物理特征的全面、高分辨率渲染。该模型旨在支持海啸预报、建模和预警，以及海洋环流建模和地球可视化。当前版本ETOPO 2022有冰面和基岩版本，描绘了覆盖格陵兰岛和南极洲的冰盖顶层，或下面的基岩。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/picture2.jpg)

图1  ETOPO1冰盖全球地形模型（Ice Surface Global Relief Model）

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/picture3.jpg)

图2  ETOPO1基岩全球地形模型（Bedrock Global Relief Model）

**数据集下载**：https://www.ncei.noaa.gov/products/etopo-global-relief-model

#### 多金属结核主量元素数据(Major elements of polymetallic nodule)

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成多金属结核主量元素标准数据集。数据量共计1018站,2551个样品，空间范围覆盖全球大部分海域（-180°～180°E，-65.62°～66.68°N），数据要素项包括Mn、Fe、Co、Ni、Cu、Zn、Pb、Al、Si等元素百分含量。

**下载链接** ：https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=1&did=&dataSetId=30

#### 富钴结壳主量元素数据（Major elements of cobalt-rich crust）

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成富钴结壳主量元素标准数据集。数据量共计1203站,3286个样品，空间范围覆盖全球大部分海域（-180°～180°E，-64.18°～56.17°N），数据要素项包括Cu、Ni、Fe、Co、Si、Pb、Al、Mn、Zn等元素百分含量。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=21

#### 3弧秒（90 m）全球DEM数据集GDEM_2022

**数据集摘要**：GDEM_2022是由清华大学发布的全球3弧秒（约90米）分辨率的海陆数字高程模型数据集。该数据集利用深度学习和迁移学习技术，基于NASA和GEBCO数据，提供了比传统方法更精确的地形信息，支持全球气候变化、海洋研究等领域。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/71aee5ebd3b3694aa9bf47a3e57fbde.png)

上图为3弧秒（90 m）全球DEM数据集GDEM_2022

**数据集下载**：https://cloud.tsinghua.edu.cn/d/695ed43696564904980f

#### Seton et al. (2020) - present day age grid and seafloor spreading parameters

**数据集摘要**：Seton et al. (2020) 提供了一个现代海床年龄网格和扩张参数数据集，这是一个重要的地质学资源，用于研究地球的板块构造和海底地质历史。数据集包含了当前海床的年龄分布和与之相关的扩张速率信息，这些数据是通过分析海洋地质数据和地球物理测量得到的。该数据集对于理解板块运动、海底扩张过程以及相关的地质活动具有重要意义，支持地质学家和地球物理学家在海洋地质学、地震学和资源勘探等领域的研究。

🌟海洋地壳年龄：海洋地壳的年龄可以反映地壳形成和演化的过程，以及与之相关的地质活动。
![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/cf9f3287c95a4c073f92fa45beaf52e.png)
*海洋地壳年龄，单位为百万年*

🌟海底扩张率：海底扩张率是板块构造理论的核心组成部分，描述了海底地壳在大洋中脊或其他构造板块边界形成的速度。
![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/879a27482a0f2450a4bb3c7a93f9612.png)
 *（a） 当今海底扩张率网格。（b） 当今的传播模式网格。超慢 = <20 毫米/年，慢速 = 20-55 毫米/年，中等 = 55-75 毫米/年，快速 = 75-180 毫米/年，超快 = >180 毫米/年。直方图插入显示每种扩展模式的百分比。*

🌟共轭脊侧翼上的地壳增生和海底扩张方向性：共轭脊侧翼上的地壳增生是指在海洋板块构造中，两个相对的洋中脊（共轭洋中脊）两侧的地壳增长现象。海底扩张通常伴随着新的地壳形成，新形成的地壳会记录下地球磁场的方向。通过测量海底的磁异常，科学家可以推断出地壳形成时的磁场方向，从而确定扩张方向。
![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/c535d7ecce490c69694d0c59f77d767.png)
*（a）共轭脊侧翼上的地壳增生百分比是指通过海底扩张过程中新地壳的形成程度。（b) 当今的传播方向网格。*

🌟蔓延倾角网络：描述海底地形特征的一个重要参数，它指的是海底地形相对于水平面的倾斜程度。
![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/e7d3b857e2449a21a4a6644ccb8edcd.png)
*现在的蔓延倾角网格。高于 45° 的值表示断裂带段，用白色表示。插入显示按扩展模式分隔的扩展倾角的百分比分布。*

**论文链接**：https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020GC009214

**数据集下载**：https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/

#### Deep-sea sediments of the global ocean mapped with Random Forest machine learning algorithm

**数据集摘要**：这个数据集利用随机森林机器学习算法对全球深海沉积物进行了映射。它通过分析各种海洋地质和地球物理数据，创建了一个全球深海沉积物分布的详细图谱。数据集包含了深海沉积物的类型、厚度和分布特征，为研究深海地质环境、古海洋学、海底资源分布和全球气候变化提供了宝贵的信息。随机森林算法的应用提高了沉积物分类的准确性，并允许在数据稀疏区域进行有效的预测，从而为深海勘探和环境评估提供了强有力的技术支持。

🌟深海沉积物空间分布：

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/b5e5b737ee8a83b3bf41047a639dd92.png)

**分别为钙质软泥、黏土、硅藻软泥、固体沉积物、放射虫软泥的可能性分布**

**下载链接**：https://doi.pangaea.de/10.1594/PANGAEA.911692

#### Total sediment thickness of the World’s Oceans & Marginal Seas, version 2 

**数据集摘要**：Total Sediment Thickness of the World’s Oceans & Marginal Seas, version 2 是一个全球性的海洋沉积物厚度数据库。这个数据集由Gaina等人在2019年通过Geochemistry, Geophysics, Geosystems期刊发表，名为GlobSed。它提供了一个5弧分钟分辨率的全球海洋和边缘海的总沉积物厚度网格28。与之前的全球网格相比，GlobSed覆盖了更大的区域，并且在北大西洋、北极、南大洋和地中海区域进行了更新，导致估算的总海洋沉积物体积增加了29.7%28。

🌟世界海洋和边缘海的总沉积物厚度：在边缘地区，沉积物厚度估计是通过速度-深度（velocity-depth）反射数据计算得出的。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/1749768499028682ad438d146b81d26.png)

**图片表示了沉积物的厚度，范围由0-20000米**

**下载链接**：https://www.earthbyte.org/total-sediment-thickness-of-the-worlds-oceans-marginal-seas-version-2/

#### NGDC Seafloor Sediment Grain Size Database

**下载链接**：https://www.ngdc.noaa.gov/mgg/geology/data/g00127/

#### Deck41表层海底沉积物描述数据库

**下载链接**：https://www.ngdc.noaa.gov/mgg/geology/data/g02094/

### 海洋生物数据的调研

#### COPEPOD海洋生物数据集(COPEPOD marine biology dataset)

**数据集摘要**：数据来源于美国国家海洋渔业中心海岸带与海洋浮游生态、生产和观测数据库，数据集区域为全球。西边经度：-180.0，东边经度：180.0，南边纬度：-78.5，北边纬度：89.0。数据起始时间为：1913.08.30-2013.08.29。共213821个站次。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=59

#### 10米高分辨率全球红树林分布数据集(HGMF_2020)

**数据集摘要**：可持续发展大数据国际研究中心（SDG中心）在高精度全球红树林制图研究方面取得进展，研制了首套高空间分辨率（10米）的全球红树林分布数据集（HGMF_2020）。利用遥感大数据和Google Earth Engine（GEE）云平台，集成影像最大值合成算法（MSIC）以及面向对象随机森林算法（OBRF），提出了一种高效、高精度、高鲁棒性的红树林制图方法体系，构建了首套高空间分辨率（10米）的全球红树林分布数据集，命名为HGMF_2020。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/image-20240816174057030.png)

**论文** ：https://doi.org/10.1016/j.scib.2023.05.004

**下载链接**：https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PKAN93

#### GLOBEC NEP MOCNESS Plankton (MOC1) Data, 2000-2002

**数据集摘要**：该数据集来源于GLOBEC（Global Ocean Ecosystem Dynamics）项目的东北太平洋（NEP）子计划，具体收集时间为2000年至2002年。MOCNESS（Multiple Opening/Closing Net and Environmental Sensing System）是一种用于收集不同深度的浮游生物样本的系统。通过MOC1设备，研究人员能够获取分层的浮游生物数据，包括生物量、物种组成和丰度等关键信息。

该数据集的核心是通过多次海洋采样，了解浮游生物的垂直分布特征以及其对环境变化的响应。数据可以用于研究海洋生态系统的动态变化、食物网结构、以及与气候变化相关的生态学问题，帮助深入理解海洋生态系统对环境变化的适应机制。

![img](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/tabledap/erdGlobecMoc1.png?longitude,latitude,cast_no&time%3E=2000-05-24T00%3A00%3A00Z&time%3C2002-05-31T00%3A00%3A00Z&longitude%3E=-128.01&longitude%3C=-120.01&latitude%3E=40.94&latitude%3C=48.94&.draw=markers&.marker=5%7C5&.color=0x000000&.colorBar=%7C%7C%7C%7C%7C&.bgColor=0xffccccff)

**数据集下载**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/erdGlobecMoc1/

#### Image dataset of common benthic foraminifera in surface sediments of the North Atlantic Ocean

**数据集摘要**：北大西洋表层沉积物中底栖有孔虫的图像数据集提供了106种不同类群的显微照片，这些数据对于研究海洋环境和古海洋学至关重要。这些有孔虫是了解海底环境条件的关键指标，图像集有助于物种识别和环境重建。

**数据集下载**：https://doi.org/10.1016/j.dib.2019.104554

---

## 海底数据集下载

### 海洋水文数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [全球0.5度海洋盐度格点数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456516931682066433&otherId=1456516931803701249) | 全球0.5度海洋盐度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括CTD, Argo, Bottle, Glider, mooring等观测仪器。 |
| [IAP全球海洋温度1°格点数据集](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1746836580808540162&otherId=1746836581001478146) | 该数据集的原始数据为来自全球海洋数据库（WOD）中的所有现场观测数据 |
| [全球0.5度海洋温度格点数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456577680076988418&otherId=1456577680144097281) | 全球0.5度海洋温度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括XBT, CTD, Argo, Bottle, MBT, Glider, mooring等观测仪器。 |
| [全球0.1度高分辨率海洋环流模式HYCOM数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1777794551860174850&otherId=1777794551939866626) | 该数据集是基于HYCOM2.3.01高分辨率准全球海洋模式，对全球温度、盐度、环流的模拟结果。该模式的空间范围为75°S-75°N，纬向与经向分辨率均为0.1°，垂向50层，时间分辨率为30日平均。 |
| [Sea Surface Salinity, Miras SMOS, Near Real-Time, Global 0.25°, 2010-present, 3 Day Composite](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/coastwatchSMOSv662SSS3day/2023/) | 该数据集提供了自2010年以来的全球海表盐度（Sea Surface Salinity, SSS）的近实时观测数据，分辨率为0.25°。数据来源于欧洲航天局（ESA）的微波辐射成像卫星MIRAS（Microwave Imaging Radiometer with Aperture Synthesis），该卫星是土壤湿度和海洋盐度（SMOS, Soil Moisture and Ocean Salinity）任务的一部分。 |

### 海洋地质数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [GEBCO海洋数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=3&did=&dataSetId=86-1) | 数据来源于全球海陆数据库（GEBCO），全球海陆栅格地形数据，数据分辨率为30″，约为900m，数据公布时间为2014年。 |
| [ETOPO全球地势模型](https://www.ncei.noaa.gov/products/etopo-global-relief-model) | ETOPO全球地势模型整合了来自区域和全球数据集的地形、测深和海岸线数据，以实现地球表面地球物理特征的全面、高分辨率渲染。 |
| [多金属结核主量元素数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=1&did=&dataSetId=30) | 数据量共计1018站,2551个样品，空间范围覆盖全球大部分海域（-180°～180°E，-65.62°～66.68°N），数据要素项包括Mn、Fe、Co、Ni、Cu、Zn、Pb、Al、Si等元素百分含量。 |
| [富钴结壳主量元素数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=21) | 数据量共计1203站,3286个样品，空间范围覆盖全球大部分海域（-180°～180°E，-64.18°～56.17°N），数据要素项包括Cu、Ni、Fe、Co、Si、Pb、Al、Mn、Zn等元素百分含量。 |
| [3弧秒（90 m）全球DEM数据集GDEM_2022](https://cloud.tsinghua.edu.cn/d/695ed43696564904980f) | GDEM_2022是由清华大学发布的全球3弧秒（约90米）分辨率的海陆数字高程模型数据集。该数据集利用深度学习和迁移学习技术，基于NASA和GEBCO数据，提供了比传统方法更精确的地形信息，支持全球气候变化、海洋研究等领域。 |
| [Seton et al. (2020) - present day age grid and seafloor spreading parameters](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/) | 新的海洋地壳年龄网格以及扩散速率、不对称性、方向性和倾斜度的互补网格 |
| [Deep-sea sediments of the global ocean mapped with Random Forest machine learning algorithm](https://doi.pangaea.de/10.1594/PANGAEA.911692) |         对全球海洋深海沉积物的海底岩性进行了空间预测         |
| [Total sediment thickness of the World’s Oceans & Marginal Seas, version 2](https://www.earthbyte.org/total-sediment-thickness-of-the-worlds-oceans-marginal-seas-version-2/) |                世界海洋和边缘海的总沉积物厚度                |
| [NGDC Seafloor Sediment Grain Size Database](https://www.ngdc.noaa.gov/mgg/geology/data/g00127/) | NGDC海底沉积物粒度数据库包含全球 17,000 多个海底样本的粒度数据 |
| [Deck41 表层海底沉积物描述数据库](https://www.ngdc.noaa.gov/mgg/geology/data/g02094/) |  Deck41 是全球 36,401 个海底样本的表层沉积物成分的数字摘要   |

### 海洋生物数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [COPEPOD海洋生物数据集](https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=59) | 数据来源于美国国家海洋渔业中心海岸带与海洋浮游生态、生产和观测数据库，数据集区域为全球。西边经度：-180.0，东边经度：180.0，南边纬度：-78.5，北边纬度：89.0。数据起始时间为：1913.08.30-2013.08.29。共213821个站次。 |
| [10米高分辨率全球红树林分布数据集](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PKAN93) | 可持续发展大数据国际研究中心（SDG中心）在高精度全球红树林制图研究方面取得进展，研制了首套高空间分辨率（10米）的全球红树林分布数据集（HGMF_2020）。 |
| [GLOBEC NEP MOCNESS Plankton (MOC1) Data, 2000-2002](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/erdGlobecMoc1/) | MOCNESS（Multiple Opening/Closing Net and Environmental Sensing System）是一种用于收集不同深度的浮游生物样本的系统。通过MOC1设备，研究人员能够获取分层的浮游生物数据，包括生物量、物种组成和丰度等关键信息。 |
| [Image dataset of common benthic foraminifera in surface sediments of the North Atlantic Ocean](https://doi.org/10.1016/j.dib.2019.104554) |     在26个抓取站收集的表层沉积物中106个底栖有孔虫分类群      |

