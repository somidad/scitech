
# PowerShell start location

If you want to start the PowerShell in a specific location (drive or folder), do as follows on Windows:

1. Go to `Documents` folder (in general, `%USERPROFILE%/Documents`)
2. Go to `PowerShell` folder. If not exists, create one
3. Open `profile.ps1` file with a text editor. If not exists, create one
4. Add the following:

```powershell
Set-Location <desired location>
```

**References**

1. [How do you set PowerShell's default directory?](https://stackoverflow.com/questions/32069265/how-do-you-set-powershells-default-directory)
