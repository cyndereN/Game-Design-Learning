# Game UI
游戏的核心依旧是关乎于设计。而 UI 是很好的工具，去把设计内容展示出来。 游戏设计关注玩家怎么和虚拟世界交互，UI 是用比较通俗简单的方式告诉玩家如何和这个世界进行交互。
## What is UI?

用户界面（ User Interface ）
In the industrial design field of human–computer interaction, a user interface (UI) is the space where interactions between humans and machines occur - images, sounds, texts, etc.
是系统和用户之间进行交互和信息交换的媒介，它实现信息的内部形式与人类可以接受形式之间的转换。

GUI是Graphical User Interface的简称，简单来说，就是游戏中菜单的设计。广义上，GUI还包括游戏的画面、游戏中重叠的字幕、时间、HP等等，也就是说除了游戏玩法本身以外的其他信息也都可以算在里面。
华丽而富有设计感；或者简洁朴素到舍弃一切个性。UI是为了游戏和玩家服务的。

然而概念是“静止”的。游戏开发者在工作生产中所形成的理解，更能体现 UI 对于当下的意义。我大致把大家关于此问题的回答分为两类：广义 UI 和狭义 UI。

这里所说的广义 UI 是指不单把图形界面（ GUI ） 视为 UI。

“ 游戏就是 UI。游戏本身就是一种互动，它是一个交互的过程。”

## Good design is invisible

Only when UI is bad people can notice them
当它无法保证玩家与游戏之间的交流，玩家处理游戏信息的成本过高，这样的 UI 势必令人诟病。无论是玩家无法找到目标界面，或者是信息呈现方式过于繁杂，这些情况都会打破玩家的沉浸感，让玩家的注意力从游戏本身，转移到如何解决 UI 问题上面。
When it cannot guarantee the communication between the player and the game, and the cost for the player to process game information is too high, such a UI is bound to be criticized. 
无论是玩家无法找到目标界面，或者是信息呈现方式过于繁杂，这些情况都会打破玩家的沉浸感，让玩家的注意力从游戏本身，转移到如何解决 UI 问题上面。
Whether the player cannot find the target interface, or the way information is presented is too complicated, these situations will break the player's sense of immersion and divert the player's attention from the game itself to how to solve UI problems.


## Tricks, tips

- 游戏UI配色的选择
    - 沉稳配色
    避免大面积偏亮偏纯的色调。游戏玩家经常需要花费长时间在游戏场景交互，选用较为冷色、暗色系的配色，更能避免玩家产生过度视觉刺激和疲劳。

    - 依据游戏属性选择色调
    虽说很多游戏界面都采用较为科技感的冷色调，但并代表可套用所有游戏界面，如一些儿童类的游戏，更适合采用色彩鲜亮的配色，以吸引他们的注意力；一些注重情感互动的游戏，更适合以暖色为基调给人温暖的感觉。

    - 对比色辅助
    亮色调可以作为小面积点缀配色，和背景色形成一定对比，起到聚焦视觉的作用。多用于按钮、重要信息等模块。

- 合理引导界面视觉效果
    - 游戏UI界面符合用户习惯
    用户浏览顺序一般遵循从上到下——从左到右——从大到小——从突出到整体

    - 抓住游戏UI界面重点
    理清玩家用户思路，清晰什么是玩家用户当下需要操作的信息，用对比色彩或者交互效果作为突出，不要让用户有一种在游戏UI界面“捉迷藏”的混乱思绪。比如重点消息提示加纯色角标提示，非重要信息可降低颜色饱和度，弱化其重要性。

    - 闭环式引导过渡
    当用户完成了他们应该做的步骤，给他们一个自然的方式继续实现他们的目标。如好友列表，当用户暂无好友信息时，可以在页面中引导去相应位置添加好友，避免动作的戛然而止。

- 界面文字排版简洁清晰
    - 简要文字
    - 可读性
    - 为文字分组
    - 善于利于文字格式
    - Use icon instead of texts.
    Simple icons + beautiful animations
- 统一界面视觉风格
    - 确定游戏UI界面风格
    - 统一交互视觉
    - 统一字体风格

small-scale game: one canvas, show and hide different UI

## UI and UX

UI is a subset of UX. 
UX is how people feel about a product and their pleaseure and satisfaction when using it, looking at it, holding it, and opening or closing it. The goals may be like Satisfying, Supporting... It is modeled based on user behavior, focusing underlying logic; Dynamic, change between flows.
UI is more of feedback on visual aspect, upper logic; Static.

## Games with Good UI

Dead Space, Persona 5, Pokemon Go, Death Stranding ...

- Dead Space, Last of Us II:
Hud and game are integrated into one. Help players get into flow.

- Persona 5:
华丽而富有设计感。
在《Persona4》中，整个游戏以黄色为基础，色彩丰富的画面；而《Persona5》中则是以红色为底色的“黑白调”。同时，《Persona5》还使用了平面角色的绘制方法加上3D模型，这两者的结合表达出了一种非常有设计感的画面，它不失华丽并且角色的各种动作也十分有趣。我认为，为了表达出这款游戏的世界观，游戏设计者使用了各种各样的方式，这些方式和以往的游戏UI相比，都有很大的突破。

- Pokemon Go
简洁朴素到舍弃一切个性。
举一个例子的话，《精灵宝可梦GO》中“CP”这个概念非常出色。CP是用来表示小精灵强大与否的数值，一般来说，它会设计成表示攻击力、速度等等的好几条数值线，但在《精灵宝可梦GO》中，所有的数值只有CP这一种，实在是非常简洁。除此之外，它还带有小精灵的重量和身高等等情报，这些都会让我们真正感觉到这些小精灵就像活着的一样。这些都是小细节，但我认为《精灵宝可梦GO》的设计理念就体现在这里了。
举一个例子的话，《精灵宝可梦GO》中“CP”这个概念非常出色。CP是用来表示小精灵强大与否的数值，一般来说，它会设计成表示攻击力、速度等等的好几条数值线，但在《精灵宝可梦GO》中，所有的数值只有CP这一种，实在是非常简洁。除此之外，它还带有小精灵的重量和身高等等情报，这些都会让我们真正感觉到这些小精灵就像活着的一样。这些都是小细节，但我认为《精灵宝可梦GO》的设计理念就体现在这里了。

- Death Stranding
扁平简约的科幻风格，全息的立体动态效果确实这款游戏UI最亮眼的地方。
Holographic, three-dimensional dynamic effects. 
很多地方都带了透视倾斜的数字全息效果。
Perspectively tilted digital holographic effect.

- Unrailed
Avatars walk on button to select.

## 总结

"流畅，直觉，觉察不到，高效"
UI 服务于游戏的体验目标，辅助玩法设计达成特定效果。如果一味追求高效率和易用性，而忽略了“玩” 这个过程，这将使 UI 设计本末倒置。


## Unity UI

- UI Toolkit
Newest, based on standard web technologies. UXML + USS + C#

- uGUI
GameObject-based UI. Supports advanced rendering and text features

- IMGUI
Code-driven UI Toolkit that uses the OnGUI function, and scripts that implement it, to draw and manage. Used for extension, plugins. Not recommended for building runtime UI.


## Unreal UI

- Blueprint（ User Inteface-Blueprint） 也就是常说的UMG (Unreal Motion Graphics)，是我们常用的UI工程文件 
- Font（字体资源拖入Content Browser自动生成）字体文件
- Texture (PNG资源拖进来可以自动生成) 图片资源文件
- Material 材质文件，可用于UI材质或者mesh材质
- Actor（Blueprint Class-Actor）可以摆放到场景中的文件类型，用于制作3DUI

## 事件编程

https://www.youtube.com/watch?v=OuZrhykVytg&ab_channel=CodeMonkey