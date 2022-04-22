when you create stash ?

you change some file but now you need to pull code from origin 
other persone change same file , & now your local also write someting 
that time you need to create stash 
stash means all code you copy and after pulling form origin you paste all those file that you create in stash command 
you might see this error , 

```
error: cannot pull with rebase: You have unstaged changes.
error: please commit or stash them.
```

- check stash list command 
```
    git stash list 
```

- now you have empty stash list , nothing show on there, if you try first time .

- now we are going to create stash list by this command 
```
    git stash
```

- now check stash list by this command 
```
    git stash list
```
- wow have someting but i don't seen this file , that i create previously , 
- yes , those file have inside this stash 
- now you can pull from origin , so pull it 
- then you need to paste code from stash by this command 

```
    git stash apply
```

### that is done , now you know everyting about stash 

# but better way to do same thing 
- when create stash set a message with it by this command 
```

```









