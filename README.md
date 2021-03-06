# Analyse_of_Complex_System
学习“分析信息系统”课程的项目。这门课程需要掌握模型化企业架构和工作流程。基于medelio软件完成UML图的绘制。<br>
我采访的是一家德国超市企业在法国特鲁瓦的分公司。采访持续半个小时，问题从企业背景，到企业各部门工作流程，到个人任务细节，充分了解了企业的架构和工作流程。完成了五类UML图的绘制。鉴于不同企业部门分工和流程差异较大，所以上传了架构模型，不涉及企业信息。
## 组织流程
此图绘制角色和角色分工以及相互间关系。可以迅速表达一个企业的组织结构，并将各个岗位工作任务清晰分配，以了解各个角色的工作以便分析，或用于提高企业效率。<br>
![](https://github.com/JoJoDU/Analyse_of_Complex_System/raw/master/image/组织流程.png)
## 组织重要部门
共从五类群体进行分析：<br>A.战略最高决策层（战略决策、管理和协调组织内各项活动和工作）<br>B.中间层(组织的实际运营)<br>C.操作骨干(基础工作的骨干力量)<br>D.技术层(设计和规划组织的各营运体系，控制着组织内的技术工作)<br>E.后勤人员(提供必要服务)<br>
![](https://github.com/JoJoDU/Analyse_of_Complex_System/raw/master/image/组织重要部门.png)
## 组织客户
具体分析企业的客户构成，分析其继承关系，用类图展示。例如企业客户和个人客户均继承于客户，但是在共同特征中又有着不同的特点。
## 组织商品
具体分析企业商品类别，用类图展示，对象与类之间的五种关系需要区分。<br>
* 依赖（Dependency）：元素A的变化会影响元素B，但反之不成立，那么B和A的关系是依赖关系，B依赖A；类属关系和实现关系在语义上讲也是依赖关系，但由于其有更特殊的用途，所以被单独描述。uml中用带箭头的虚线表示Dependency关系，箭头指向被依赖元素。<br>
* 泛化（Generalization）：通常所说的继承（特殊个体 is kind of 一般个体）关系，不必多解释了。uml中用带空心箭头的实线线表示Generalization关系，箭头指向一般个体。<br>
* 实现（Realize）：元素A定义一个约定，元素B实现这个约定，则B和A的关系是Realize，B realize A。这个关系最常用于接口。uml中用空心箭头和虚线表示Realize关系，箭头指向定义约定的元素。<br>
* 关联（Association）：元素间的结构化关系，是一种弱关系，被关联的元素间通常可以被独立的考虑。uml中用实线表示Association关系，箭头指向被依赖元素。<br>
* 聚合（Aggregation）：关联关系的一种特例，表示部分和整体（整体 has a 部分）的关系。uml中用带空心菱形头的实线表示Aggregation关系，菱形头指向整体。<br>
* 组合（Composition）：组合是聚合关系的变种，表示元素间更强的组合关系。如果是组合关系，如果整体被破坏则个体一定会被破坏，而聚合的个体则可能是被多个整体所共享的，不一定会随着某个整体的破坏而被破坏。uml中用带实心菱形头的实线表示Composition关系，菱形头指向整体。<br>
## 个人任务
此流程图用于细致描绘个人任务的由始至终，将任务细化为每一个步骤，可以详细解释一项工作的完成步骤及多项工作的协调完成过程。

![](https://github.com/JoJoDU/Analyse_of_Complex_System/raw/master/image/个人任务.png)
