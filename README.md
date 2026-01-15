# linux notes

My personal notes and tips for linux

## Ubuntu
### Update snap store
The snap store update fails because its running during the update.

Execute the following commands to update the snap

```bash
killall snap-store
sudo snap refresh
```
