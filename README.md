> https://tishina.in

a red team operator's journey to writing public code.
```
NtProtectVirtualMemory(RW) ->
	NtWriteVirtualMemory ->
		NtProtectVirtualMemory(RX) ->
			NtCreateThreadEx
```
