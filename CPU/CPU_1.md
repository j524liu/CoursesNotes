# 微机原理与接口

1. 数的表示

   1. 原码
      $$
      [x]_原=\begin{cases}
      x,&0\leq x<2^n\\
      2^n-x,&-2^n<x\leq 0
      \end{cases}
      $$
      

   2. 补码
      $$
      [x]_补=\begin{cases}
      x,&0\leq x<2^n\\
      2^{n+1}+x,&-2^n\leq x\leq 0
      \end{cases}
      $$
      

   3. 反码
      $$
      [x]_反=\begin{cases}
      x, &0\leq x<2^n\\
      (2^{n+1}-1)+x, &-2^n<x\leq 0
      \end{cases}
      $$
      