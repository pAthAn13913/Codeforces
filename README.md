# Codeforces Problem Solutions

This folder contains my solutions to Codeforces problems.

## About
- Each source file is named by problem ID and title.
- Most solutions are written in C/C++.
- This repository is used for practice and problem-solving history.

## Notes
- File names may follow different naming styles based on when the solution was added.
- Solutions are kept as submitted/practiced versions.

## Help
- Pick a problem file by its Codeforces ID.
- Compile and run locally to understand the approach.
- Compare different solved files to learn common patterns.

## Local Testing Setup
Use this snippet in C++ solutions for easier local testing and faster I/O:

```cpp
#ifndef ONLINE_JUDGE
	freopen("input.txt", "r", stdin);
	freopen("output.txt", "w", stdout);
#endif

ios_base::sync_with_stdio(false);
cin.tie(NULL);
cout.tie(NULL);
```

Purpose:
- `#ifndef ONLINE_JUDGE` block: On your local machine, it reads input from `input.txt` and writes output to `output.txt`. When submitted to an online judge, this block does not run.
- `ios_base::sync_with_stdio(false); cin.tie(NULL);`: Used for faster input/output, especially helpful for large input cases.
