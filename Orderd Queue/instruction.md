/*
最大堆的实现
对于堆，若parent的结点为i,则
Lchild为2*i,Rchild位2*i+1
*/
/*这里为了计算方便，将根结点元素储存在Elements[1]中
主要实现了利用数组存储树中元素，利用完全二叉树(二叉堆)
实现最大(最小)优先队列(堆)的建立、插入、以及删除最大(最小)
逻辑比较清晰，适合新手
*/