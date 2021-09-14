# performance-analysis-test
This project is a small task to get someone to understand very basic profiling, performance analysis, and bottleneck finding techniques.

Here, you wont find lessons on how to analyze performance. Yet, you will be forced to search for ones if you want to finish this task.

The goal is to find the bottlenecks in the code. (NOT TO FIX THEM AS THEY ARE NOT FIXABLE ON PURPOSE)
The code is simple java code with static methods calling other static methods in the same project or from some jar.
DO NOT observing the referenced jar archive.

To get started:
- Clone the repo
- Open in intellij
- Import a gradle project
- Make sure it compiles and run without errors

You will start with this message when running the ```BottleNeckHunt.main``` method for the first time : ```The code has some bottleneck(s)```

You will be receiving hints in the console depending on how you are approaching the problem.

You should get this message if you find the bottlenecks.
```You got me!```

Or this message if you are close
```You are nearly there! ```

Moreover, you should be able to profile and analyse the code and the time taken by each code section. Find below an example of a good profiling of the code in this task.

Note: These numbers may vary according to the machine specifications and the business of the OS.

![Screen Shot 2021-09-14 at 12 15 29 PM](https://user-images.githubusercontent.com/18014563/133240210-3ad58bb8-7c74-412d-a4a2-e375ceeec84c.png)
![Screen Shot 2021-09-14 at 12 15 41 PM](https://user-images.githubusercontent.com/18014563/133240029-bb487095-1fd0-4c0e-82f2-1d5aa213a4f8.png)
