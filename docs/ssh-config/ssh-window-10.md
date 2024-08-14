[Setting up SSH-Agent in Windows for Passwordless Git Authentication](https://interworks.com/blog/2021/09/15/setting-up-ssh-agent-in-windows-for-passwordless-git-authentication/)

Using an elevated PowerShell window (run as admin), execute the following command to install the SSH-Agent service and configure it to start automatically when you log into your machine:

```powershell
Get-Service ssh-agent | Set-Service -StartupType Automatic -PassThru | Start-Service
```
**Setting up an SSH Key Pair to Access a Git Remote Provider**

**Adding the SSH Key to the SSH-Agent Service**
```powershell
ssh-add C:\Users\tan.trinh/.ssh\tantrinh.tpf.dev
```
