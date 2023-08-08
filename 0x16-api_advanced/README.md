Api_advanced

This repository contains Python scripts for interacting with the Reddit API to perform various tasks using the "praw" library. Each script is designed to demonstrate different functionalities of the Reddit API.

## Table of Contents

- [Task 0: How many subs?](#task-0-how-many-subs)
- [Task 1: Top Ten](#task-1-top-ten)
- [Task 2: Recurse it!](#task-2-recurse-it)

## Task 0: How many subs?

Write a function that queries the Reddit API and returns the number of subscribers for a given subreddit. If the subreddit is invalid, return 0.

**File:** [0-subs.py](./0-subs.py)

## Task 1: Top Ten

Write a function that queries the Reddit API and prints the titles of the first 10 hot posts for a given subreddit. If the subreddit is invalid, print None.

**File:** [1-top_ten.py](./1-top_ten.py)

## Task 2: Recurse it!

Write a recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit. If no results are found, return None.

**File:** [2-recurse.py](./2-recurse.py)

## Usage

To use these scripts, follow these steps:

1. Clone this repository: `git clone https://github.com/tolulope-web/alx-system_engineering-devops.git`
2. Navigate to the `0x16-api_advanced` directory: `cd alx-system_engineering-devops/0x16-api_advanced`

For each task, you can run the respective script with the desired subreddit as an argument:

```sh
python 0-subs.py programming
python 1-top_ten.py programming
python 2-recurse.py programming
```

## Author

- **Author:** Ajayi Tolulope
- **GitHub:** [tolulope-web](https://github.com/tolulope-web)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
```
