# 同步与异步

同步（synchronize, sync）：指一个进程在执行某个请求时，若该请求需要一段时间才能返回信息，
那么，这个进程将会一直等待下去，直到收到返回信息才继续执行下去，
比如两个人打电话

异步（asynchronous, async）：指进程不需要一直等下去，而是继续执行下面的操作，不管其他进程的状态，
当有消息返回时系统会通知进程进行处理，这样可以提高执行的效率，
比如两个人发短信