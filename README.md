# Final

<p align="center">
  <a href="https://github.com/HusseinHany/EDUFLOW"><img src="docs/banner.svg" width="100%" alt="EDUFLOW: a learning path lights up through a graph of courses, from Intro to Deep Learning."></a>
</p>

Single-file version of **EduFlow**, a personalized learning path generator in C++.

The maintained, modular version (separate headers and sources, Makefile and CMake) is in [EDUFLOW](https://github.com/HusseinHany/EDUFLOW).

## Fixes

The same fixes as in EDUFLOW are applied here: typing a letter where a number is expected no longer freezes the menus, closed input exits cleanly, saved courses load back correctly, the scheduler can't loop forever, and scores, stress levels, skill levels, hours and durations are checked.

## Files

| File | What it is |
| --- | --- |
| `Final` | The whole program in one C++ source file |
| `EduFlow(1).cpp` | The later revision: lists the saved students before loading one, saves after every change, and reloads students at startup |

## What's inside

The same parts as the modular project, in one file: `Course`, `Student`, `WeeklySchedule` and `ProgressReport`; an AVL tree, a binary search tree, a graph for prerequisites, a linked list and a stack; depth-limited search; a recommendation engine (`AIEngine`); a schedule generator; file storage; and a console interface.

## Build and run

```bash
g++ -std=c++17 -x c++ Final -o eduflow
./eduflow
```
