# todo-list
原生js实现一个todo-list

主要功能：
1. 三列布局，左边是待办事项，中间是完成事项，右边是添加事项
2. 添加事项由标题和内容组成，并可以选择任务类型
3. 点击提交后，待办事项这一栏会出现任务。任务上面有完成和删除按钮
4. 点击任务的完成按钮，任务会出现在中间的完成事项栏。此时任务的只剩下删除按钮
5. 点击任务的删除按钮，任务直接被删除。

注意：
1. 对于待办事项并没有做持久化处理。所以一旦刷新页面，任务会全部消失
2. 布局采用浮动方式实现。

整体界面
![todo-list](https://github.com/windofme1109/todo-list/blob/master/img/todo-list_2.png)

添加事项
![add-event](https://github.com/windofme1109/todo-list/blob/master/img/add.png)

完成事项
![finish-event](https://github.com/windofme1109/todo-list/blob/master/img/finish.png)



