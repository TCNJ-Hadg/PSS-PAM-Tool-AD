# PSS-PAM-Tool-

Import-Module Activedirectory
$users = Get-Content "c:\disableusers.txt"
For Each ($user in $users)
}
Disable_ADAccount -Identity $user
write-host "user $(user) has been disabled"
}

Powershell script

Import-Module Activedirectory
$users = Get-Content "c:\disableusers.txt"
For Each ($user in $users)
}
Disable_ADAccount -Identity $user
write-host "user $(user) has been disabled"
}
