# Chapter 9 - Evaluation

> Definition: **<u>Assessment of usability and usefulness</u>** of a system or its components and/or features

## 1. Usability

### 1.1 一些定性

1. ❌ Not a **binary** property
2. ❌ Not a **property of an artifact**
   1. ✅ a **relational property** of the **whole user-artifact** system

### 1.2 Aspects of usability 

1. **Learnability**: 学的多快
2. **Throughput**： perform tasks多快
3. **Flexibility**: users可以在subsystems里做多少事情
4. **Attitude**: Users的态度如何

## 2. User Experience 

### 2.1 一些定性

- a very nebulous term 是个模糊的概念
- ❌ Not **first-order** design
  - ✅ It is **second-orde**r design
  - Combined with the user and the context of use

### 2.2 Aspects of user experience 

1. **Desirability**: user想用吗
2. **Pleasureability**: user高兴吗
3. **Engagement**：System有没有attract user (可以理解为用户的参与度engage度)
4. **Flow**: users perform tasks的专注度(does the system fully immerse users in a task)

## 3. Evaluation Techniques

> Definition: Assess the degree of **<u>usability</u>** & <u>**user experience**</u>

### 3.1 Approach(2个)

1. #### Analytical 快捷不正式

   Perform a **simulation** of how users' tasks will be performed

   **Quick and informal**

2. #### Empirical 正式且麻烦

   Build a **prototype** and **test it with users**

   需要planning, sign up users等等

### 3.2 Answer evaluation questions

- **Rarely straightforward**  to answer
- **Rarely** determined by a **quick calculation** 
- time varies(depending on complexity of system)

### 3.3 Evaluation Strategies(2个)

与上面的两个approach（Analytical和empirical）是独立开的

1. #### Formative

   - **During design and implementation** process
   - Influence development 

2. #### Summative

   - **After Implementation**
   - Assess proper functioning

### 3.4 Aspects of Evaluation

- **What** evaluation is

  1. usefulness
  2. `Usability` & `User experience`

- **How** to evaluate

  Approach: `analytical` &` empirical `

- **Why** Evaluate

  - To improve design
  - To see if systems meets the need

- **When** to evaluate

  - `Fomative`: throughout
  - `Summative`: at the end

### 3.5 Evaluation Methods

一般都是a collection of approaches

have a mix of analytical / empirical and summative / formative

#### Recording techniques

1. Paper & Pencil
2. Audio Recording
3. Video Recording

#### Analytical Methods

- Cognitive walkthrough (user-artifact centered)
  - Task-specific 分析用户对任务的整体理解, 用户是否知道什么东西能操作
- Heuristic evaluation (artifact centered

#### Empirical Methods

- Simple observation
- Think-aloud
- Think-after
- Co-operative Evaluation
- Co-discovery learning

> No perfect method!!!!  

## 4. Heuristic Evaluation 

> This is a form of <u>**analytical evaluation**</u>(快捷不正式)
>
> - Evaluate a system based on a set of principles 
> - 阶段：Design & Evaluation
> - 为谁服务：paper prototypes & working systems

### 4.1 What are heuristics

非硬性规范，一种经验总结。用于指导和评估用户界面设计，确保可用。

English explanation：General usability guidlines used to evaluate and improve user interface design

### 4.2 优缺点

#### Pro

- User involvement not required 不需要用户参与
- small number of heuristics can catch many common design problems 以小见大
- cheap and fast

#### Con

- Real evaluation involves more than a checklist 与现实有差距
- no subtleties of use 无法表达微妙的东西
- Can easily miss what users do and think 遗漏用户想法

> ⚠️ dont be naive about their comprehesive effectiveness 
>
> 不要指望他们有全面的效果

### 4.3 常见Heuristics举例

✨✨✨✨✨✨✨✨✨✨✨十条✨✨✨✨✨✨✨✨✨✨✨

- 
  Simplify **dialogue** 
- Speak the **users’ language**
- Minimize the users’ **memory load**
- Have **consistency**
-  Provide **feedback**
- Provide clearly marked **exits**
- Provide **shortcuts**
-  **Deal with error** in a positive and helpful manner
-  Minimize **user error**
- ◦Provide help and **documentation**

✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨

> Evaluation  heuristics 就是从design conceptes/princinples 衍生而来的

### 4.4 Heuristic Evuation

- 概念：**small set of evaluators** examine the interface **independently** with usability principles (heuristics)

#### 使用过程：小而多

- Individual evaluators 会覆盖不全

  - 一个evaluator只会找到35%的问题

  - 不同的evaluator找到不同的问题

  - Cost-benefit analysis: critical usability 用 more evaluators

- 推荐数量：5 （最少3）
- 时间：通常1-2 hours
- 2遍：Go through interface at least twice
  - Macro: 大概的感受general scope of system
  - Micro: 第二遍focus on specific interface elements
- Findings are shared after all evaluators finished
  - Ensures independent and unbiased evaluations

#### Record evaluations

- 2 ways: witten report from evaluator /  take notes as the evaluator comments on system
- **List usability problems** and **annotate** them withe specific **principles**
- Does not provide:
  - a systematic way to generate fixes
  - probable quality of redesign (假设Redesign会怎样)
- Fix: based on guidelines 

## 5. Empirical Evaluation  （经验）

> 在industry和academia都有使用！

Somebody  doing something in some situation

- Who: humans(individuals/groups)
- What:actions / behaviour/ tasks
- When & where: system/ location

### 5.1 Criteria for good empirical research

- **Generalizability**

  Result对庞大用户群体的可拓展性

- **Precision**

  - Measurement behaviour的准确性
  - 对extraneous情况的考虑

- **Realism**

  - The situation you gathered 有多贴近现实

### 5.2 *Method - Simple observation

Evaluator observes user performing tasks

- Pro: Easy to do

- Con: Does not give insight into user's decision process. 不关注用户做决定的过程

  <img src="/Users/limohan/Library/Application Support/typora-user-images/image-20250410160424701.png" alt="image-20250410160424701" style="zoom:50%;" />

### 5.3 *Method - Think-aloud

> 📌📌📌📌📌The most used evaluation Method📌📌📌📌📌

- 概念： 参与者在think / do的时候需要talk aloud

- ✨ This gives insight into what the user is thinking

- Problems

  - Awkward

  - Thinking aloud may alter the way people perform tasks 影响做任务

  - Hard to talk when concentrating a problem 专注的时候说不了话

- 所以也不是所有情况都适用

### 5.4 *Method - Think-after

> Variation of think-aloud

-  Process
  - Record user session (video)
  - Play recording  back to users
  - User watch recording and think aloud
- ✨👉 User行动的时候录视频，看着视频回放think aloud
  - Overcome think-aloud的无法同时做两件事的问题

### 5.5 *Method - Co-operate Evaluation

Evaluiator and user talk together, 互相提问

- Evaluator提问比如“why did you do that” 
- User提问比如遇到problem需要clarification

好处：

- **Less constrained** than think-aloud
- User can **criticize** the system 
- Evaluator can **clarify confusion**

⚠️ Evaluator可能会过度影响user (overly influence the user)

### 5.6 *Method - Co-discovery learning

Two people work together on a task

> Between two `users`!

It removes awkwardness

## 6. Examples and case studies

### 6.1 Case Study 1

**<u>Task</u>**: Develop concept maps

**Goal**: How does the tool support the development of concept maps

- Explore shapes
- Make sense of relationships among them
- Determine how they are derived from each other 

<img src="/Users/limohan/Library/Application Support/typora-user-images/image-20250410221711505.png" alt="image-20250410221711505" style="zoom:50%;" />

**3 ways to interact** (interfaces )

1. Stacked
2. Distributed
3. Coupled

**Study Design**

1. Mixed methods are combined 
2. Multiple types of data-collection instruments
3. Multi-Method was used to cross validate(交叉验证)
4. Compare 3 groups, each group interacting with one of 3 interfaces

**Participants**

36 undergraduate computer science and engineering students

None of the subjects previously used the tool 没人之前用过

**Procedure**

<img src="/Users/limohan/Library/Application Support/typora-user-images/image-20250410224453456.png" alt="image-20250410224453456" style="zoom:50%;" />

**Data Sources**

1. Achievement Results
2. Video Transcripts
3. Interview Transcripts
4. Direct Observation

**Results**

<img src="/Users/limohan/Library/Application Support/typora-user-images/image-20250410224658997.png" alt="image-20250410224658997" style="zoom:50%;" />

**Conclusion**

1. Transitional processes 不易理解
2. Computer tools可以separate it
3. By placing distributed and stacked interfaces side by side, users可以control each dimension
4. 也为其他的study提供implications

### Case Study 2

和Case study1类似，在ppt里64页

也不在ppt最后的summary里，

应该只是老师举了两个他做过的study 特别具体那种，不是重点。
