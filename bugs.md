## Bug
+ 输出是没有加\n,错误提示wrong answer  青岛费用流，wrong了两个小时
+ 输入如果是输入到n和m都为0时结束时应该是 (n || m)  不是 n && m
+ poj g++ double输出应该为%f , 不能用万能头文件
+ for 0-n 或者 0-m  最后一个不要加 = 
+ 取余mod的时候，写  ((x%mod)+mod) % mod  防止负数
+ wrong 了想一想是不是int*int 爆掉int了，改用longlong
