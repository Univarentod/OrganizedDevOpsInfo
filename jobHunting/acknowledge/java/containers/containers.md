[back to main menu](../../../../MainMenu.md)  

![containers](./containers_java.png)  

Deque没有isEmpty函数  
ArrayDeque：底层是用数组去存放数据  
LinkedList：底层用链表去存放数据  
forEach循环体的右侧实际上是调用了Iterable接口里默认的获得Iterator的函数，所以可以自己实现任意访问次序的Iterator放到那里  