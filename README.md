- **AI绘画警告，AI绘画大模型的正途，或者说本质是以大量数据集训练出自己画风，随着AI绘画的发展，模型大体可分为两类，一种是大模型在市面上已经完全可以产出不侵权且拥有自主创新、拥有自己版权的作品，详情请自行了解，一种是特定画风的小模型训练，也是最为人诟病的一种模型，本机器人的AI绘画模型便是以少量数据集训练的小模型，并带有强烈的模仿特定画风，无法视其为市面上存在的“利用大量数据集训练的可产出不侵权且拥有自主创新作品、拥有自己版权作品的AI绘画大模型”，本机器人的AI模型它的训练过程与结果，您可以将它理解为“它以极快到难以想象的速度模仿人类的学习临摹过程。临摹并学习了另外一个特定画师的作品画风。”临摹者本身，无论是AI还是人类产出的作品将其作为临摹学习目的不侵犯任何版权，涉版权应当以产出的内容为准，此小模型所产出的所有内容仅供您学习参考，应当由指令的使用者承担责任，请勿将产出的作品作为观看用途的二次盈利目的。**

- **关于收取成本费1元：由于该模型服务运行在云GPU服务器上，每个小时的成本为1.22元，为了防止滥用及成本补贴**
- **我们将采取收费1元=20次生成次数的使用限制**
- **收取的费用仅为“运营成本补贴”，用于维护模型的运行，用户缴纳费用，主体上针对的是使用模型工具的过程，而非图片观看用途的盈利目的**

## 指令实例

绘画猫哥，1boy，独奏，舌头，吐舌头，猫耳，白头发，白袜子，上半身赤裸，白色内裤，看向观众，坐着，厕所，马桶，水，手在背后
-r 1024x1024 -t 25 -c 5


### 绘画指令

命令前缀是“绘画”，接着选择模型，比如：

- **绘画猫哥**
- **绘画1助**
- **绘画兔子**

可以根据自己想要的画风选择模型。
### 画风预览
- #### 猫哥
- ![Image_1067382340501312](https://github.com/user-attachments/assets/46bcab0d-5efa-40d2-aec1-207a037d954c)

- #### 兔子
- ![7V~E$ 7~_GQ$N~EA2`~S_AH](https://github.com/user-attachments/assets/8fab67d0-3ad5-424b-8690-4cf3268219cb)

- #### 1助
- ![Image_1089475440846582](https://github.com/user-attachments/assets/c35fadf2-8442-4a3e-abbf-f59f35130250)

- ### 提示词

顾名思义，提示AI该画什么，可以前往：https://tags-dev.novelai.dev/ 学习提示词的应用。

常用提示词包括人物特征、服装特征、情境与环境等。以下是一个具体的例子：


1boy，独奏，舌头，吐舌头，猫耳，白头发，白袜子，上半身赤裸，白色内裤，看向观众，坐着，厕所，马桶，水，手在背后


#### 说明：

- **角色特征**：
  - 角色数量：1个男孩（1boy）
  - 外貌：白头发、猫耳、舌头
  - 身体：上半身赤裸

- **服装特征**：
  - 袜子：白袜子
  - 内衣：白色内裤

- **情境与环境**：
  - 动作：坐着、手在背后、吐舌头
  - 场景：厕所、马桶、水

- **视角**：看向观众
- **独奏**：强调只有一个男孩

### 提示词使用建议：

- **提示词必须使用，逗号隔开**。
- **避免使用口语化句子**，尽量使用动词、名词。
  - 错误提示词例子：2个男孩站在草地上亲吻
  - 正确提示词例子：2boy，站着，草地，亲吻
  - 错误提示词例子：小男孩旁边的地上放着鸡蛋
  - 正确提示词例子：1boy，地面，鸡蛋
  - 错误提示词例子：小男孩手里拿着内裤
  - 正确提示词例子：1boy，手/双手，拿着，内裤
- **也尽量不要使用形容词**，如“温柔”、“美丽”、“可爱”之类的形容词，这些词意义不大，反而会影响提示词的关联度。

---

## 参数说明
（参数之间也应该用空格隔开）
### 分辨率 `-r`
指定图像分辨率，最高不能超过 2048×2048（宽×高）。

例如：

- `-r 960x1024`
- （生成的最终质量也受图像分辨率的影响，比如你的构图角色是站着的，应当将分辨率调整为竖图，否则AI可能会将角色的腿部以下截断）

### 采样迭代步数 `-t`
指定AI绘图的采样迭代步数。步数越低，图像越粗糙；步数越高，图像细节越丰富，但可能出现多头多四肢畸形等问题。一般建议在 20-30 之间：

- `-t 25`

### 服从度 `-c`
指定AI提示词的服从度。越低，AI绘制的内容越开放，不完全按照提示词绘制；越高，AI会更严格按照提示词绘制。一般建议 4-10 之间：

- `-c 4`
