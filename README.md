#### By d4s7 | BSec Team :warning:

> In this article I will explain WinAPI codes so you can hack your victim.
> This content is fully focused on education and learning. I am not responsible for your actions used in this tutorial.

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
  // Header: windows.h
);
```

| Term | Description |
| ----------- | ----------- |
| dwDesiredAccess | Access of object. |
| bInheritHandle | If TRUE, creates an handle. |
| dwProccessId | ID of process. |

[-space¹-]

[-space²-]

- [ ] ReadProccessMemory()
- The name already says.
```cpp
BOOL ReadProcessMemory(
  HANDLE  hProcess,
  LPCVOID lpBaseAddress,
  LPVOID  lpBuffer,
  SIZE_T  nSize,
  SIZE_T  *lpNumberOfBytesRead
  // Header: windows.h
);
```

| Term | Description |
| ----------- | ----------- |
| hProcess | Handle of proccess. |
| lpBaseAddress | A pointer to the base address of proccess. |
| lpBuffer | The buffer to proccess. |
| nSize | The number of bytes. |
| lpNumberOfBytesRead | The number of bytes transfered to specified buffer. |

[-space¹-]

[-space2-]

- [ ] WriteProcessMemory()
- Writes data to an area of memory in a specified proccess.
```cpp
BOOL WriteProcessMemory(
  HANDLE  hProcess,
  LPVOID  lpBaseAddress,
  LPCVOID lpBuffer,
  SIZE_T  nSize,
  SIZE_T  *lpNumberOfBytesWritten
);
```

| Term | Description |
| ----------- | ----------- |
| hProcess | Handle of proccess. |
| lpBaseAddress | A pointer to the base address of proccess. |
| lpBuffer | The buffer to proccess. |
| nSize | The number of bytes. |
| lpNumberOfBytesRead | The number of bytes transfered to specified buffer. |

**LEMBRAR DE COLOCAR O RESTO DAS COISAS AQ. POR EXEMPLO, O USO DESSAS FUNÇÕES E EXPLICAÇÃO DE OUTRAS**


