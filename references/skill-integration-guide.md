# 多技能协同指南

> 当用户问题涉及多个家庭管理维度时，本指南提供协同优先级规则、调用顺序建议和综合整合方法。

## 何时需要多skill协同

判断标准：用户query明确涉及2个以上维度，或单一skill无法完整回答。

### 典型多维度场景

| 场景 | 涉及skill | 协同原因 |
|------|----------|---------|
| "孩子写作业磨蹭，是态度问题还是能力问题？" | self-driven-parenting + child-dev-learning | 需先排查发育/能力因素，再处理态度/习惯 |
| "要不要报编程班？" | structured-thinking-decision + child-dev-learning | 决策前需评估孩子是否具备相关能力基础 |
| "小学六年如何系统规划？" | structured-thinking-decision + self-driven-parenting + brain-health-advisor | 决策框架+执行方法+学习方法三位一体 |
| "孩子聪明但成绩差，记忆力也不好" | child-dev-learning + brain-health-advisor | 发育评估+认知训练双管齐下 |
| "孩子考试焦虑，想报补习班" | self-driven-parenting + structured-thinking-decision | 情绪问题+决策判断 |
| "孩子做什么都三分钟热度，该报什么兴趣班？" | child-goal-discovery + structured-thinking-decision | 先诊断目标状态，再做具体选择 |
| "我们想重新梳理家庭方向，但不知道怎么开始" | family-mission-charter + structured-thinking-decision | 使命愿景+决策方法论结合 |
| "三年级了，想让孩子更自立，但怕放太早" | child-self-reliance-skill-tree + self-driven-parenting | 授权节奏+心理动机双保障 |
| "孩子问为什么要学习，我不知道怎么回答" | child-goal-discovery + self-driven-parenting | 深层目标感+日常动机联动 |
| "家里对教育方向有分歧，想定个家规" | family-mission-charter + li-xigui-parenting-guide | 宪章框架+方法论工具嵌入 |

## 协同优先级规则

### 规则一：诊断优先于干预

当问题可能涉及发育/能力缺陷时，**先调用 child-dev-learning 排查**，确认非发育问题后再调用其他skill。

> 例："孩子写字慢" → 先排查是否为书写障碍（child-dev-learning），再讨论习惯培养（self-driven-parenting）

### 规则二：决策优先于执行

当问题既涉及"选什么"又涉及"怎么做"时，**先调用 structured-thinking-decision 明确方向**，再调用执行层面的skill。

> 例："选奥数还是编程" → 先用structured-thinking-decision做选择，再用self-driven-parenting/child-dev-learning支持执行

### 规则三：动机与能力并重

当孩子的学习问题同时涉及"不愿学"和"学不会"时，**self-driven-parenting 和 brain-health-advisor/child-dev-learning 同等重要**，建议同时调用。

> 例："孩子不想学，学了也记不住" → 同时从动机（self-driven-parenting）和认知策略（brain-health-advisor）两个角度给出建议

### 规则四：认知支持是通用底座

brain-health-advisor的学习方法/认知训练内容可以作为其他skill建议的**补充和强化**，通常作为协同skill而非主skill。

> 例：self-driven-parenting建议"给孩子自主权"时，可补充brain-health-advisor的"如何帮助孩子建立有效的学习计划"

## 常见协同模式

### 模式A：串行诊断 → 干预

```
child-dev-learning（排查问题根源）
    ↓
[如果是发育/能力问题] → 继续 child-dev-learning 干预建议
[如果是态度/习惯问题] → 转向 self-driven-parenting
```

**适用场景**：用户不确定问题性质，需要先诊断后干预

### 模式B：决策 → 执行

```
structured-thinking-decision（做出选择/制定框架）
    ↓
self-driven-parenting（执行中的心理支持）
    ↓
brain-health-advisor（执行中的方法优化）
```

**适用场景**：用户需要先做选择，再落实执行

### 模式C：并行双轨

```
self-driven-parenting（动机与心理）
        ↘
          → 综合整合
        ↗
brain-health-advisor（方法与认知）
```

**适用场景**：用户问题同时需要心理支持和认知支持，两者独立但互补

### 模式D：三足鼎立

```
          structured-thinking-decision（框架与决策）
                     ↓
    self-driven-parenting ← 综合整合 → brain-health-advisor
         （动机心理）              （方法认知）
```

**适用场景**：长期规划类问题，需要决策框架+心理支持+方法支持

## 综合整合方法

### 整合原则

1. **不重复**：各skill的核心观点保留，重复内容去重
2. **不矛盾**：如skill间建议有冲突，评估后选择更适配当前场景的，或说明不同角度的考量
3. **有主次**：明确标注哪个维度的建议是当前最优先的
4. **有联系**：说明不同维度建议之间的关联（如"在改善学习方法的同时，也要注意保护孩子的学习动机"）

### 整合输出模板

```markdown
## 综合评估

您的问题涉及 **N个维度**：
1. **[维度1]**（主/次）：简要说明
2. **[维度2]**（主/次）：简要说明
3. ...

### 各维度专业建议

**[维度1] — 来自 [skill-name]**
[该skill的核心建议，保持专业完整性]

**[维度2] — 来自 [skill-name]**
[该skill的核心建议，保持专业完整性]

### 维度间的关联

[说明维度1和维度2如何相互影响，以及综合考量]

### 优先级建议

1. **第一步（最优先）**：[具体行动]
2. **第二步**：[具体行动]
3. **第三步**：[具体行动]

### 需要注意的边界

[如涉及医学诊断建议就医、如某些建议需根据孩子具体情况调整等]
```

## 避免过度协同

以下情况**不需要**多skill协同，单一skill即可：

- 用户问题明确属于单一维度（如"DHA有用吗"→brain-health-advisor单独即可）
- 协同带来的增量价值不明显
- 为了"全面"而强行调用多个skill，反而稀释核心建议

**判断标准**：如果调用第二个skill后，输出内容与第一个skill高度重叠，或只是边缘相关，则不调用。
