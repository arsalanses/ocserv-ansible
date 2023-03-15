Add user
```
docker exec -ti ocserv ocpasswd -c /etc/ocserv/ocpasswd testUserName
```

Change user password
```
docker exec -ti ocserv ocpasswd -c /etc/ocserv/ocpasswd testUserName
```

Delete user
```
docker exec -ti ocserv ocpasswd -c /etc/ocserv/ocpasswd -d testUserName
```

Show all users and their hashed password
```
docker exec -ti ocserv cat /etc/ocserv/ocpasswd
```
