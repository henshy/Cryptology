# CTR

- （CounTeR）计数器模式
- 初次累加的计数器进行加密后，和对应明文分组XOR

### 算法

##### 加解密

​							加密和解密都是用加密算法

![](image/CRT模式.png)

##### CTR生成规则

![](image/CTR计数器生成规则.png)

### 特点

- 可并行计算
- 速度快

### 攻击

##### 比特攻击

- 和OFB一样，密文一个比特的反转，就会造成明文一个比特的变化。