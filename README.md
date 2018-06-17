# Threading-in-Python

In these example we test the performance increase we get by using threads.
Note that in python only one thread can run at a given time so the benefits we have in this example occurs because of the time.wait.
Where there is a wait in one thread the other starts to work!
These is why threads are used when performing I/O task.



![without_thread](https://user-images.githubusercontent.com/21143253/41505828-cdcf1d48-7219-11e8-8d2d-408040c485ce.png)
![with_threading](https://user-images.githubusercontent.com/21143253/41505829-ce07fdfc-7219-11e8-9935-506e0b6b9e88.png)
