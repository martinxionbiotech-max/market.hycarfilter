# market.hycarfilter — Hycarfilter Market Insights

行业报告 / 出口市场情报子站（MkDocs Material）。定位「被检索、被引用的行业报告层」。

## 四仓定位

```
hycarfilter.com        (Astro 商业主站)   → 说服采购者「为什么要买」
data.hycarfilter.com   (MkDocs 产品数据库) → 型号/规格唯一真值「参数是多少」
tech.hycarfilter.com   (MkDocs 技术标准)   → 「怎么做 / 怎么测 / 凭什么」
market.hycarfilter.com (MkDocs 行业报告)   → 本仓「这款在哪个市场怎么卖」
```

**内容红线**：本仓只写「行业层面」内容——市场规模/格局、区域需求、趋势、采购流程、贸易合规框架；**不重复 data 站产品数值、不重复 tech 站工艺/标准原理、不写主站营销文案**。引用他站数值时**同值引用**（HS 编码、效率档位、认证字段等以 data 站 canonical 数据集 `data.hycarfilter/data/products.json` 为准）。

## 来源性质分层标注

本仓所有内容遵守一条标注纪律，每页顶部以 note 声明，正文以行内标签区分：

- **[行业常识]** —— 滤清器行业通用做法、公开共识；
- **[框架参考]** —— 认证 / 准入 / 合规框架介绍，**不构成认证或法律结论**；
- **[数据引用]** —— 引用 data 站 canonical 数据集同值（HS 编码 / 效率 / 认证字段等）；
- **[分析判断]** —— 研究员原创主观判断（小筑 ✍️），供采购决策参考。

**估算性市场数据**（市场规模区间、增速等）一律显式标注「**估算参考 / for reference only**」，非权威统计值，仅供量级参考。

## 构建

```bash
pip install -r requirements.txt
mkdocs build
```

## 同步

本仓不存储产品数值；引用 data 站数值时逐项核对同值（0 冲突）。data 站 `products.json` 版本更新后，回查本仓「数据引用」标签出现的数值是否仍需一致。
