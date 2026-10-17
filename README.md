Since you're starting Python and preparing for coding interviews at Google, let's build your logical thinking step by step, from very easy problems to beginner interview-level questions.

Don't try to solve everything at once. The goal is to understand how to think, not just how to write Python code.

# Python logical thinking practice roadmap

[Math blocks icon](https://images.openai.com/static-rsc-4/rZ3xwDsewvG0FTyk9093k0TDaV08gVi1B06OFYShjxoTXedJZynVDw9pc7xqmlI4TEwDMQWCYfu7gS1gcAZ_R3azNGnl2sB3YZBDFCvVNXwgAHgc_7sOlOU2f5cT7uDf1ttjREHyHbkxn-q4mNJvpUJcu1Zd-5Qz8jzHF3KsNeKWEL-JUenocOQFnkxCTcuG?purpose=inline)

Level 1: Basic logic

Start here

Learn conditions, comparisons, and arithmetic.

Questions 1–5

[Wayfair.com - Online Home Store for Furniture, Decor, Outdoors & More](https://images.openai.com/static-rsc-4/wg2Hn8w06qeSLzhlf5S0xzD3ibXimhdw3WLDcXKPnhHL5QST2c9MgUlx6DycHJcPwMHCgaqbq25QQcGGJMMzY4iMA5Owi7ZVT7vzzxft_nej8t3YJ-y9f4AgHd6vbdDcj8TVllgpreCN38ZrKgVTLXmZWxm_9s5KqWq9e4JKjOI?purpose=inline)

Level 2: Loops and numbers

Learn how to repeat operations and track values.

Questions 6–10

[alphabet blocks](https://images.openai.com/static-rsc-4/UPBkg13ipNfuzIzsGvxJzf0191WOyl0o5pHeo9hzqDHA7g_okAwQr2X5XqnD4tj6M8Bjc6wlceZtl0gfsNFeTKnSY5XoZgOahMpbnR6Ri_y56UC9NnLUUFcN--kkUGJijBIKYjWJB9809R4vLR3T_8pq8sDSkkJOtUi3WKDOCKvObgAr0ukxHQ3ZZgG7UR5V?purpose=inline)

Level 3: Strings and lists

Learn to process characters, numbers, and collections.

Questions 11–15

[Modern design illustration of coding maze](https://images.openai.com/static-rsc-4/_XNqvgIiOKS-lOTrszO0LJ8-ZUBd7Je3n7rUd83a_RExxUB8qBZ508957WZqTU7u9oZabp7zHuECOy7U8b3NHWHoRbSlhppnoQJseSMvO0O5WOal4bpMkV3prR3S_-XdWbpVim1TyUm2fDHNAJchieOs4R-2ODxlvKeLTDEvnm-ldyMmux7B0mX9AVA5EzMY?purpose=inline)

Level 4: Interview logic

Learn problem-solving patterns used in coding interviews.

Questions 16–20

## Level 1 — Start with these 5 questions

Try to solve these in order. You don't need advanced Python knowledge.

QUESTION 1

Even or odd

Given an integer, determine whether it is even or odd.

Example: `number = 7`

Expected output: `Odd`

Hint: Think about the remainder when dividing by 2.

QUESTION 2

Find the largest of two numbers

Given `a = 12` and `b = 8`, find the larger number.

Expected output: `12`

Hint: Which comparison operator can you use?

QUESTION 3

Positive, negative, or zero

Given `number = -5`, identify whether the number is positive, negative, or zero.

Expected output: `Negative`

Hint: You will need `if`, `elif`, and `else`.

QUESTION 4

Find the largest of three numbers

Given `a = 15`, `b = 27`, and `c = 19`, find the largest number.

Expected output: `27`

Hint: Compare the numbers instead of simply printing the known answer.

QUESTION 5

Check a leap year

Given a year, determine whether it is a leap year.

Example: `year = 2024`

Expected output: `Leap year`

Hint: Think about divisibility by 4, 100, and 400.

## Level 2 — Loops and number logic

Once you finish Level 1, try these.

| No. | Problem                                | Example               |
| --- | -------------------------------------- | --------------------- |
| 6   | Print numbers from 1 to N              | `N = 5` → `1 2 3 4 5` |
| 7   | Find the sum of numbers from 1 to N    | `N = 5` → `15`        |
| 8   | Calculate the factorial                | `5` → `120`           |
| 9   | Reverse a number                       | `1234` → `4321`       |
| 10  | Check whether a number is a palindrome | `121` → `True`        |

## Level 3 — Strings and lists

| No. | Problem                                 | Example                      |
| --- | --------------------------------------- | ---------------------------- |
| 11  | Reverse a string                        | `"python"` → `"nohtyp"`      |
| 12  | Count vowels in a string                | `"apple"` → `2`              |
| 13  | Find the largest number in a list       | `[4, 9, 2, 7]` → `9`         |
| 14  | Find the second-largest distinct number | `[4, 9, 2, 7]` → `7`         |
| 15  | Remove duplicates from a list           | `[1, 2, 2, 3]` → `[1, 2, 3]` |

## Level 4 — Beginner interview problems

| No. | Problem                                      | What you learn       |
| --- | -------------------------------------------- | -------------------- |
| 16  | Check if a string is a palindrome            | Two-pointer thinking |
| 17  | Find two numbers that add up to a target     | Hash maps / Two Sum  |
| 18  | Find the missing number in a sequence        | Number patterns      |
| 19  | Find the first non-repeating character       | Frequency counting   |
| 20  | Find the maximum sum of a subarray of size K | Sliding window       |

These last problems will help prepare you for technical interviews, including Google-style coding questions.

## Let's solve them interactively

We'll use the same method that works well for learning logic: one question at a time, hints before solutions, and feedback on your reasoning.

## Your first challenge

Easy

You are given a list of numbers:

# [3, 8, 2, 10, 5]

Task: Find the largest number without using Python's built-in `max()` function.

Think about these questions:

1. What value should you initially store as the largest?
2. How will you compare each new number with it?
3. When should you update the stored largest value?

Your answer

I'll explain the logic in plain English first.

I'll try writing Python code.

Give me a small hint first.

Check my answer

My advice: Spend 15–20 minutes daily. For every problem, first understand the input and expected output, work through an example by hand, write the logic in plain English, and then convert it into Python. Don't rush into harder questions before you understand why your code works.
