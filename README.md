# gcloud-git-sync

```
cd /home/tqviet1978
git clone https://github.com/viettranme/gcloud-git-sync.git
cp Hello/platforms/android/app/build/outputs/apk/debug/app-debug.apk gcloud-git-sync/
cd gcloud-git-sync
git add app-debug.apk 
git config --global user.email "vtq@vietmaisolutions.com"
git config --global user.name "Viet Tran"
git commit -m "X"
git push origin master
```
