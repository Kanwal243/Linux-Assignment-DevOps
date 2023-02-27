# Linux-Assignment-DevOps Kanwal
>TASKS
```
Find out operating system you are running using command & top 3 services using memory & CPU.
```

![assign](https://user-images.githubusercontent.com/83213183/221673238-749ca03b-170e-4e99-ba60-180777098e5a.PNG)

Top 3 services using memory & CPU 

# sudo top
1 - To check the memory and CPU usage of all running services:

![Sudo top](https://user-images.githubusercontent.com/83213183/221676860-c3bde3ee-6afb-4bbd-8c4d-c114208f00c7.PNG)

# sudo ps aux --sort=-%mem | head -n 4
2 - To check the top memory-consuming processes:

![1](https://user-images.githubusercontent.com/83213183/221677325-c6cbd09f-387b-4710-b339-adf1f3fb6f20.PNG)

# sudo ps aux --sort=-%cpu | head -n 4
3 - To check the top CPU-consuming processes:
![image](https://user-images.githubusercontent.com/83213183/221678734-7099a63d-085e-46e0-86ca-6fffb4cd119a.png)



