Redis Basic Operations and Caching with Python

This repository contains implementations of basic Redis operations and caching techniques using Python. It includes solutions to various tasks such as storing data, recovering original data types, counting method calls, and implementing a simple web cache with Redis.
Table of Contents

    Overview
    Features
    Installation
    Usage
    Tasks
    Learning Objectives
    Resources
    Contributing
    License

Overview

Redis is a fast, open-source, in-memory key-value data store used for caching, real-time analytics, and as a message broker. This project demonstrates how to use Redis to store and retrieve data, count method calls, track inputs/outputs for functions, and implement an expiring web cache.
Features

    Basic Redis operations such as storing and retrieving strings, integers, and other types.
    Tracking function call counts and storing input/output history using Redis.
    Implementing a simple web cache that stores the HTML content of web pages with an expiration time.
    Use of Python decorators for enhanced functionality (e.g., counting function calls, storing call history).

Installation
Prerequisites

    Python 3.7 or later
    Redis server installed locally or running in a container

Steps

1.Clone the repository:
git clone https://github.com/busayo524/alx-backend-storage.git
cd alx-backend-storage/0x02-redis_basic
2.Install Redis server (on Ubuntu 18.04):
sudo apt-get update
sudo apt-get install redis-server
3.Install Redis Python client:
pip3 install redis
4.Start the Redis server:
sudo service redis-server start

Usage

Run the Python scripts provided in the repository to interact with Redis:
1.Store data and retrieve it:
python3 main.py

2.Count method calls and retrieve input/output history:
python3 call_history.py

3.Use the web cache:
python3 web.py

Tasks
0. Writing Strings to Redis

    File: exercise.py
    Implements a Cache class that stores and retrieves data from Redis using a random key.

1. Reading from Redis and Recovering Original Type

    File: exercise.py
    Adds methods to retrieve and convert Redis-stored data back to its original type (string, integer).

2. Incrementing Values

    File: exercise.py
    Implements a count_calls decorator to track the number of times a method is called.

3. Storing Lists

    File: exercise.py
    Adds a call_history decorator that stores input/output of methods in Redis.

4. Retrieving Lists

    File: exercise.py
    Implements a replay function to retrieve and display the history of method calls.

5. Expiring Web Cache

    File: web.py
    Implements a caching system for web pages with a 10-second expiration.

Learning Objectives

    Use Redis for basic data operations.
    Implement Redis as a simple caching solution.
    Understand Python decorators and how they can be used to track method calls and store input/output history.
    Implement a basic web page caching system with Redis.

Resources

    Redis Crash Course Tutorial
    Redis Commands
    Redis Python Client
    How to Use Redis With Python

Contributing

Contributions are welcome! If you'd like to contribute, feel free to create a pull request or raise an issue.

License

This repository is licensed under the MIT License. See the LICENSE file for more information.
