1，	基本概念
AIDL的实现一共分为三部分，一部分是客户端，调用远程服务。一部分是服务端，提供服务。最后一部分，也是最关键的是AIDL接口，用来传递的参数，提供进程间通信。
2，	注意事项
①	Aidl文件与Java文件包名应当一致
②	服务端与客户端的aidl应当是同一个包名
③	AIdl接口方法最好使用类似于void setName(int name);

