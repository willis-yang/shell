## IOS Scheduled Task

### progress
```
ldid -S your-task
chmod +x  your-task
cp com.testing.plist /Library/LaunchDaemons/com.testing.plist
launchctl load -w /Library/LaunchDaemons/com.testing.plist
launchctl start com.testing
launchctl list |grep com.testing
```
### docs
[ios office doc](https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/CreatingLaunchdJobs.html#//apple_ref/doc/uid/10000172i-SW7-108425)