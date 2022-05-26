# Howdy Interview Challenge

## Introduction
Welcome to the Howdy interview challenge. The goal of this challenge is to see a piece of your code as a basis for talking about your developer skills.

We would like you to implement your evaluation method in a language of your own choosing, eg. JavaScript, TypeScript, C# or something else.
Don't worry too much about the correctness, and please don't spend too much time. We intend for the challenge to take about one hour to complete. If you are not done after one hour, feel free to submit a partial solution.

## The challenge

Part of the Howdy mission is to monitor and evaluate the wellbeing of our users.
We regularly ask them questions about their wellbeing to see whether they thrive or need professional help.

Sometimes, we also need to evaluate how a group of people is doing (e.g. sports team, department, office).
Your goal is to find an evaluation technique, that based on the individual scores of people in the group, assigns a score to that group.

Please note that:
- Score should be evaluated on a monthly basis
- There can be multiple answers from an individual in a month
- Individual scores must remain confidential
- Score range is a decimal number from 0 to 5 inclusive

## Dataset
We ask users 5 questions in a single session, where each answer is an integer from 0 to 5 inclusive.
Each session consists of a `groupId`, `answeredOn` and answer scores `answer1` to `answer5`.
For the sake of simplicity, you can combine these 5 answers to a single value and use that in your method if you'd like.

We provide you a dataset of sessions in [answers.json](answers.json) file.

## Submission
Please send us a link to a public repo with the code (eg. on github or gitlab).
