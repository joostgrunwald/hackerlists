# Tools
- prowler for scan https://github.com/prowler-cloud/prowler
- pingcastle azure module (doesn't find very much just yet)
- 
# monkey365
- Import-Module ./monkey365
$assets = Invoke-Monkey365 -ExportTo PRINT,HTML -PromptBehavior SelectAccount -IncludeAzureActiveDirectory -Instance Microsoft365 -Analysis 
$assets = Invoke-Monkey365 -ExportTo PRINT,HTML -PromptBehavior SelectAccount -IncludeAzureActiveDirectory -Instance Azure -Analysis All
SharePointOnline,ExchangeOnline,MicrosoftTeams,IRM 
https://silverhack.github.io/monkey365/configuration/microsoft365-options/
https://silverhack.github.io/monkey365/configuration/azure-options/

# scuba 
PS C:\Users\joost\Downloads\ScubaGear-0.3.0> Import-Module -Name .\PowerShell\ScubaGear <br>
PS C:\Users\joost\Downloads\ScubaGear-0.3.0> Invoke-SCuBA

# Things to check
- which blobs are open
- CA, compliance policies
- are secure standards on?
- version checks of devices
- secure score
- legacy auth disabled? legacy auth in logs?
