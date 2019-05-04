---
external help file: Az.Network-help.xml
Module Name: Az.Network
online version: https://docs.microsoft.com/en-us/powershell/module/az.network/get-azhubvirtualnetworkconnection
schema: 2.0.0
---

# Get-AzHubVirtualNetworkConnection

## SYNOPSIS
Retrieves the details of a HubVirtualNetworkConnection.

## SYNTAX

### ListSubscriptionIdViaHost (Default)
```
Get-AzHubVirtualNetworkConnection -ResourceGroupName <String> -VirtualHubName <String>
 [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### GetSubscriptionIdViaHost
```
Get-AzHubVirtualNetworkConnection -ConnectionName <String> -ResourceGroupName <String> -VirtualHubName <String>
 [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### Get
```
Get-AzHubVirtualNetworkConnection -ConnectionName <String> -ResourceGroupName <String> -SubscriptionId <String>
 -VirtualHubName <String> [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### List
```
Get-AzHubVirtualNetworkConnection -ResourceGroupName <String> -SubscriptionId <String> -VirtualHubName <String>
 [-DefaultProfile <PSObject>] [<CommonParameters>]
```

## DESCRIPTION
Retrieves the details of a HubVirtualNetworkConnection.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -ConnectionName
The name of the vpn connection.

```yaml
Type: System.String
Parameter Sets: GetSubscriptionIdViaHost, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
The resource group name of the VirtualHub.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The subscription credentials which uniquely identify the Microsoft Azure subscription.
The subscription ID forms part of the URI for every service call.

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VirtualHubName
The name of the VirtualHub.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IHubVirtualNetworkConnection
## NOTES

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/az.network/get-azhubvirtualnetworkconnection](https://docs.microsoft.com/en-us/powershell/module/az.network/get-azhubvirtualnetworkconnection)
