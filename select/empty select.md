یه نکته‌ی جالب در مورد بلاک کردن cpu در go هست که میتونید بدون اینکه مصرف cpu رو به ۱۰۰درصد برسونید، آن را کاملا بلاک کنید: 

```go
select {}
```

همانطور که در [این لینک](https://stackoverflow.com/questions/18661602/what-does-an-empty-select-do) در stackoverflow توضیح داده شده:

![[Pasted image 20240720221943.png]]

