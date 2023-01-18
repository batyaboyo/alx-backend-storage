# 0x0B. Redis basic

## Description

In this project project I practised Redis  basic in the tasks I did.:

---

Tasks
+ [x] [0. Writing strings to Redis](./exercise.py)

* Create a Cache class. In the \_\_init__ method, store an instance of the Redis client as a private variable named _redis and flush the instance using flushdb.

+ [x] [1. Reading from Redis and recovering original type](./exercise.py)

* Redis only allows to store string, bytes and numbers (and lists thereof). Whatever you store as single elements, it will be returned as a byte string. Hence if you store "a" as a UTF-8 string, it will be returned as b"a" when retrieved from the server.

+ [x] [2. Incrementing values](./exercise.py)

* Familiarize yourself with the INCR command and its python equivalent.

+ [x] [3. Storing lists](./exercise.py)

* Familiarize yourself with redis commands RPUSH, LPUSH, LRANGE, etc.

+ [x] [4. Retrieving lists](./exercise.py)

* In this tasks, we will implement a replay function to display the history of calls of a particular function.

+ [x] [5. Implementing an expiring web cache and tracker](./web.py)

* In this tasks, we will implement a get_page function. The core of the function is very simple. It uses the requests module to obtain the HTML content of a particular URL and returns it.
