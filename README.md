# 协议说明：

## 非必填字段：

| 属性类型 | 空值处理 |
|--------|---------|
|  array   |   []    |
|  string  |   过滤   |
|  number  |   过滤   |
|  object  |   过滤   |
|  bool    |   过滤   |



1、世界
world name:必选
world background image:1张-必选
world story:
   image必选 audio必选 eye可选 n组
unlock rules（解锁规则）：  int0-10
level up：
   audio必选 eye可选  n组-随机1组
unlock story（解锁后的故事）：
   image必选 audio必选 eye可选 n组
world transitions（世界过渡故事）:
   image audio eye n组-可选（仅世界1需要上传）
   
2、主题
name
image:1张-必选
intro:
  audio必选 eye可选 1组
Celebration:
  audio必选 eye可选 n组
Gift before:
  audio必选 eye可选 n组-随机1组
Gift after:
  audio必选 eye可选 n组-随机1组
badge:
  image：1张-必选
  before:
     audio必选 eye可选 n组
  after：
     audio必选 eye可选 n组

3、素材
（1）intro：
title:
audio eye feet 1组-必选
randomized：是/否
（2）outro:
title:
audio eye feet 1组-必选
door open:开/关
randomized：是/否
（3）mood:
title:
music in必选   eye in可选  1组
music loop
musi out必选   eye out可选  1组
randomized：是/否
 
4、module
（1）factoid：
Background：1张-必选
Animation：1张-png-必选
intro：随机1个/指定一个
content：
    audio eye feet 1组-必选
outro：随机1个/指定一个
（2）anecdote：
image必选 audio必选 eye可选   1组
mood：随机1个/指定一个
（3）joke：
gif：1张-必选
audio：1个-必选
eye：1个-可选
door：开/关
（4）video:
intro:
    audio:1个-必选 eye:1个-可选
video：1个-必选 eye:1个-可选
（5）trivia：
intro audio 1个-必选  intro eye 1个-可选
guide audio 1个-必选  intro eye 1个-可选

1、choice：
  question:audio-必选  eye-可选  text-必选   1组
  option:
    A:audio-必选  eye-可选 text-必选 1组
    B:audio-必选  eye-可选 text-必选 1组
    C:audio-必选  eye-可选 text-必选 1组
  answer:A/B/C
  answer analysis:audio-必选  eye-可选  1组
  right answer:audio-必选  eye-可选  n组
  wrong answer:audio-必选  eye-可选  n组
  
2、T/F:
  question:audio-必选  eye-可选  text-必选   1组
  answer:T/F
  answer analysis:audio-必选  eye-可选  1组
  right answer:audio-必选  eye-可选  n组
  wrong answer:audio-必选  eye-可选  n组
  
（6）slideshow:
intro audio：1个-必选
intro eye：1个-可选
content：
  image必选 audio-必选 eye-可选  n组

（7）DIY:
intro audio：1个-必选
intro eye：1个-可选
step：
  image必选 audio-必选 eye-可选  n组
  
（8）conversation:
round：n组
  必选：
  corbit：audio-必选  eye-可选 text-必选 1组
  answer：Y/N  T/F  Tell me more/I donnot know
  corbit：audio-必选  eye-可选 text-必选 1组
  必选：
  corbit：audio-必选  eye-可选 text-必选 1组
  answer：Y/N  T/F  Tell me more/I donnot know
  corbit：audio-必选  eye-可选 text-必选 1组
  可选新增：
  corbit：audio-必选  eye-可选 text-必选 1组
  answer：Y/N  T/F  Tell me more/I donnot know
  corbit：audio-必选  eye-可选 text-必选 1组
ending：可选
  audio-必选  eye-可选 text-必选 1组



