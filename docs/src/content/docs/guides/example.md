---
title: Example Guide
badge:
	text: New
	variant: tip
---

An example of a basic code block

```
foreach ($file in $files) {
	Write-Host $file
}
```

An example of a basic code block, formatted with PowerShell

```powershell
foreach ($file in $files) {
	Write-Host $file
}
```

An example of a basic code block, formatted with PowerShell with no frame

```powershell frame="none"
foreach ($file in $files) {
	Write-Host $file
}
```

An example of a basic code block, with a title

```powershell title="Powershell Example"
foreach ($file in $files) {
	Write-Host $file
}
```

An example of a basic code block, with a title and a code frame

```powershell frame="code"
// files.ps1
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