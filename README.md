# Get-ProtectedVMList
Returns a list of virtual machines protected by SRM

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
