def jiami1(str)
  string=""
  str.each_byte {|a| string=string+chr(a+rand(128))}
  return string
#死数据加密，无法解密，♾️
加密过程：
随机加密
破解概率为0
将数据永久性毁坏，无法修复
最安全的密码，就连神也解不开
def jiami2(str)
  string=""
  len=str.length
  str1=(0..len).each do {|a| return chr(ord(a)+rand(97))} 
  strarr=str.split("fuhao")
  count=0
  strarr.each{|a| string=string+a+str1[count] if count <= len;if count == len count=0 }
  return string+str1
加密过程：
对数据进行随机加密
解码方式为随机解密
破解概率为～0
解出概率为2的字符次方
def jaimi3(str)
  string=""
  sex=rand(97,113)
  str.each_byte{|x| if x.ord!=sex x=x.ord-sex/2+1+x.ord;if x.class == Double x=abs(x)+1; string+=x.chr}
  return string,sex.chr
加密过程：
对数据进行除1处理
其他数据同它堆积
解法-1*2+字符1
速度快
安全
破解概率为2的字符次方
def jiami4(str)
  加密过程：
  组加密
  选出前两个相同的大于等于2的字符串     对整组进行加密处理
举例如下
23ds32235
23
23fu55237
加密完成

def jiami5（）  
加密过程：
    对称加密
两组数据等长
相互加密
234346ag

hdfgh235
hdf    b
fab    g

def jiami6（）
加密过程
不等加密公式等长

随机字符串1


随机长字符串

1-随
。。。
随-串


def jiami7（——）

布丁加密法则
最后一个字符非、n

num=log（ord（chr））
12.。。。10

21.。。。10


def jiami8（——）
加密共识

加字符加密法
jaklsfjlas
加密方式特殊符号内部按位加最大为编码位数
外面反转
#kcnpx#saljf


def jiami9（）
加密modern

新建一个ttf文件
转化为ttf文件编码
即可


def jiami10（）
加密方式：
等于加密

将某符号进行等价交换  q   ==   💰
asdfwefalsadjfagasgaga

q-a+q
。。。。
q
💰

def jiami11（）
加密方式：
可能性加密
判定 abcdefghijklmnopqrstyvwxyz  //==
aagfdag
a+10
b+9
g+9
f+9


。。。。
26轮流

不是 概率-1 最低为0
     =100% 概率=10
不需要解密的加密方式
效率低但安全度高。
数据混杂度高》60%

def jiami12（）

中文加密法

abcdef 。。。 转化为中文的 啊 比
中文转化为拼音

安全性高解密难度大（自己人也是）


def jiami13（）
super加密
随机生成super块
非常规破解
随机生成序列
进行对比替换

erert


sdfaagaaga agasgasasd dasfsfd 
                erert   asasd

解密不易（安全性在于（块密复杂度），）


def jiami14（）
加密方法：
768574766798275
234092759023759
257982735927897
285903859089023
285092383025990
280593802985093
上面不变

92835
23789
32794

25798
23409
76857

倒序对比加密

def jiami15（）
图加密方式

文件前缀更改为图样式。


def jiami16（）

建立信任链

数据变形
adfssf
假设-》为 86 87
aaaa
至少为-》*2个字符
  ik-》
-》 -》——》 ->
》
》


压缩
压缩度数10-33 ✅
压缩度数34-50 较差
压缩度数51-75 🍵
压缩度数75-100> ❌

4字节 -两字节 -50%
      -1字节  -75%

数据有效性
数据可压缩度
数据冗余度
数据分解度
数据等价度
数据趋向性
数据平等性
数据可用评估
极限压缩适用可能性
数据暴力压缩保留性
数据最大公约数粉碎
目前最大化数据重复率























