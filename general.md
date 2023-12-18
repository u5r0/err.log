### [System limit for number of file watchers reached](https://github.com/gatsbyjs/gatsby/issues/11406)
- *diagnose:* `cat /proc/sys/fs/inotify/max_user_watches`
- **Fix:** `sudo sysctl fs.inotify.max_user_watches=524288`


