# Final

Single-file version of **EduFlow**, a personalized learning path generator in C++.

The maintained, modular version (separate headers and sources, Makefile and CMake) is in [EDUFLOW](https://github.com/HusseinHany/EDUFLOW).

## Known issues

This is the older version and is kept as it was. It still has problems that are fixed in EDUFLOW: typing a letter where a number is expected freezes the menus, saved courses fail to load back, and a course with more weekly hours than the timetable holds can freeze the scheduler.

## Files

| File | What it is |
| --- | --- |
| `Final` | The whole program in one C++ source file |
| `EduFlow(1).cpp` | A slightly different revision of the same file |

## What's inside

The same parts as the modular project, in one file: `Course`, `Student`, `WeeklySchedule` and `ProgressReport`; an AVL tree, a binary search tree, a graph for prerequisites, a linked list and a stack; depth-limited search; a recommendation engine (`AIEngine`); a schedule generator; file storage; and a console interface.

## Build and run

```bash
g++ -std=c++17 -x c++ Final -o eduflow
./eduflow
```
