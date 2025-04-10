1. 交互（interaction） = 动作（Action）+ 反应（Reaction）

2. Interactivity (交互属性) : Action（动作）
    Presence（存在性）
        类型：Explicit（显性） / Implicit（隐性）
        定义：
        Whether the system advertises the availability of an action to the user.
        系统是否向用户明确呈现某个操作的存在与可能性。
        示例：
        A button with a tooltip saying "Click to save" is explicit; hidden keyboard shortcut is implicit.
        显示“保存”的按钮是显性提示；隐藏的快捷键操作则是隐性的
    Agency（动作表达方式）
        类型：Verbal（语言型） / Manual（手动型）
        定义：
        The metaphorical way a user performs an action—either by "speaking" (typing) or "acting" (manipulating).
        用户通过比喻方式表达动作，是“说出来”（键盘命令），还是“动手做”（拖拽、点击）。
        示例：
        In Tower of Hanoi, dragging a disk = Manual; typing move(1,3) = Verbal.
        拖拽圆盘是手动型；输入命令是语言型。
    Granularity（粒度）
        类型：Atomic（原子级） / Composite（复合型）
        定义：
        Whether an action is made of one step or several.
        用户操作是一步完成，还是由多个子步骤组成。
        示例：
        Angry Birds launching gesture is atomic; swapping gems in Bejeweled is composite (choose → swap → wait).
        愤怒的小鸟发射动作为原子级；宝石消除游戏需要连续点击、交换，是复合型。
    Focus（关注）
        类型：Direct（直接） / Indirect（间接）
        定义：
        Whether the user acts on the representation of interest directly, or via another element.
        用户是否直接作用于目标表示，还是通过中介（如按钮）间接操作目标。
        示例：
        Dragging an object = Direct; clicking “Move” after adjusting arrow = Indirect.
        拖动物体是直接；先调整方向再点“移动”是间接。
    Flow（流动性）
        类型：Discrete（离散） / Continuous（连续）
        定义：
        Whether the action happens instantly or over time.
        操作是瞬时发生，还是在时间上持续进行。
        示例：
        Clicking a checkbox = Discrete; dragging a slider = Continuous.
        点击选择框是离散；拖动滑块是连续。
    Timing（时间性）
        类型：User-paced（用户节奏） / System-paced（系统节奏）
        定义：
        Whether the user controls when to act or must act within a system-imposed time limit.
        用户是否能自由决定操作时间，或是受到系统节奏约束。
        示例：
        Tower of Hanoi with no timer = User-paced; timed quiz = System-paced.
        没有时间限制的河内塔是用户节奏；限时答题是系统节奏。

3. Interactivity (交互属性) : Reaction（反应/反馈）
    Activation（激活）
        类型：Immediate（立即） / Delayed（延迟） / On-demand（按需）
        定义：
        Determines when the system reacts after a user action is committed.
        决定用户操作后系统反应发生的时间。
        示例：
        Clicking a shape and it appears instantly = Immediate; reaction after a pause = Delayed; clicking “Run” after entering code = On-demand.
        点击图形立即出现在右侧是立即反应；动作后延迟变化是延迟；写完指令后点击“运行”再变化是按需激活。
    Transition（过渡方式）
        类型：Stacked（叠加） / Distributed（分布）
        定义：
        How system presents changes in state visually—sequentially or simultaneously.
        系统如何在视觉上呈现状态变化，是顺序堆叠还是并列展示。
        示例：
        A progress bar that shows only current step = Stacked; timeline showing multiple stages = Distributed.
        只能看到当前状态的进度条是堆叠式；显示多个时间点的图是分布式。
    Spread（影响范围）
        类型：Self-contained（自包含） / Propagated（传播型）
        定义：
        Whether a user action affects only the target representation or causes effects on other elements.
        动作是否仅影响本体，还是会影响界面上其他元素。
        示例：
        Swapping gems with no match = Self-contained; matching triggers chain reaction = Propagated.
        交换宝石无反应是自包含；触发消除并引发连锁反应是传播型。
    State（状态变化）
        类型：Created（新增） / Altered（更改） / Deleted（删除）
        定义：
        What changes happen to the representations after a reaction.
        系统在反应后对表示进行的具体变更类型。
        示例：
        A new shape appears = Created; a score is updated = Altered; an item is removed = Deleted.
        添加图形是新增；修改数值是更改；清除物体是删除。
    Context（上下文变化）
        类型：Changed（改变） / Unchanged（不变）
        定义：
        Whether the overall environment or setting around representations changes after an interaction.
        执行动作后，表示所处的语境是否发生改变。
        示例：
        Moving to a new level in a game = Context Changed; staying in same layout = Context Unchanged.
        关卡切换、场景变换是语境改变；界面内容变但布局不变是语境未变。

4. Macro-Level Interactivity 宏观交互维度卡片
    Diversity（多样性）
        定义：
        Refers to the variety of interactions available to the user to support different cognitive tasks.
        指系统提供给用户的交互方式数量与类型是否多样，是否支持多种认知任务。
        示例：
        A data tool that lets users zoom, filter, search, annotate, and link graphs demonstrates high diversity.
        一个数据工具提供缩放、筛选、搜索、标注、关联图表等功能，说明其交互多样性高。
    Complementarity（互补性）
        定义：
        How well individual interactions coordinate and support each other to enable complex tasks.
        个别交互之间是否能协同配合、相互补充，共同支持复杂任务的完成。
        示例：
        In a learning tool, using one interaction to explore a concept and another to test understanding = complementary design.
        在学习软件中，一个交互用于探索概念，另一个用于测试理解，体现交互互补。
    Flexibility（灵活性）
        定义：
        Refers to the user’s ability to adjust and personalize interface elements to suit their needs.
        用户是否能够根据自己的需要调整界面特征，包括颜色、大小、速度、视角等。
        示例：
        A tool allowing users to change font size, color theme, chart type, or speed of animation = high flexibility.
        允许用户更改字体大小、配色方案、图表类型、动画速度的工具，具有高度灵活性。
    Genre（交互类型）
        类型：Access（访问型） / Annotation（注释型） / Construction（构建型） / Combination（组合型）
        定义：
        Classifies the overall nature of interaction the system offers.
        定义系统提供的整体交互方式的类型。
        示例：
        Access: Viewing news articles
        访问型：浏览新闻文章
        Annotation: Adding notes to charts
        注释型：在图表上添加注释
        Construction: Building a simulation model
        构建型：建立仿真模型
        Combination: Using all of the above
        组合型：包含多种操作，如编辑、构建与标注

5. 设计启示与重点
High quality interactivity = better usability and user experience
高质量的交互性 = 更好的可用性与用户体验
Each interaction dimension affects the user's cognitive process, efficiency, mood, and sense of engagement
每个交互维度都会影响用户的认知过程、效率、情绪与参与感