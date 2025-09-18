# 网站页面编辑教程
主要参考如下网站：[编辑网页](https://greene-lab.gitbook.io/lab-website-template-docs/basics/edit-pages)

## git clone本地修改网页
- 首先克隆项目到本地
  ```
  cd your_folder
  git clone git@github.com:SYSUSELab/sysuselab.github.io.git
  git remote add origin git@github.com:SYSUSELab/sysuselab.github.io.git
  ```
- 编辑你负责的页面
    - 假如负责Team页面，你需要进入到Team文件夹，如下图
    ![alt text](image-1.png)
    - 编辑index.md文件
  
      ![alt text](image-2.png)
    - 修改相应文本
    ![alt text](image-3.png)
    - 提交
        ```
        git add team\index.md
        git commit -m "提交team主页修改"
        git push origin main
        ```
    - 返回到github仓库，若有相应的内容即可，等待2min左右即可在网页上看到内容
    ![alt text](image-4.png)
## 网页上修改
- 打开你要修改的文件
    ![alt text](image-5.png)
- 点击那个笔按钮即可修改
    ![alt text](image-6.png)
- 右上角提交即可
    ![alt text](image-7.png)