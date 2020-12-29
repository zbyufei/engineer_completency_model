工程师职级胜任力框架
===
- [工程师职级胜任力框架](#工程师职级胜任力框架)
- [一、前言](#一前言)
- [二、目标](#二目标)
- [三、说明](#三说明)
- [四、职级和胜任力评估框架](#四职级和胜任力评估框架)
  - [1、技术技能](#1技术技能)
    - [1.1 质量和测试](#11-质量和测试)
      - [1.1.1 写代码](#111-写代码)
      - [1.1.2 测试](#112-测试)
      - [1.1.3 调试](#113-调试)
      - [1.1.4 可观测性(Observability)](#114-可观测性observability)
    - [1.2 软件设计和架构](#12-软件设计和架构)
      - [1.2.1 理解领域(domain)](#121-理解领域domain)
      - [1.2.2 软件架构](#122-软件架构)
      - [1.2.3 安全](#123-安全)
  - [2、交付](#2交付)
    - [2.1 增量价值交付](#21-增量价值交付)
      - [2.1.1 任务分解](#211-任务分解)
      - [2.1.2 优先级和依赖分析](#212-优先级和依赖分析)
      - [2.1.3 应对不确定性(Dealing with ambiguity)](#213-应对不确定性dealing-with-ambiguity)
    - [2.2 自我组织(self-organization)](#22-自我组织self-organization)
      - [2.2.1 可信赖和责任感](#221-可信赖和责任感)
      - [2.2.2 经济思维](#222-经济思维)
  - [3、反馈、沟通和协作](#3反馈沟通和协作)
    - [3.1 反馈](#31-反馈)
      - [3.1.1 提供反馈](#311-提供反馈)
      - [3.1.2 寻求和接收反馈](#312-寻求和接收反馈)
    - [3.2 沟通](#32-沟通)
      - [3.2.1 有效沟通(Effective communication)](#321-有效沟通effective-communication)
      - [3.2.2 知识分享](#322-知识分享)
    - [3.3 协作](#33-协作)
      - [3.3.1 团队合作(Teamwork)](#331-团队合作teamwork)
      - [3.3.2 关系建设(Relationship building)](#332-关系建设relationship-building)
      - [3.3.3 解决分歧(Handling disgreement)](#333-解决分歧handling-disgreement)
  - [4、领导力](#4领导力)
    - [4.1 推进对齐(Driving alignment)](#41-推进对齐driving-alignment)
      - [4.1.1 推进对齐](#411-推进对齐)
    - [4.2 流程思考](#42-流程思考)
      - [4.2.1 流程思考](#421-流程思考)
    - [4.3 协调促进(Facilitation)](#43-协调促进facilitation)
      - [4.3.1 协调促进](#431-协调促进)
    - [4.4 教导(Mentoring)](#44-教导mentoring)
      - [4.4.1 教导](#441-教导)
  - [5、战略性影响](#5战略性影响)
    - [5.1 业务敏锐和战略](#51-业务敏锐和战略)
      - [5.1.1 业务敏锐](#511-业务敏锐)
      - [5.1.2 战略工作](#512-战略工作)
      - [5.1.3 产品思维](#513-产品思维)

# 一、前言
尽管这些年国内的IT行业发展迅速，但是仍然欠缺一套比较系统性的工程师职级胜任力框架，这就造成国内很多工程师大都偏技术执行(一心只想成为技术大牛)，从而忽视了自己全方位的工程师职业素养和能力的培养。

最近我有幸读到了Circle CI公司分享的[工程胜任力矩阵](https://github.com/spring2go/engineer_completency_model/blob/main/CircleCI%20Engineering%20Competency%20Matrix%20%5Bpublic%20version%5D.xlsx)，我发现这份文档就是一份比较贴合互联网研发型企业的工程师胜任力框架，于是我在它的基础上，重新整理出了一份更适合国内工程师阅读的《工程师职级胜任力框架》，并把它分享在我的[github站点](https://github.com/spring2go/engineer_completency_model)上，希望这份文档对工程师的职业开发和成长有帮助。注，Circle CI是美国一家专注CI/CD持续交付领域的SaaS企业服务公司，公司成立于2011年，今年(2020年)已经融到E轮1亿美金融资。工程胜任力矩阵是Circle CI公司的HR和工程团队联合开发，于2018年在其[技术博客上](https://circleci.com/blog/why-we-re-designed-our-engineering-career-paths-at-circleci/)公开分享出来的。

# 二、目标

工程师职级胜任力框架的主要目标是：

* 作为工程师职业开发和成长路径的对标参考
* 作为管理者评估工程师职级/能力+目标设定的对标参考
* 作为HR开发工作描述(JD)和评估候选人职级/能力的对标参考
* 作为企业文化建设的一种手段
  * 将企业的核心价值观和文化融入职级胜任力框架(codify core value and culture into engineering level & completency matrix)，通过框架来引导工程师的价值认同和文化行为。

# 三、说明

* 职级一共分六级，分别如下：
  * E1 ～ 助理工程师(Associate Engineer)
  * E2 ～ 工程师(Engineer)
  * E3 ～ 高级工程师(Senior Engineer)
  * E4 ～ 资深工程师(Staff Engineer)
  * E5 ～ 高级资深工程师(Senior Staff Engineer)
  * E6 ～ 首席工程师(Principal Engineer)
* 评估的纬度共分**5个关键区(Key area)**，关键区再细分为**15个价值(Value)维度**，价值维度再细分为**27个胜任力(Competency)纬度**。其中5个关键区分别是：

  * 技术技能(Technical skills)
  * 交付(Delivery)
  * 反馈、沟通和协作(Feedback, Communication, Collaboration)
  * 领导力(Leadership)
  * 战略性影响(Strategic Impact)
* 各个工程级别的**最主要差异**在所能hold住的**工作的范围(scope)**，或者说**影响力范围**，其中：
  * E1 ～ E3 属于独立贡献者(individual contributor)，小范围工作，偏任务执行(Execution of Work)
    * E1: 任务范围内
    * E2: 项目范围内
    * E3: 小组/团队内
  * E4 ～ E6 能够善用人力(一般要带团队)和产品等杠杆进行规模化的产出(Utilizing skills to scale and generate leverage)，越高层越偏向战略方向和文化建设。
    * E4: 整个团队范围
    * E5: 几个相关团队范围
    * E6: 整个技术部门甚至公司
* 该框架的目标不是将工程师培养成技术牛人，**技术能力在整个框架中只占五分之一**，而是希望提升工程师的综合素养和能力。

# 四、职级和胜任力评估框架

## 1、技术技能
### 1.1 质量和测试
#### 1.1.1 写代码

| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 写代码时能意识到代码的可测试性和可读性的重要性，能意识到边界情况和错误处理。 |
| E2   | **总是能写出易于测试和易于他人理解的代码，能考虑到各种边界情况并做合理错误处理**。能有效书写代码文档。 |
| E3   | 总是能写出易于测试和易于其他开发者理解的**生产级的代码**，能充分考虑各种边界情况和做充分的错误处理。**知道在必要时写代码注释，同时尽量让代码自注释(self-documenting)**。 |
| E4   | 同E3                                                         |
| E5   | 同E3                                                         |
| E6   | 同E3                                                         |

#### 1.1.2 测试
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 知道测试金字塔。能写单元测试(有时需要高级工程师的协助)。     |
| E2   | **理解**测试金字塔原理，并能根据测试金子塔的原理来编写单元测试，能在高级别工程师指导下编写高层测试(组件、集成、e2e测试等)。**不仅能测试成功路径(happy path)，同时也能充分测试边界和错误情况。** |
| E3   | 理解测试金字塔原理，并根据其原理来编写底层单元测试和中高层测试。能写出**优雅和高质量的**测试用例，全面覆盖成功路径、边界和错误情况。 |
| E4   | 理解团队所使用的测试方法，通过质量指标改进测试。能根据团队所采用的测试框架和测试金字塔原理来改进测试方法。 |
| E5   | 理解**多个团队**所使用的测试方法，并通过质量指标来改进测试。和这些团队协作，根据所采用的测试框架和测试金字塔原理来改进测试方法。**能对组织的测试战略产生影响**。 |
| E6   | 理解**公司级**的测试方法，并通过质量指标来改进测试。和**所有团队**合作，根据所采用的测试框架和测试金子塔原理来改进测试方法。**推进**公司级的测试战略。 |

#### 1.1.3 调试
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 理解调试基础，知道如何使用调试工具。                         |
| E2   | 能够使用**系统性方法**定位和调试单个服务的问题。             |
| E3   | 能够**熟练使用系统性方法**定位和调试单个服务中的所有问题。能够使用系统性方法定位和调试**跨服务问题**(有时需要更高级工程师协助)。 |
| E4   | **在所负责的领域内**，能熟练使用系统方法定位和调试所有问题。 |
| E5   | **在所负责的几个领域内**，能熟练使用系统方法定位和调试所有问题。 |
| E6   | 根据需要领导**跨部门的**事件应急响应流程。使用系统性方法定位和调试**跨部门边界**的问题。 |

#### 1.1.4 可观测性(Observability)
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | N/A(该级别暂无要求)                                          |
| E2   | 知道部门的监控理念，并熟悉自己团队领域内的主要运维监控指标。 |
| E3   | 知道部门的监控理念。**能帮助团队改进监控**。能根据团队领域内的运维监控数据，**对系统的稳定性和性能改进提出合理建议**。 |
| E4   | 根据部门的监控理念**推动**所在团队的监控工作。知道所在领域的运维监控数据，能利用这些数据来推动团队**改善**服务的稳定性和性能。 |
| E5   | 在多个团队间推动**可观测的DevOps文化**，帮助工程师利用运维数据来提升各自领域服务的稳定性和性能。 |
| E6   | 在**多个部门间**推进可观测的DevOps文化，帮助公司内**不同部门的**工程团队利用运维数据来提升各自领域服务的稳定性和性能。 |


### 1.2 软件设计和架构
#### 1.2.1 理解领域(domain)
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 在高级工程师的帮助下，对领域上下文有初步理解。               |
| E2   | 对团队内的**某部分领域**有较深入理解，能在该领域内高产出地工作。 |
| E3   | 对团队内的**某个子领域**有专业级掌握，能够进行一定的**抽象建模**，能利用领域抽象能力高产出地工作 |
| E4   | 对**团队负责的整个领域**有专家级的掌握，包括领域内的服务，它们之间的交互，系统间的数据流等。**对周边领域也要有一定理解，因为它们会影响团队的领域**。 |
| E5   | 对**若干个相关领域**有专家级掌握，包括领域内的服务，它们之间的交互，系统间的数据流等。 |
| E6   | 对**组织的整体架构**有专家级的掌握，**包括所有的领域，领域之间的边界，以及它们之间如何交互**。 |

#### 1.2.2 软件架构
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 对服务化架构有总体认识，在此基础上能够设计基本的服务/模块，同时尽量避免冗余代码/功能，减少对接口的不兼容变更。 |
| E2   | 设计的服务要和总体服务化架构**对齐**(align with)。           |
| E3   | 设计的服务/系统和总体架构**始终对齐**。高校地利用**抽象、模块化和重用机制**。 |
| E4   | **使用行业沉淀下来的成熟的设计模式来架构服务和系统，让团队可以增量和自治的开发，并考虑未来的扩展性。考虑未来的可能用例场景，在做设计决策时，以最小化未来变更成本为主要目标**(架构要灵活适应未来的变化)。 |
| E5   | 在**多个团队之间**宣导能支持增量和自治开发的，并且能支持未来扩展的**架构文化**。指导**多个团队**考虑未来的可能用例场景，在做设计决策时，以最小化未来的变更成本为主要目标。 |
| E6   | 在**整个组织内**宣导能支持增量和自治开发的，并且能支持未来扩展的架构文化。指导**组织内的所有团队**考虑未来的可能用例场景，在做设计决策时，以最小化未来的变更成本为目标。 |

#### 1.2.3 安全
| 职级 | 胜任力                                                       |
| ---- | ------------------------------------------------------------ |
| E1   | 理解安全的重要性。                                           |
| E2   | 理解安全的重要性。在做对安全可能有影响的决策时，咨询更高级工程师的意见。 |
| E3   | **所有工程工作**都要经过“安全放大镜”的检视。在做code review和peer review时，主动留意安全漏洞。 |
| E4   | 积极和安全团队，还有自己的团队进行合作，根据组织的安全战略改进团队的安全方法。在团队中鼓励**安全优先(security first)**的理念，并通过榜样力量领导他人(leading by example)。 |
| E5   | 积极和安全团队，还有其他**多个团队**进行合作，保障组织安全战略的落地。在**多个团队间**鼓励安全优先(security first)的理念，并通过榜样力量领导他人。 |
| E6   | 积极和安全团队进行合作来**制定和完善组织级别的安全战略**。在**多部门间**宣导安全优先的理念。**能够识别不易被他人察觉的安全威胁**。 |

## 2、交付
### 2.1 增量价值交付
#### 2.1.1 任务分解
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 理解合理地将工作分解为大小适当的任务对持续集成和增量交付的重要性。 |
| E2   | 在开始工作之前，**确保**任务已经被分解到适合持续集成和增量交付的大小(通常需要团队成员和管理者的帮助)。 |
| E3   | 带着批判性眼光评审**任务**分解，确保任务已经被分解到适合持续集成和增量交付的大小。 |
| E4   | 带着批判性眼光评审**项目**分解，确保项目已经被分解到适当大小并进行了优先化，并且团队成员充分理解这种分解和优先级。 |
| E5   | 带着批判性眼光评审**跨团队的工作**分解，确保工作已经被分解到适当大小并进行了优先化。并且所有涉及的团队都理解这种分解和优先级。 |
| E6   | 带着批判性眼光评审**组织级的工作**分解，确保工作已经被适当分解并且在**多部门间**进行了优先化。 |

#### 2.1.2 优先级和依赖分析
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 按照优先级执行任务。                                         |
| E2   | 理解并按照优先级执行任务。关注和说明**任务依赖**。           |
| E3   | **确保**任务的优先级设定合理，并且能说明依赖关系。           |
| E4   | 确保任务级别的依赖关系已经被说明，并且团队也理解这些依赖关系。在团队中宣导**优先级文化**：先集中力量解决优先级高的任务 + 优先级的设定要和组织战略对齐。 |
| E5   | 确保**跨团队的**项目依赖关系已经被说明，并且**所有涉及的团队和干系人(stakeholders)**都充分理解这些依赖关系。在**多个团队间**宣导优先级文化：先集中力量解决优先级高的任务/项目 + 优先级的设定要和组织战略对齐。 |
| E6   | 识别组织**多部门间的**项目依赖关系，并且和相关团队合作，在这些依赖变成实际问题之前先想办法解决它们，并设计出预防性措施以防止依赖问题的重复出现。在**多个部门间**宣导优先级文化：先集中力量解决优先级高的项目 + 优先级的设定要和组织战略对齐。 |

#### 2.1.3 应对不确定性(Dealing with ambiguity)
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | N/A(该级别暂无要求)                                          |
| E2   | 在个人工作范围内，**通常**能够有效处理风险、变更和不确定性。在日常业务处理(甚至在高压情况)中，即使没有明确的下一步指示，也能自动自发地决策和行动。 |
| E3   | 在个人工作范围内，能够有效处理风险、变更和不确定性。在日常业务处理(甚至在高压情况)中，即使没有明确的下一步指示，也能自动自发地决策和行动。 |
| E4   | **在团队范围内**，能够有效处理风险、变更和不确定性。**在团队范围内**，在日常业务处理(甚至在高压情况)中，即使没有明确的下一步指示，也能自动自发地决策和行动。 |
| E5   | **在多个团队范围内**，能够有效处理风险、变更和不确定性。**在多个团队范围内**，在日常业务处理(甚至在高压情况)中，即使没有全景(total picture)，也能自动自发地决策和行动。 |
| E6   | **在多个部门范围内**，能够有效处理风险、变更和不确定性。**在多个部门范围内**，在日常业务处理(甚至在高压情况)中，即使没有全景，也能自动自发地决策和行动。 |

### 2.2 自我组织(self-organization)
#### 2.2.1 可信赖和责任感
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 能够每天和团队交流工作进度。能够履行已经承诺的交付，并且具有一定的交付紧迫感。 |
| E2   | 承诺和自身工作能力匹配的工作量(不夸大也不低估)，和团队保持沟通，以确保他们理解你的工作的优先级和紧迫性，并按照承诺履行交付。如果有任何阻碍(blockers)、延迟和成本激增问题，则**每天要及时**将这些问题升级反馈到团队。和团队**澄清各自对工作的预期是什么**(避免last minute surprise)。 |
| E3   | 确保**理性和现实的**承诺，确保团队理解你的工作的优先级和紧迫性，并按照承诺履行交付。在需要升级阻碍、延迟和成本激增等问题之前，**提前预期**并沟通这些潜在的问题(防患于未然)。确保在团队中，**所有相关人员**对各自的工作的预期都是清楚的。 |
| E4   | 在**所在团队的项目**中，在需要升级阻碍、延迟和成本激增等问题之前，提前预期并沟通这些潜在的问题(防患于未然)。确保在**所在团队和外部干系人**中，所有相关人员对各自的工作的预期都是清楚的。 |
| E5   | 能够成功管理**多个团队**的交付承诺，交付路线图和进度汇报。在**多个团队**的项目中，在需要升级阻碍、延迟和成本激增等问题之前，提前预期并沟通这些潜在的问题(防患于未然)。确保在**多个团队和外部干系人**中，所有相关人员对各自的预期都是清楚的。 |
| E6   | 能够成功管理**整个组织级**的交付承诺，交付路线图和进度汇报。确保在**多个部门和外部干系人**中，所有相关人员对各自的预期都是清楚的。 |

#### 2.2.2 经济思维
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 理解在决策中的成本 vs 价值权衡的重要性。在工作中如果碰到需要这种决策的场景时，能够向更高级的工程师求助。 |
| E2   | 在采取具体行动方案时，能够做**成本 vs 价值分析**，并采用最经济的行动方案，必要时向更高级的工程师咨询。**有时**，在对团队成员提供建议时，可以采用这种经济思维。 |
| E3   | 在采取具体行动方案时，能够做成本 vs 价值分析，并采用最经济的行动方案，必要时咨询更高级的工程师。在自己的工作中，和对团队提供建议时，**经常使用**这种经济思维。 |
| E4   | 在采取具体行动方案时，能够做成本 vs 价值分析，并采用最经济的行动方案。在自己的工作中经常使用这种经济思维。在**所在团队中**宣导这种**经济思维文化**(economic thinking culture)，确保作出及时且经济的决策。 |
| E5   | 在采取具体行动方案时，能够做成本 vs 价值分析，并采用最经济的行动方案。在自己的工作中经常使用这种经济思维。在**多个团队中**宣导经济思维文化，确保作出及时且经济的决策。 |
| E6   | 在采取具体行动方案时，能够做成本 vs 价值分析，并采用最经济的行动方案。在自己的工作中经常使用这种经济思维。在**整个组织中**宣导经济思维文化，确保作出及时且经济的决策。 |

## 3、反馈、沟通和协作
### 3.1 反馈
#### 3.1.1 提供反馈
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 知道如何有效地赞扬他人，如何提出建设性反馈。                 |
| E2   | 能够对**团队组员和管理者**表达赞扬和提出建设性反馈。         |
| E3   | 能够对团队组员和管理者表达赞扬和提出建设性反馈。**能够在时机恰当时，对团队的业务干系人提供反馈**。 |
| E4   | 在**团队和团队的业务干系人**中，鼓励赞扬和提出建设性反馈的文化。自己以身作则展示这种行为。 |
| E5   | 在**多个团队**和团队的业务干系人中，鼓励赞扬和提出建设性反馈的文化。身体力行展示这种行为。 |
| E6   | 在**整个组织**中，鼓励赞扬和提出建设性反馈的文化。自己以身作则展示这种行为。 |

#### 3.1.2 寻求和接收反馈
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 积极主动向团队组员和管理者寻求反馈，并能利用接收到反馈作为个人成长的重要途径。 |
| E2   | 同E1                                                         |
| E3   | 同E1                                                         |
| E4   | 在团队和相关的业务干系人中**鼓励主动寻求反馈的文化**，并以反馈作为成长的重要途径。身体力行展示这种行为。 |
| E5   | 在**多个团队**和相关的业务干系人中鼓励主动寻求反馈的文化，并以反馈作为成长的重要途径。身体力行展示这种行为。 |
| E6   | 在**整个组织**中鼓励主动寻求反馈的文化，并以反馈作为成长的重要途径。身体力行展示这种行为。 |

### 3.2 沟通
#### 3.2.1 有效沟通(Effective communication)
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 能够面向听众(in an audience-oriented way，以听众为中心而不是自顾自表达)，有效、清晰和简洁地沟通(包括书面和口头形式)。积极聆听对方的反馈，确保你真正理解对方的关切。关注肢体语言。 |
| E2   | 在和团队成员沟通时，不管是**技术还是非技术主题**，**通常**都能够面向听众，有效、清晰和简洁地沟通(包括书面和口头形式)。积极聆听对方的反馈，确保你真正理解对方的关切。关注肢体语言。 |
| E3   | 在和团队成员沟通时，不管是技术还是非技术主题，**始终**都能够面向听众，有效、清晰和简洁地沟通(包括书面和口头形式)。积极聆听对方的反馈，确保你真正理解对方的关切。关注肢体语言。 |
| E4   | 能够在**具有多样背景和性格的团队**中有效沟通。在团队中，鼓励清晰、简洁、有效和面向听众的**沟通文化**。确保团队成员能够积极聆听对方的反馈，真正理解对方的关切。身体力行展示这种行为。关注肢体语言。 |
| E5   | 能够在具有多样背景和性格的**多个团队间**有效沟通。在**多个团队间**，鼓励清晰、简洁、有效和面向听众的沟通文化。确保团队成员能够积极聆听对方的反馈，真正理解对方的关切。身体力行展示这种行为。关注肢体语言。 |
| E6   | 能够在**整个公司**中有效沟通。在**整个公司**中，鼓励清晰、简洁、有效和面向听众的沟通文化。确保团队成员能够积极聆听对方的反馈，真正理解对方的关切。身体力行展示这种行为。关注肢体语言。 |

#### 3.2.2 知识分享
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 理解自己的职责范围内的工作，经常和团队成员分享知识。         |
| E2   | 理解自己的工作**领域**，经常和团队成员分享知识，并**积极充实团队文档库**。留意可以分享知识的机会。 |
| E3   | 理解**所在团队**的工作领域，经常和团队成员分享知识，并积极充实团队文档库。留意可以分享知识的机会，**鼓励其他人也积极分享知识**。 |
| E4   | 在**所在团队和相关业务干系人**中，鼓励分享和积极书写文档的**分享文化**。身体力行展示这种行为。 |
| E5   | 在**多个团队**和各自的相关业务干系人中，鼓励分享和积极书写文档的分享文化。身体力行展示这种行为。 |
| E6   | 在**整个组织**中，鼓励分享和积极书写文档的分享文化。身体力行展示这种行为。 |

### 3.3 协作
#### 3.3.1 团队合作(Teamwork)
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 在组员请求帮忙的情况下，给予力所能及的帮助。为自己积累乐于助人的信誉，在得到别人的帮助时，也要记得别人的信誉。 |
| E2   | 在组员请求的情况下，帮助组员**一起克服阻碍完成工作**。为自己积累乐于助人的信誉，在得到别人帮助时，也要记得别人的信誉。 |
| E3   | **有时**能主动帮助组员一起克服阻碍完成工作。为自己积累乐于助人的信誉，在得到别人帮助时，也要记得别人的信誉。 |
| E4   | **总是**能主动帮助组员一起克服阻碍完成工作。为自己积累乐于助人的信誉，在得到别人帮助时，也要记得别人的信誉。 |
| E5   | 在**多个团队**范围内，总是能主动帮助组员一起克服阻碍完成工作。为自己积累乐于助人的信誉，在得到别人帮助时，也要记得别人的信誉。 |
| E6   | 在**整个组织**范围内，赋能团队互帮互助，人人乐于积累和给予信誉。 |

#### 3.3.2 关系建设(Relationship building)
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 在工作中和团队成员、管理者建立密切关系。                     |
| E2   | 在工作中和团队成员、管理者，以及对口的**产品团队**建立密切关系。 |
| E3   | 在工作中和团队成员，管理者，以及**相关业务的干系人**建立密切关系。 |
| E4   | 在工作中和团队成员，管理者，团队相关的业务干系人，以及**组织内的高级别工程师**之间建立密切关系，并不断提升这种关系。**在做团队定位和计划的时候，充分利用这些建立的关系**。 |
| E5   | 在**多个团队范围内**，和工程师、管理者，还有相关业务干系人建立密切的关系。在为**这些团队**做定位和计划时，充分利用这些建立的关系。 |
| E6   | 和**整个组织范围内**的成员建立密切的关系。在为**整个组织**做定位和计划时，充分利用这些建立的关系。 |

#### 3.3.3 解决分歧(Handling disgreement)
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能以积极健康的方式解决分歧。能够根据他人的观点输入来调整和改变自己的视角和计划。 |
| E2   | 讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能够开诚布公(而非保守固执)，在有分歧观点的基础上，进行**建设性**的和**富有成效**的对话，**通过深入理解对方关切来解决分歧**。**能够根据他人的观点输入来调整和改变自己的视角和计划**。 |
| E3   | 鼓励**团队成员**在讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能够开诚布公(而非保守固执)，在有分歧观点的基础上，进行建设性的和富有成效的对话，通过深入理解对方立场来解决分歧。能够根据他人的观点输入来调整和改变自己的视角和计划。 |
| E4   | **在团队内鼓励开诚布公和就事论事文化**，鼓励团队成员在讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能够开诚布公(而非保守固执)，在有分歧观点的基础上，进行建设性的和富有成效的对话，通过深入理解对方立场来解决分歧。能够根据他人的观点输入来调整和改变自己的视角和计划。 |
| E5   | 在**多个团队范围**内，鼓励开诚布公和就事论事文化，鼓励团队成员在讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能够开诚布公(而非保守固执)，在有分歧观点的基础上，进行建设性的和富有成效的对话，通过深入理解对方立场来解决分歧。能够根据他人的观点输入来调整和改变自己的视角和计划。**深入挖掘表层分歧的背后关切，并将这些关切融入各自的视角和计划中**。 |
| E6   | 在**整个组织范围**内，鼓励开诚布公和就事论事文化，鼓励团队成员在讨论时，能积极参与讨论，公开表达自己的观点，同时尊重他人的意见。当发生意见分歧时，能够开诚布公(而非保守固执)，在有分歧观点的基础上，进行建设性的和富有成效的对话，通过深入理解对方立场来解决分歧。能够根据他人的观点输入来调整和改变自己的视角和计划。**将整个组织的背后关切融入各自的视角和计划中**。 |

## 4、领导力
### 4.1 推进对齐(Driving alignment)
#### 4.1.1 推进对齐
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 在初步了解组织战略和原则的基础上，在时机恰当时能积极参与相关内容的小组讨论。在初步理解组织目标的基础上，全力投入实现小组目标(目标导向)。 |
| E2   | 在了解组织战略和原则的基础上，在时机恰当时**能发起**一下相关内容的小组讨论。在初步理解组织目标的基础上，全力投入实现团队目标。 |
| E3   | 在理解组织战略和原则的基础上，在时机恰当时能发起一下相关内容的团队讨论，**确保团队目标和组织目标对齐**。在理解组织目标的基础上，**确保团队全力投入实现共同目标**。 |
| E4   | 在**团队中**鼓励**目标对齐文化**，在理解组织战略和原则的基础上，按需发起一下相关内容的团队讨论，确保团队目标和组织目标的对齐。在理解组织目标的基础上，确保团队全力投入实现团队目标。 |
| E5   | 在**多个团队**中鼓励目标对齐文化，在理解组织战略和原则的基础上，按需发起一下相关内容的**多团队**讨论，确保团队目标和组织目标的对齐。在深入理解组织目标的基础上，确保多个团队全力投入实现各自的团队目标。 |
| E6   | 在**整个组织内**推动目标对齐文化，在深入理解组织战略和原则的基础上，按需发起战略和目标讨论，确保团队目标和组织目标的对齐。确保在**整个组织范围内**，大家既理解整个组织的大目标，也清楚各自的团队目标。 |

### 4.2 流程思考
#### 4.2.1 流程思考
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 理解团队所采的实践和流程。                                   |
| E2   | **有时**能思考团队所采用的实践和流程，**并能和团队讨论改进办法**。 |
| E3   | **经常**能思考团队所采用的实践和流程，并能和团队讨论改进办法。 |
| E4   | 经常能思考团队所采用的实践和流程，并能和团队讨论改进办法。**有时**能和其他团队合作来改进**组织的**实践和流程。 |
| E5   | 经常对**多个团队**会产生影响的实践和流程进行思考，和相关团队讨论改进办法，并推进落地。**经常**能和其他团队合作来改进组织的实践和流程。 |
| E6   | **对组织的实践和流程的持续改进总负责**。                     |

### 4.3 协调促进(Facilitation)
#### 4.3.1 协调促进
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | N/A(该级别暂无要求)                                          |
| E2   | N/A(该级别暂无要求)                                          |
| E3   | 在团队中协调促进讨论，确保每个人都有机会分享观点和被倾听，并且讨论的结果和会议目标议题紧密关联。鼓励那些不太愿意说话的参与者，同时防止某人全程垄断讨论。 |
| E4   | 同E3                                                         |
| E5   | 在**多个团队间**协调促进讨论，确保每个人都有机会分享观点和被倾听，并且讨论的结果和会议目标议题紧密关联。**确保相关团队都参加讨论**。协调讨论向**有结果产出的方向**推进，协助澄清观点，对于最终讨论结果，确保大家的**认同**(buy-in)。 |
| E6   | 在**整个组织间**协调促进讨论，确保每个人都有机会分享观点和被倾听，并且讨论的结果和会议目标议题紧密关联。确保相关团队都参加讨论。协调讨论向有结果产出的方向推进，协助澄清观点，对于最终讨论结果，确保大家的认同(buy-in)。 |

### 4.4 教导(Mentoring)
#### 4.4.1 教导
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 主动寻找能帮助自己提升工作经验的导师。                       |
| E2   | 主动寻找能帮助自己提升工作经验的导师。**有时**也能以开放灵活、相互尊重和富有同理心的方式去教导其他初级组员。 |
| E3   | 能够以开放灵活、相互尊重和富有同理心的方式去教导其他初级组员。**从保持团队技能适度冗余和关键岗位要有候补的角度考虑，主动寻找教导机会**。 |
| E4   | 能够以开放灵活、相互尊重和富有同理心的方式去教导其他组员。从保持团队技能适度冗余和关键岗位要有候补的角度考虑，主动寻找教导机会。**必要时能够对其他团队的组员进行教导**。 |
| E5   | 在**多个团队间**，能够以开放灵活、相互尊重和富有同理心的方式去教导其他成员。在多个团队间鼓励**教导文化**，主动为自己和他人寻找教导机会，同时作为导师帮助他人成长。 |
| E6   | 在**整个组织**中，能够以开放灵活、相互尊重和富有同理心的方式去教导其他成员。鼓励**组织级的教导文化**，主动为自己和他人寻找教导机会，同时作为导师帮助他人成长。 |

## 5、战略性影响

### 5.1 业务敏锐和战略
#### 5.1.1 业务敏锐
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 基本理解团队的领域和整个公司的主营业务。                     |
| E2   | 基本理解团队的领域，**并且理解团队在整体业务战略中的定位和作用**。 |
| E3   | **深入**理解团队的领域，并且理解团队在整体业务战略中的定位和作用。对**周边团队的业务领域**有基本的理解。 |
| E4   | 深入理解团队的领域和**战略**，以及如何将其映射到**公司的总体战略框架**。**充分理解**周边团队的战略，**理解自己团队在其他团队战略中的定位/作用和接口点**。 |
| E5   | 深入理解**多个团队**的领域，理解这些团队在公司整体业务战略中的定位和作用。 |
| E6   | 深入理解**整个公司的业务，包括每一个领域**，理解它们是如何拼装成公司的整体战略版图的。 |

#### 5.1.2 战略工作
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | N/A(该级别不适用)                                            |
| E2   | 理解公司的工程战略。                                         |
| E3   | 理解公司的工程战略，**经常能参与讨论该战略给团队带来的机会和影响**。 |
| E4   | 根据公司的工程战略，**和团队成员+高级工程师协作**，讨论并决定本团队的工作重点。**有时**能参与公司的工程战略制定。 |
| E5   | **经常**参与战略性的组织决策和计划。领导**跨团队**战略工作制定，对决策施加影响以确保**多团队**和公司总体战略目标的对齐。 |
| E6   | **领导**战略性的**组织**决策和计划。**经常在战略层次思考和工作**，对决策施加影响以确保组织级的战略目标对齐。 |

#### 5.1.3 产品思维
| 职级 | 胜任力                                                       |
| ---- | :----------------------------------------------------------- |
| E1   | 理解团队所产出产品的基本功能。                               |
| E2   | 理解团队所专注的**产品区**，理解它们在总体业务中的**定位和作用**，有时能提出产品**改进建议**。 |
| E3   | **充分理解**公司的业务模式和当前团队所专注产品区的关系。**有时**能参与产品团队的路线图制定，并提出反馈意见。**寻找机会简化产品和技术设计**。 |
| E4   | 和产品团队一起协作评估和开发新产品功能。**经常参与**产品路线图的制定。**通过主动对话**简化产品和技术设计。 |
| E5   | **能够识别新产品机会，以及和竞争对手产品之间的差异点**。在**多个团队间**，经常能根据技术战略和限制来协助细化产品路线图。有时能改变技术战略或限制来定义和**创造新产品**。 |
| E6   | 在**整个组织范围内**，和产品/业务方通力协作，**积极寻找**能够创造新产品或重新定义产品路线图的任何机会。 |