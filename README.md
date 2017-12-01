This is a PowerShell function. Returns a list of virtual machines protected by SRM.<br>

*Blog Post*<br>
[List SRM Protected VMs with PowerCLI](http://vmkdaily.ghost.io/get-list-of-srm-protected-vms-with-powercli/)

*Help Output*<br>

```
NAME
    Get-ProtectedVMList
    
SYNOPSIS
    Returns a list of virtual machines protected by SRM.
    
    
SYNTAX
    Get-ProtectedVMList [-PassThru] [<CommonParameters>]
    
    
DESCRIPTION
    Returns a list of virtual machines protected by SRM. Also includes SRM detail for each
    protected virtual machine.  Optionally, use the PassThru switch to return virtual machine
    objects instead.
    
    By default, we return the following properties (unless using PassThru):
    
    MoRef
    ProtectedVm
    PeerProtectedVm
    State
    PeerState
    NeedsConfiguration
    ProtectionGroup
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-ProtectedVMList -examples".
    For more information, type: "get-help Get-ProtectedVMList -detailed".
    For technical information, type: "get-help Get-ProtectedVMList -full".

```
