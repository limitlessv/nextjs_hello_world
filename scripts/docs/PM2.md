[pm2 cheatsheet](https://devhints.io/pm2)

pm2 not start after restart

https://github.com/Unitech/pm2/issues/4556

I found it !
make sure you specify the user after the startup option

```
pm2 startup -u nodeuser
```

in our case

```
pm2 startup -u ubuntu
```

> it will ask you to run a script
