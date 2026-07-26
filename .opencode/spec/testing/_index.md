# 测试规范

本域定义测试策略和覆盖率要求。

## 注入规则

派 `system-tester` 时，本文件注入 prompt。

## 测试层级

按 Orchestrator 四层测试体系：Layer 0 (UI 视觉) → Layer 1 (API/集成) → Layer 2 (E2E) → Layer 3 (策略)

示例（替换为实际项目规则）：

- 核心业务逻辑覆盖率 ≥ 80%
- E2E 测试覆盖关键用户路径（登录、下单、支付）
