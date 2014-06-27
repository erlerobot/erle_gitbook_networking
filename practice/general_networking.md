## General Networking

####Question 1

Display network information for your workstation:


---

Display IP address.

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

Display IP route.

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

Display name servers.

```js
var Serv= hostname
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

- [x] Edit /etc/hosts file
- [ ] Use `ifconfig` command

> If you use the ifconfig command,you will need to type the Ip address often, and that's what we want to avoid. For more info of how to edit hosts file visit chapter 6.2 *Network configuration files*.



---


####Question 3


---

How would you permanently store proxy information for a text mode browser such as links?:

- [ ] use chmod to change proxy servers permission
- [x] edit your ~/.bashrc with a `export` line

> You can find the answer in 7.3.1 "proxy servers".



---


