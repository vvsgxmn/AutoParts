## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的汽车零部件销售系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向汽车后市场配件流通的 B2C/B2B 商城与进销存平台，针对线下柜面询价效率低、车型年款组合繁多、OE 原厂件号易抄错、库存台账与销售出库脱节、售后评价难回溯等问题，把品牌车型库、配件商品库、进销存台账、商城下单履约与 VIN 查件工单整合到同一套前后端分离工程中。

系统采用 SpringBoot + Vue 架构，区分采购客户与系统管理员：客户端按品牌车系/品类检索配件、查看 OE 与适配清单、购物车结算与订单退款评价，并可提交 VIN 查件；管理端维护车型商品、出入库与供应商，处理发货退款与查件答复，并在经营大盘查看销售额、品类占比与库存预警。库存随出入库联动、低于预警值大盘提示，适合毕设、课设与汽配电商学习参考。

## 主要功能模块

- **用户认证与角色分流**：采购客户与管理员统一登录，JWT 鉴权；/admin 仅 ADMIN 可进
- **车型筛选商城**：品牌→车系年款→品类/关键词/价格筛选，爆款与轮播推荐
- **配件详情**：OE 原厂编号、材质规格、质保、适配车型表与车主评价，库存不足不可超卖加购
- **购物车与结算**：增减数量、收货地址、满额包邮规则，模拟收银台支付后进入待发货
- **订单履约**：待付款/待发货/已发货/已完成/已取消全状态；确认收货后可评价，退款须审核
- **VIN 查件工单**：提交 17 位车架号与需求说明，管理员报价并关联商城配件
- **养车指南与个人中心**：分类文章阅读，爱车绑定、多地址与密码维护
- **经营数据大盘**：累计销售额、订单数、在售商品、库存预警，销售趋势与品类占比图表
- **主数据中台**：品牌/车系车型/品类/商品档案，上下架与预警库存
- **进销存与供应商**：采购入库/销售出库台账联动库存，供应商名录维护
- **履约审核**：物流发货、退款同意/驳回、查件工单答复与推荐配件
- **论文与 UML 概览**：配套论文设计实现页拼图与 UML 图列表，便于答辩材料对照

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E9%85%8D%E4%BB%B6%E5%95%86%E5%9F%8E.png" alt="配件商城" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/VIN%E6%9F%A5%E4%BB%B6.png" alt="VIN查件" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E6%88%91%E7%9A%84%E8%AE%A2%E5%8D%95.png" alt="我的订单" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E7%AE%A1%E7%90%86%E5%91%98%E7%BB%8F%E8%90%A5%E5%A4%A7%E7%9B%98.png" alt="管理员经营大盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E9%85%8D%E4%BB%B6%E5%95%86%E5%93%81%E7%AE%A1%E7%90%86.png" alt="配件商品管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E9%94%80%E5%94%AE%E8%AE%A2%E5%8D%95%E7%AE%A1%E7%90%86.png" alt="销售订单管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/autoparts/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->
