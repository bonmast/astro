---
title: Example Guide
badge:
	text: New
	variant: tip
---

An example of a code block

```powershell
// PowerShell
foreach ($file in $files) {
	Write-Host $file
}
```

A more complex example of a code block

```diff lang="powershell"
// files.ps1
foreach ($file in $files) {
-  Write-Host $file
+  Write-Host $file.Path
}
```
An example of simple asides

:::caution[Warning]
This is a warning
:::

:::danger[Stop]
This is a serious warning
:::

:::note
This is a note
:::