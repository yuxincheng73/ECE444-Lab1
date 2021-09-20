# Yu Xin Cheng

After making c1, c2 on rebase branch and c3, c4 on develop branch, I called "git rebase rebase" on develop branch. 
![image](https://user-images.githubusercontent.com/50343180/133946530-ed4bdc9b-d1aa-437d-81a7-e2a7a4f16233.png)

Then I have to reorder the commits so that c1 and c2 are after c3 and c4. I used "git rebase -i HEAD~4" and in vim, I reordered the commits accordingly. 
![image](https://user-images.githubusercontent.com/50343180/133947905-e95e1df2-dcb8-440b-8a62-f24066d81935.png)

Here is the final git log:
![image](https://user-images.githubusercontent.com/50343180/133947950-01cfe8ed-139f-4771-aec4-44bdb8177661.png)




