# 零基础入门推荐系统-新闻推荐
## 单路nn召回，线上A榜能够达到MRR27+

## 改进方向
  仅利用了用户与新闻的点击数据（其他特征没有用到），可以尝试引入给的物品预训练嵌入表征以及其他特征如时间特征（在进行排序建模时，发现该特征能够有效提升最终的排序效果，在现实生活中时效性高的新闻往往更容易得到人们的关注）等
 
