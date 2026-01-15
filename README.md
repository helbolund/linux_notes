# linux notes

My personal notes and tips for linux

[[_TOC_]]

## Ubuntu
### Update snap store
The snap store update fails because its running during the update.

Execute the following commands to update the snap

```bash
killall snap-store
sudo snap refresh
```
