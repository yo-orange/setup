```bash:install
winget install Microsoft.VisualStudioCode -l D:/tools/vscode
winget install Git.Git -l D:/tools/git
winget install --id Google.Chrome --force --silent
# winget install 7zip.7zip -l D:/tools/7zip
winget install --id Microsoft.OpenJDK.17
# "C:\Program Files\Microsoft\jdk-17.0.2.8-hotspot"
wget https://github.com/mzyy94/RictyDiminished-for-Powerline/archive/refs/tags/3.2.4-powerline-early-2016.zip -O 3.2.4-powerline-early-2016.zip
# https://nelog.jp/how-to-use-ricty-diminished-font
# http://monolog.lsv.jp/font-rictydiminished/
https://hosopro.blogspot.com/2017/01/powershell-set-environment-variable.html#:~:text=%E4%B8%80%E6%99%82%E7%9A%84%E3%81%AB%E7%92%B0%E5%A2%83%E5%A4%89%E6%95%B0,%E3%82%92%E8%A8%AD%E5%AE%9A%E3%81%99%E3%82%8B%E3%81%A0%E3%81%91%E3%81%A7%E3%81%99%E3%80%82&text=PS%20C%3A%5Cwork%3E%20%24env,%E3%82%92%E8%A8%AD%E5%AE%9A%E3%81%97%E3%81%A6%E3%81%84%E3%81%BE%E3%81%99%E3%80%82
[System.Environment]::SetEnvironmentVariable("JAVA_HOME", "C:\Program Files\Microsoft\jdk-17.0.2.8-hotspot", "Machine")
# 環境変数設定例
# PS C:\work> $oldSystemPath = [System.Environment]::GetEnvironmentVariable("Path", "Machine")
# PS C:\work> $oldSystemPath += ";c:\work"
# PS C:\work> [System.Environment]::SetEnvironmentVariable("Path", $oldSystemPath, "Machine")
winget install --id Microsoft.PowerAutomateDesktop -l D:/tools/PowerAutomateDesktop
winget install --id SlackTechnologies.Slack
winget install --id Google.Drive
```

# Java
- https://tech-lab.sios.jp/archives/19941
```bash:spring
code --install-extension vscjava.vscode-java-pack
code --install-extension pivotal.vscode-boot-dev-pack
```

# Git
```
$ git config --global user.name "name"
$ git config --global user.email "email"
$ git config --global core.autocrlf false
```
