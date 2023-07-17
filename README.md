### Challenge on finding the smallest number of cubes needed to fill the box.
You are given a box with integer dimensions length x width x height. You are also given a set of cubes whose sides are powers of 2, e.g. 1x1x1, 2x2x2, 4x4x4 etc.
You need to fill the box with cubes from the set.

Write a program that for a given box and given set of cubes can determine the smallest number of cubes needed to fill the box.

#### Usage
1. Clone the repository
2. Install ruby 3.2.2
3. Run the following commands to see the output:
    ```bash
    ./challenge < problems.txt
    ```
4. Expected output:
      ```bash
      1
      8
      1000
      -1
      9
      62
      59
      50070
      9
      ```

#### Solution
I tried the solution with comparing the volumes of for each cubes set.
Unfortunately, it didn't work for all the test cases.
Then I realized that the problem is different and it's more about taking any cubes from the sets and filling the box.
I played with solution that tried to cut the box into smaller boxes and fill them with cubes it didn't work at all.
The problem is that I don't know how to fill the box with cubes that will fit rest of the space. We need to know what is a shape and how to take the correct cubes to fill the shape or shapes as there might be non cube shapes.
