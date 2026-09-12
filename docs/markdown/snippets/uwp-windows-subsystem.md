## UWP is recognized as a Windows subsystem

UWP is now handled as a Windows subsystem. Set it in the `[host_machine]`
section of a machine file with:

```ini
[host_machine]
system = 'windows'
subsystem = 'uwp'
```