- "first we create our folder for out project and name it as test1"

![image](https://github.com/user-attachments/assets/f0a26997-0a6c-49cc-ae54-9264c2e64c84)



- "After that, we will create a Git repository to let Git track and save the changes of the source code in test1. Once we create the folder, we will go into the test1 folder and run git init."

**
![image](https://github.com/user-attachments/assets/cd11fbae-e343-48ea-b3ec-e728fb83cff4)


**

- "try to command git status"

**
![image](https://github.com/user-attachments/assets/2816dc38-a355-42e2-a062-adf37f5cc675)

**

"This message appears because we just created a Git repository, and our test1 folder does not have any files yet. Let's create the index.html file and add some code to it."

** ![image](https://github.com/user-attachments/assets/629b07e7-69c9-4617-b160-2434e49dd4f0)
 **


- "after that try to put git status again it will show like this"
**
![image](https://github.com/user-attachments/assets/e76e83b1-4f5a-4015-b1c2-42e461e8ea93)

**

"git status shows that our index.html file is an Untracked file. This means the file is new and not saved in Git yet. It has not been committed before."

"Now, let's add our index.html code by using the following command:


![image](https://github.com/user-attachments/assets/84e11f4f-df24-4f44-9eea-84d141f5ab37)


"After that, try running git status. You will see:"
**
![image](https://github.com/user-attachments/assets/3e0f7532-556a-440c-8b32-430a5a48bf84)

**
"git status tells us that our index.html file is ready to be committed. The note in parentheses also guides us on how to remove the index.html file from staging back to unstage."

"Next, we will commit the code. The code that will be committed is the index.html file already in staging. Use the following command:

![image](https://github.com/user-attachments/assets/6fa2df65-8b07-4241-ad37-65ebf6703491)

The -m option is used to specify a commit message, which describes the changes made in the code.

"You will see output like this:

![image](https://github.com/user-attachments/assets/c37f9064-3ce8-49fc-a3e6-30cc509fb300)


"This means a new commit has been created. The 68191ae is the commit hash, which is a unique ID for that commit."

"After that, run git status, and you will see the following status:"

![image](https://github.com/user-attachments/assets/4fd059a7-a4a0-4729-bbc7-b9b531f88f99)



