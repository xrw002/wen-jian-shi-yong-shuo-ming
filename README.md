在命令行上创建一个新的存储库
````
echo "# -" >> README.md 
git init 
git add README.md 
git commit -m "第一次提交" 
git branch -M main 
git remote add origin git@github.com:xrw002/-.git
git push -u origin main
````
...或者从命令行推送现有的存储库
```
git remote add origin git@github.com:xrw002/-.git
git branch -M main 
git push -u origin main
````
