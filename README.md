# About Dedicated Server Script
The script allows you to manage servers.

## How it work?

We must go to [line](https://github.com/TouchMe-Inc/l4d2_ds_script/blob/f26954af1602b97262988f4e5f374d236f8695b6/srcds#L36) and specify our parameters:
* Path to server
* Server IP:PORT
* Server params


After this, you can use the commands:
```
./srcds -a <start|stop|restart|status|update|console> -n <server number>
```

For example:
```
./srcds -n 1 -a status
```
```
./srcds -n 1 -a start
```
```
./srcds -n 1 -a stop
```

## Attention
All commands are executed on behalf of an authorized user. The user must have the right to run the script and servers.
