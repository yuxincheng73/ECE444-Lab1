# Yu Xin Cheng

After making c1, c2 on rebase branch and c3, c4 on develop branch, I called "git rebase rebase" on develop branch. 
![image](https://user-images.githubusercontent.com/50343180/133946530-ed4bdc9b-d1aa-437d-81a7-e2a7a4f16233.png)

Then I have to reorder the commits so that c1 and c2 are after c3 and c4. I used "git rebase -i HEAD~4" and in vim, I reordered the commits accordingly. 
![image](https://user-images.githubusercontent.com/50343180/133947387-ff102d6b-2bab-4ef7-9305-becbe11531ec.png)

Here is the final git log:
![image](https://user-images.githubusercontent.com/50343180/133946694-fa5953e4-b294-4d98-b935-7a315887ba6b.png)




