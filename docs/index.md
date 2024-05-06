# Python functions naming: an algorithm
____
### The Motivation Part
Well, we all know that clear naming is crucial for readability.

Still, I see a function named `get_user` in every project. I renamed it to `fetch_user_from_db` in one project and to `clear_user_data` in another. As you can see, the functions had the same name but had nothing in common.

The most important part of a function name is a verb. The most popular verb is “get”, and it is a very lazy choice: it gives us none of the additional info. For example, you can replace “get” with “fetch”, then I would know that the function receives data from the network/disk.

Below you can see The Naming Algorithm: a connection between common verbs and their meanings. Use it for great good and forget about “get” and “process”.
### The Naming Algorithm
![image with algorithm](assets/img/full_image.jpeg)