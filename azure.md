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

FOR LATER
- scoutsuite using venv ──(venv)─(fortifier㉿fortifier)-[~/ScoutSuite]
└─$ python3 scout.py azure --user-account-browser --subscriptions {tenid}

# Things to check
- which blobs are open
- CA, compliance policies
- are secure standards on?
- version checks of devices
- secure score
- legacy auth disabled? legacy auth in logs?
