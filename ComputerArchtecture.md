## 阅读笔记

> decode

解码相应的指令

> dispatch

dispatch阶段将已经decoded的指令发送到issue队列中，此时指令所需的操作数不一定准备就绪

> issue 

当队首指令所有的操作数都准备就绪时，将队首指令issue到执行单元

> execute

执行到来的指令

> retire

解放执行完毕的指令，将值写回