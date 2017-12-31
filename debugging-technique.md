# 调试技巧

## 输入输出重定向

### C/C++语言层面的输入输出重定向

```cpp
freopen("in.txt", "r", stdin);
freopen("out.txt", "w", stdout);

```

### 系统层面的输入输出重定向

PowerShell

```ps
Get-Content in.txt | .\Program.exe >> out.txt

```

CMD

```cmd
Program.exe < in.txt > out.txt

```

## 条件编译

```cpp
#ifndef ONLINE_JUDGE
// Do something
#endif

```
