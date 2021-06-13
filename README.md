#2 Project(thread-safety by semaphore)
20163364 김세한

1) semaphore
![image](https://user-images.githubusercontent.com/84447571/121805213-2b0e3480-cc85-11eb-89fa-6645f775a9ad.png)

2) mutex
![image](https://user-images.githubusercontent.com/84447571/121805224-437e4f00-cc85-11eb-9866-2e96d77e255e.png)


Result: Mutex's Performance time is fatser than Semaphore's Performance time 
MUtex has only two states(lock, unlocked)
Semaphore deosn't have a lock concept. 
Mutex prevents one Process or Thread from accessing data from shared resources or critical sections.
Semaphore prevents multiple processes or threads from accessing data from shared resources, such as critical sections.
So, Semaphore's Performance time is slower than Mutex's.
