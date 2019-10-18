## 快读
```cpp
inline int read() 
{
    int res=0;
    char ch=getchar();
    while(ch>'9'||ch<'0')
        ch=getchar();
    while(ch>='0'&&ch<='9')
    {
        res=res*10+ch-'0';
        ch=getchar();
    }
    return res;
}
```
