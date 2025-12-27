I made an autoclicker based purely in powershell that can be imported and used. It offers a changeable CPS, as well as the option for randomization.

powershell Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass && powershell Invoke-Expression (Invoke-RestMethod https://raw.githubusercontent.com/praiselily/AutoClicker/refs/heads/main/LilithClicker.ps1)
