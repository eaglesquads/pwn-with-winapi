#### ~By d4s7 | BSec Team


> In this article I will explain WinAPI codes so you can hack your victim.
>> This content is fully focused on education and learning. I am not responsible for your actions used in this tutorial.

Windows API
: the Windows API is a set of functions that are usually performed by Windows.

And now you will see various functions of WinAPI:

- [ ] OpenProcess()
- Open a actual process.
```cpp
HANDLE OpenProcess()
  DWORD dwDesiredAccess,
  BOOL bInheritHandle,
  DWORD dwProccessId
);
```

