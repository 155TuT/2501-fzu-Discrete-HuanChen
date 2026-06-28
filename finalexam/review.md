# 离散复习

$ \lor \land \to \Leftrightarrow \equiv \lnot $

## 真值表法求主析取、主合取

0为假 1为真

“析取 $ \lor $ ”只要不是00就是1（或）

”合取 $ \land $ “只要不是11就是0（与）

“蕴含 $ \to $ ”只要不是10就是1

“等价 $ \leftrightarrow $”不是11和00就是0

成真赋值是小项相或（主析取），成假赋值是大项相与（主合取），下标为对应顺序

## 逻辑公理

1. 双重否定律 $ \lnot\lnot P \Leftrightarrow P$

2. 等幂律 $ P \lor P \Leftrightarrow P, P \land P \Leftrightarrow P$

3. 交换律 $ P \lor Q \Leftrightarrow Q \lor P, P \land Q \Leftrightarrow Q \land P$

4. 结合律 $ P \lor (Q \lor R) \Leftrightarrow (P \lor Q) \lor R, P \land (Q \land R) \Leftrightarrow (P \land Q) \land R$

5. 分配律 $ P \lor (Q \land R) \Leftrightarrow (P \lor Q) \land (P \lor R), P \land (Q \lor R) \Leftrightarrow (P \land Q) \lor (P \land R)$

6. **德摩根律** $\lnot (P \lor Q) \Leftrightarrow \lnot P \land \lnot Q, \lnot (P \land Q) \Leftrightarrow \lnot P \lor \lnot Q$

7. 吸收律 $ P \lor (P \land Q) \Leftrightarrow P, P \land (P \lor Q) \Leftrightarrow P$

8. **蕴含等值式** $ P \to Q \Leftrightarrow \lnot P \lor Q$

9. **等价等值式** $ P \leftrightarrow Q \Leftrightarrow (P \to Q) \land (Q \to P)$
