# (一)  项目介绍
##  RAG-xiaofeibao-Lungcancer service : 
a RAG + KB(knowlege base & Operation) combo-service for Lung Cancer patient and families to master knowlege and achieve best treatment benefits
## 小肺宝
- 一款面向肺癌患者的RAG技术+知识库整合方案。
- 提供RAG能力加持的AI助手，努力为SLCC患者和家庭高效掌握疾病治疗信息，并获得最大治疗受益。
- 由病友家属和志愿者Chaixiaole/wuxiucong/Jerry苏/zhanggaofeng等，以及小胰宝发起人Sam Qin/Tian Kafei/Lv shaobao，以及Stepfun/零一万物伙伴，携手构建。

--- 

# (二)  项目价值
### 我们希望看到：
｜- 患者都能得到及时准确的医疗知识援助
｜- 专家经验能够极低成本扩散

### 我们可以做到：
｜- 癌症的种类繁多分级分类也多，治疗手段多样，且在空间上极不平衡，在时间上发展极快，我们应当帮助患者理清思路，合理看待，正确治疗，避免不必要的恐惧和过度或低效的治疗方法

### 因为我们相信:
｜一个弱者，在情境中若想崛起，若想为自己的权力抗争，唯一的方法就是尽量发光。不是因为相信这个光可以照亮一切，只是因为黑暗里的一点点光在远处会特别耀眼，其他的光会看到你这扇光。微光会吸引微光，微光会照亮微光，我们相互找到，然后一起发光，才能把压榨的阴霾照亮。

# (三)  开源框架1+1的创新：
｜和传统的代码开源不同，小肺宝强调技术+运营的双开源，以便于使用者能够将技术能力转化为服务价值。

## 3.1 技术栈
感谢如下开源的技术栈资源提供方，也应为你们，我们可以为SCLC肿瘤患者和家庭提供切实的帮助，加油！我们也努力在代码部分建立自己的贡献，比如插件类，优化类，以及定制模块比如KB的自动化转化。

### RAG产品：
[Dify](https://github.com/langgenius/dify)：很好的承载和提供小肺宝所需要的RAG能力，包括知识库构建，agent构建，工作流构建，公众号和bot的发布，作为最具特色的插件和LLM生态，我们使用dify，根据SCLC患者需求场景，通过实践和测试，选择适配的最佳LLM（比如文本逻辑，影像解析等）以及插件生态（比如论文搜索，定制插件），同时也保持应用段的扩展性，以及知识库前置处理的自定义模块。

### 文档处理：
我们使用Doc2X和MinerU作为文档转化的技术栈，一方面提升文件格式的高质量转化，更有特色的是实现了大量严肃的治疗指南和治疗文档中的图文混排。

### 患者互动端： 
 - [dify-on-wechat](https://github.com/hanfangyuan4396/dify-on-wechat)： 使用DOW，很便捷的接入病友微信群，让bot成为一个使用门槛更低，体验更佳的渠道，我们对DOW做了优化，以便于和SLCLPal的应用结合起来，比如QA记录和分析。

## 3.2 运营栈 
### 3.2.1. 知识库体系框架
示意图

### 3.2.2. 知识库API申请
由于内容的研究性和法规责任约束，我们无法直接开源知识库，但是我们愿意通过开放知识库API能力，来帮助开源公益的诉求，比如测试和对比，或者小范围应用。公益项目的API资源有限，，如果有商业场景需求或者大规模使用场景，也可以联系我们。

### 3.2.3. 运营体系框架
示意图

### 3.2.4. 小肺宝上线国内的主流平台
#### 腾讯元器：
1. [小肺宝web端](https://yuanbao.tencent.com/chat/yn4tWRj9x3lm)  <br>
2. 小程序端<br>
<img src="https://github.com/user-attachments/assets/ac5939ef-04f9-4535-8366-6e23ccef92f3" width="185" alt="小程序端">

---
#### Cozy:
(to be filled)

---
#### Baidu:
(to be filled)


#### zhipu:
(to be filled)

---


# (四) 产品功能V1.0
（待补充）


# (五) 肺癌患者宝典 
[NCCN Guideline English](https://www.nccn.org/professionals/physician_gls/pdf/sclc.pdf)<br>
[NCCN Guideline 中文版](https://www.nccn.org/professionals/physician_gls/pdf/sclc-chinese.pdf)<br>
[NNCN患者手册](https://www.nccn.org/patients/guidelines/content/PDF/SCLC-patient-guideline.pdf)<br>

# (五) 肺癌患者社群
- 微信公众号：搜索“小肺宝助手”，关注即可。
- 小红书： 搜索“小肺宝助手”，关注即可。
- 社群：微信扫码快速加入社群。

# （六）志愿者招募
小肺宝团队需要持续招募如下职能志愿者：
1. 运营团队：涵盖多个领域，招募医学顾问、数据分析师、用户体验设计师以及社群服务专员等背景志愿者，需要6小时以上/周的工作时间。
2. RAG团队：提供RAG技术和应用开发能力，提供从KB建立到RAG质量闭环提升的全部工作，需要1-2年RAG实际操作经验和独当一面的能力；
3. 知识库团队：提供专业医疗背景，对于后续知识库的更新和维护提供专业意见，欢迎临床，药学，护理背景的公益志愿者。

# 🌟 贡献者
![Contributors 贡献者](https://contrib.rocks/image?repo=PancrePal-xiaoyibao/PancrePal-xiaoyibao&Max=1000")
