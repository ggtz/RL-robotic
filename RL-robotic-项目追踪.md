# 20241013-metapolicy部署maska，b；处理masks
## 项目进度
- [x] 完成lora层的代码部署：使用MetaPolicy类的self.embeds_bb来模仿完成 embed_a、embed_b
同时由embed_a衍生出mask_a 作用于A，B矩阵的输出层
停止emb_bb的使用，
- [ ] 目前完成至masks字典的代码更改 
原：masks=mask_L
现在更改为masks = mask_a,mask_b,mask_l
并**要使masks能够在全部代码中应用**。
**目前mask进度**

![CSDN图标](https://github.com/ggtz/RL-robotic/blob/main/Pasted%20image%2020241013215031.png "CSDN图标")


## 所遇难处
目前在解决masks部署问题

## 学习知识

无
