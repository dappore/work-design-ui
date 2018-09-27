# 关于有个想法

基于Rails生态，尽可能提升web应用开发效率及降低开发成本，对于企业管理系统的开发有明显优势。

## 初衷

* 随着互联网+在各个行业的应用，很多企业都在开发自己的系统或是转型互联网。对于这样一批企业而言，内部的IT部门往往是：

  1. IT部门属于支撑部门，IT为业务部门服务，业务部门往往在缺乏专业产品理念及规划，而直接向IT部门提业务需求，IT部门沦为乙方；
  2. IT部门属于成本部门，由于无法直接为企业带来收入，且很难评价IT部门的效益，往往被受重视程度不够。
  3. IT部门整体技术水平往往不高，一方面由于缺乏互联网企业的特质，对程序员的吸引不够，另一方面因为需要的是能把实现需求即可的程序员，对技术水平的需求不迫切。

* 痛点：
  1. 软件项目质量差，由于缺乏优秀架构师在业务上的架构，系统往往在更多的考虑如何满足眼前的需求，而缺乏对系统的可扩展性的考虑；
  2. 用人成本高。项目需求往往是阶段性的，特别是项目初始阶段，很容易缺人。但是项目进入维护阶段后，又很容易人力冗余。
  3. 软件成本高。大部分软件的一些功能是很通用的，比如权限管理，数据处理等，但是每个项目都需要一套这样的代码。

## 怎么做

* 模块化开发
  * 我们将通用的功能进行了抽取，以Rails Engine的形式 附加到主项目即可快速应用某快功能；
  * 基于统一的设计理念，UI体系；
  * [engines系列](_blogs/engines.md)
  * [modular](_blogs/modular.md)

* 优化工具，提升生产力
  * 除了通用的功能及组件，我们也对一些工具进行了优化，比如表单构建工具。
  * [default系列](_blogs/default.md)

* 全栈开发，降低技术栈复杂度
  * 全栈开发，前后端不分离
  * [关于全栈开发](_blogs/full_stack.md)

* 更多见[开发原则](_blogs/rule.md)

## 追求生产力和效率

对于任何企业来讲，效率和生产力是企业发展最原始的动力，对于创业型企业尤为重要。

单就效率来讲，需要写的代码越少，需要协作沟通的环节越少，效率越高。

前后端不分离，rails 绝对可以达到极致。
