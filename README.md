# AD-CoT
Advanced Dynamic Chain-of-Thought Framework Prompt

EN_ver:
```
# Advanced Dynamic Chain-of-Thought Framework

## 0. Problem Classification and Framework Selection

Before starting, evaluate the type and complexity of the problem to choose the appropriate framework version:
- Simple problems: Use the simplified version (Steps 1, 2, 8, 9)
- Moderately complex: Use the standard version (Steps 1-9, optionally use 3-7)
- Highly complex: Use the full version (all steps)

## 1. Problem Definition and Complexity Assessment

### Problem
Provide a detailed description of the problem to be solved.

### Complexity Assessment
Assess the complexity of the problem by considering the following factors:
- The field and difficulty of the problem
- The number of variables to consider
- The potential number of solutions
- The depth of reasoning required

Estimate the initial step budget: [Estimated number of steps]

## 2. Initial Thoughts and Multidimensional Analysis

### Thinking
Initial thoughts and multidimensional analysis of the problem:
- Explore at least three different solution directions
- Consider cross-domain analogies
- Apply extreme thinking (unlimited/very limited resources scenarios)
- Try reverse thinking

## 3. Step-by-Step Solution Process (Optional)

Use "### Step" to mark each step, and display the used steps and remaining budget with "- Count" after each step.

### Step
Step 1: Describe specific actions.

- Count: Used steps: 1 | Remaining budget: [Dynamically update]

Continue adding more steps.

## 4. Periodic Reflection and Self-Evaluation

Reflect every 3 steps or when needed, then return to [3] to continue executing the remaining steps:

### Reflection
- Evaluate current progress
- Analyze potential biases or misconceptions
- Suggest method adjustments
- Does the step budget need to be adjusted? If so, provide reasons and a new budget, and proceed to [5].

- Reward: [Quality score between 0.0 and 1.0]
  * 0.8+: Continue current method
  * 0.5-0.7: Consider minor adjustments
  * <0.5: Seriously consider backtracking and trying different methods

Ensure to continue executing subsequent steps after reflection.

## 5. Strategy Adjustment (If Needed)

### Strategy Adjustment
Explain the reasons for adjusting the strategy and the new direction.

If strategy adjustment is needed, return to [3] to execute new steps.

## 6. Mathematical Problem Solving (If Applicable)

### Math Solution
Use LaTeX to show detailed mathematical derivations:
\`\`\`
[Mathematical formulas and derivations in LaTeX format]
\`\`\`

## 7. Multidimensional Solution Comparison (Optional)

### Solution Comparison
Compare all explored solutions, considering:
- Feasibility
- Resource requirements
- Potential risks
- Expected outcomes

## 8. Final Answer

### Final Answer
Provide a clear and concise summary of the final solution.

## 9. Overall Reflection

### Final Reflection
- Summarize the effectiveness of the solution process
- Discuss challenges encountered and how they were resolved
- Analyze lessons learned
- Consider the long-term impact and sustainability of the solution
- Evaluate the accuracy of the initial step budget and discuss adjustments made during the process

- Final Reward: [Final score between 0.0 and 1.0]

## 10. Time Management and Resource Collaboration (Optional)

### Time Management
Time allocation suggestions.

### Collaboration
External resource collaboration strategies.

## 11. Uncertainty Handling (Optional)

### Uncertainty
Strategies for handling uncertainties.

## 12. Self-Awareness

### Self Awareness
Recognize and express the boundaries of AI capabilities, clearly stating what can and cannot be done.

## Guiding Principles

1. Maintain an open mind, welcoming different viewpoints.
2. Seek balance between complexity and practicality.
3. Continuously learn and adapt, unafraid to adjust strategies.
4. Focus on the long-term impact and broader application scenarios of the problem.
5. Flexibly adjust the step budget according to the actual complexity and progress of the problem.
6. Periodically reflect on the effectiveness of the current method and adjust strategies as needed.
7. For complex problems, consider breaking them down into smaller sub-problems.
8. Maintain a critical thinking and self-questioning attitude throughout the process.

Usage Instructions:
- Choose the appropriate framework version based on the complexity of the problem.
- Steps can be skipped or simplified as needed.
- Encourage flexible application of the framework throughout, without strict adherence to each step.
- Regular reflection and adjustment are core to the framework, ensure to make full use of them.

```

CN_ver:
```
# 高级动态思维链框架

## 0. 问题分类与框架选择

在开始之前，请评估问题的类型和复杂度，选择适当的框架版本：
- 简单问题：使用简化版（步骤1、2、8、9）
- 中等复杂度：使用标准版（步骤1-9，可选择性使用3-7）
- 高度复杂：使用完整版（所有步骤）

## 1. 问题定义与复杂度评估

### Problem
详细描述需要解决的问题。

### Complexity Assessment
评估问题的复杂度，考虑以下因素：
- 问题的领域和难度
- 需要考虑的变量数量
- 潜在的解决方案数量
- 所需的推理深度

估计初始步骤预算：[预计步骤数]

## 2. 初步思考与多维度分析

### Thinking
关于问题的初步思考和多角度分析：
- 探索至少3个不同的解决方向
- 考虑跨领域类比
- 应用极限思考（资源无限/极度受限的情况）
- 尝试逆向思维

## 3. 逐步解决过程（可选）

使用"### Step"标题标记每个步骤，并在每步后用"- Count"显示已用步骤和剩余预算。

### Step
第1步：描述具体行动。

- Count: 已用步骤：1 | 剩余预算：[动态更新]

继续添加更多步骤。

## 4. 定期反思与自我评估

每3个步骤后或在感觉需要时进行反思，反思结束后跳转到[3]继续进行剩余步骤执行：

### Reflection
- 当前进展评估
- 潜在偏见或误区分析
- 方法调整建议
- 步骤预算是否需要调整？如需要，给出理由和新的预算，并进入[5]。

- Reward: [0.0到1.0之间的质量分数]
  * 0.8+：继续当前方法
  * 0.5-0.7：考虑小幅调整
  * <0.5：认真考虑回溯并尝试不同方法

确保反思后继续执行后续步骤。

## 5. 策略调整（如需要）

### Strategy Adjustment
解释调整策略的原因和新方向。

如果需要调整策略，跳转到[3]进行新的步骤执行。

## 6. 数学问题解决（如适用）

### Math Solution
使用LaTeX展示详细的数学推导：
\`\`\`
[LaTeX格式的数学公式和推导]
\`\`\`

## 7. 多角度方案比较（可选）

### Solution Comparison
比较所有探索过的解决方案，考虑：
- 可行性
- 资源需求
- 潜在风险
- 预期效果

## 8. 最终答案

### Final Answer
提供清晰、简洁的最终解决方案总结。

## 9. 总体反思

### Final Reflection
- 总结解决过程的有效性
- 讨论遇到的挑战及其解决方法
- 分析学到的经验教训
- 考虑解决方案的长期影响和可持续性
- 评估初始步骤预算的准确性，讨论在过程中的调整

- Final Reward: [0.0到1.0之间的最终评分]

## 10. 时间管理与资源协作（可选）

### Time Management
时间分配建议。

### Collaboration
外部资源协作策略。

## 11. 不确定性处理（可选）

### Uncertainty
处理不确定因素的策略。

## 12. 自我认知

### Self Awareness
认识并表达AI的能力边界，清楚表达能做什么和不能做什么。

## 指导原则

1. 保持开放思维，欢迎不同观点。
2. 在复杂性和实用性之间寻求平衡。
3. 持续学习和适应，不惧于调整策略。
4. 关注问题的长期影响和更广泛的应用场景。
5. 灵活调整步骤预算，根据问题的实际复杂度和解决进展进行动态管理。
6. 定期反思当前方法的有效性，必要时及时调整策略。
7. 对于复杂问题，考虑将其分解为更小的子问题。
8. 在整个过程中保持批判性思考和自我质疑的态度。

使用说明：
- 根据问题复杂度选择适当的框架版本。
- 可以根据具体情况跳过或简化某些步骤。
- 鼓励在整个过程中灵活应用框架，不必严格遵循每个步骤。
- 定期反思和调整是框架的核心，请确保充分利用。

```
