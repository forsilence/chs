## chs (computer hardware simulation) 

计算机硬件模拟-模拟计算简单的硬件的逻辑

### 1 计算机cpu加法器(cpu adder)


逻辑门 ：与 或 非

| 名称 | 输入个数 | 输出个数 |
|---|------|---|
|与 | 2    | 1 |
|或 | 2    | 1 |
|非 | 1    | 1 |

逻辑门

ins ==> calculate ==> out

```
      +=========+  +==============+
      |         |  |     |        | 
 ====> ins| out-----> in1|        |
      |         |  |     |        |
      +=========+  |     |        |
                   |     | ------------> out
      +=========+  |     |        |
      |         |  |     |        |
 ====> ins| out-----> in2|        |
      |         |  |     |        |
      +=========+  +==============+
 
```
