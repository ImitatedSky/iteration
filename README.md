# iteration

find parameters W by 梯度下降（Gradient descent）

這裡是希望SSE = loss 最小 →不斷迭代後趨近於零 最好)

```mermaid
flowchart LR
Start(Start)
End(End)
Start-->function
function-->|a,b|output
output-->|loss|refreshW
refreshW-->function

output-->|if loss < se|End

```

![image](https://user-images.githubusercontent.com/111834126/216217844-1592bc83-bde1-47d7-ad48-c2d86c281988.png)



