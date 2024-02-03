
First set your exercism workspace path to this repository:

```shell
exercism configure --workspace /path/to/this/repository
```

The pull the exercism assignment to the GitHub repo you just cloned.

Note: If you do not set the workspace path correctly exercism files won't be placed in your GitHub repo folder on your machine.

Complete the following 20 easy level exercises and submit your code to both exercism and course GitHub classroom.

1. exercism download --track=cpp --exercise=hello-world
    - `cd hello-world`
    - complete the task
    - `mkdir build`
    - `cd build`
    - `cmake .. -D EXERCISM_RUN_ALL_TESTS=ON`
    - `make`
    - Pay attention to the test result and make sure all tests pass
    - `cd ..`
    - `exercism submit hello_world.cpp`
2. exercism download --track=cpp --exercise=lasagna
3. exercism download --track=cpp --exercise=last-will
4. exercism download --track=cpp --exercise=log-levels
5. exercism download --track=cpp --exercise=raindrops
6. exercism download --track=cpp --exercise=pacman-rules
7. exercism download --track=cpp --exercise=freelancer-rates
8. exercism download --track=cpp --exercise=vehicle-purchase
9. exercism download --track=cpp --exercise=interest-is-interesting
10. exercism download --track=cpp --exercise=ellens-alien-game
11. exercism download --track=cpp --exercise=troll-the-trolls
12. exercism download --track=cpp --exercise=making-the-grade
13. exercism download --track=cpp --exercise=doctor-data
14. exercism download --track=cpp --exercise=atbash-cipher
15. exercism download --track=cpp --exercise=rotational-cipher
16. exercism download --track=cpp --exercise=difference-of-squares
17. exercism download --track=cpp --exercise=trinary
18. exercism download --track=cpp --exercise=luhn
19. exercism download --track=cpp --exercise=hexadecimal
20. exercism download --track=cpp --exercise=allergies

Make sure to push your code to the GitHub classroom and check your final grade in the GitHub Action tab of the repo.

```shell
git add /path/to/your/project/repo
git commit -m "completed exercise xyz"
git push origin main
```

Good luck and happy coding!
