---
author: brianlic-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: provcmdlets.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.author: brianlic
ms.date: 2017-05-09
ms.mktglfcycl: manage
ms.prod: w10
ms.sitesec: library
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Export-ProvisioningPackage
---

# Export-ProvisioningPackage

## SYNOPSIS
{{Fill in the Synopsis}}

## SYNTAX

### Id
```
Export-ProvisioningPackage -PackageId <String> [-OutputFolder] <String> [-AllowClobber] [-AnswerFileOnly]
 [-LogsDirectoryPath <String>] [-WprpFile <String>] [-ConnectedDevice]
```

### Path
```
Export-ProvisioningPackage [-PackagePath] <String> [-OutputFolder] <String> [-AllowClobber] [-AnswerFileOnly]
 [-LogsDirectoryPath <String>] [-WprpFile <String>] [-ConnectedDevice]
```

### Metadata
```
Export-ProvisioningPackage [-RuntimeMetadata] <RuntimeProvPackageMetadata> [-OutputFolder] <String>
 [-AllowClobber] [-AnswerFileOnly] [-LogsDirectoryPath <String>] [-WprpFile <String>] [-ConnectedDevice]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AllowClobber
{{Fill AllowClobber Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: Force, Overwrite

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AnswerFileOnly
{{Fill AnswerFileOnly Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConnectedDevice
{{Fill ConnectedDevice Description}}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: Device

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LogsDirectoryPath
{{Fill LogsDirectoryPath Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: Logs

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OutputFolder
{{Fill OutputFolder Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: Out

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PackageId
{{Fill PackageId Description}}

```yaml
Type: String
Parameter Sets: Id
Aliases: Id

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PackagePath
{{Fill PackagePath Description}}

```yaml
Type: String
Parameter Sets: Path
Aliases: Path

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RuntimeMetadata
{{Fill RuntimeMetadata Description}}

```yaml
Type: RuntimeProvPackageMetadata
Parameter Sets: Metadata
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -WprpFile
{{Fill WprpFile Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: Wprp

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### Microsoft.Windows.Provisioning.ProvCommon.RuntimeProvPackageMetadata


## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

