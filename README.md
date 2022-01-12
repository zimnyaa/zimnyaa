A Red Team Operator's / AppSec PT journey to writing public code.
```
NtProtectVirtualMemory(RW) ->
	NtWriteVirtualMemory ->
		NtProtectVirtualMemory(RX) ->
			NtCreateThreadEx
```
