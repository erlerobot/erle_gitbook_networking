## Security

####Question 1


---

Type the command line to make a list of open (listening) ports on your machine.For more clues, you can read *9.1 Secure services and security tips*.Nevertheless you don't know, select solution to see the correct answer.

```js
var Command_line =
```

```js
var Command_line= netstat -l | grep tcp;
```

```js
assert(Command_line == netstat -l | grep tcp);
```

```js
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
```

---


####Question 2
---

How can you see who connected to your system?:

- [x] using the comman `who`
- [ ] using the command `traceroute` for following a packet

> You can know more about `who` command in the man page.



---

####Question 3
---
Using Iptables we want to let the packages just go through this system to be routed. Which command line is the correct one? :

- [ ] iptables -t filter -P FORWARD ACCEPT
- [x] iptables -t filter -P FORWARD DROP

> Read more in *9.2.2.2 Orders and parameters*




---
