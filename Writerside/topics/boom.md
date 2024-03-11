# 💣数字炸弹

<tldr>
    <p>关键词: <shortcut>boom</shortcut> <shortcut>Boom</shortcut> <shortcut>BOOM</shortcut> <shortcut>bomb</shortcut> 
<shortcut>Bomb</shortcut> <shortcut>BOMB</shortcut> <shortcut>数字炸弹</shortcut></p>
</tldr>

## 介绍

Mia会随机生成一个0~100之间的数字 `N`，这个数字既是“炸弹”。当有玩家输入数字时，会更新边界值。玩家需要在10次之内将边界值缩小到这个数字的两侧，即 `N-1` 和 `N+1` 。

## 积分规则
1. 玩家每次输入数字可获得1%score_tag%，最高可以通过这种方式获得5%score_tag%。
2. 踩到“炸弹”（即输入数字为 `N` ）的玩家则会被清空本次游戏中获得的所有积分，游戏结束。
3. 最后一名将边界值缩小到 `N-1` 或 `N+1` 的玩家将额外获得1积分，游戏结束。
4. 当10次机会全部用完，且没有玩家踩到“炸弹”或成功缩小边界值时，所有参与游戏的玩家只能获得1%score_tag%。