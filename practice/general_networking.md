## General Networking

####Question 1

This question consist on displaying network information for your workstation. You can read more in *6.2 Network configuration commands*:


---

Introduce the command necessary to display the IP address. If you don't know the solution feel free to press solution to see the right answer:

```js
var IP_address =
```

```js
var IP_address= ip addr show;
```

```js
assert(IP_address == ip addr show);
```

```js
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
```

---


---

Now type the command you should use to display the IP route.

```js
var IP_route =
```

```js
var IP_route= ip route show;
```

```js
assert(IP_route == ip route show);
```

```js
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
```

---

---

Finally introduce the command that shows the nameserver.

```js
var Serv=
```

```js
var Serv= hostname;
```

```js
assert(Serv== hostname);
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

Suppose no DNS is available. What would you do to reach your neighbour's machine without typing the IP address all the time?:

- [x] Edit /etc/hosts file.
- [ ] Use `ifconfig` command.

> If you use the ifconfig command,you will need to type the Ip address often, and that's what we want to avoid. For more info of how to edit hosts file visit chapter *6.2 Network configuration files*.



---


####Question 3


---

How would you permanently store proxy information for a text mode browser such as links?:

- [ ] use chmod to change proxy servers permission.
- [x] edit your ~/.bashrc with a `export` line.

> You can find the answer in *7.3.1 proxy servers*.



---


####Question 4

---

Does your machine run a web server?How to check it?:

- [ ] I check if /etc/httpd file exits.
- [x] I check it using `ps `.

> Go to *7.2.1 Server types* for more info .



---

####Question 5



---

You want to send to *member1@erlerobot.com* a mail containing the *doc.txt* file.Please, enter the command line for doing this. You can find help in *7.4 Mail*. If you don't know press solution.

```js
var command_line=
```

```js
var command_line= mail member1@erlerobot.com < doc.txt;
```

```js
assert(command_line= mail member1@erlerobot.com < doc.txt);
```

```js
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
```

---

