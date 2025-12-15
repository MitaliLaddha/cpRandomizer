# CP Randomizer

A personalized competitive programming tool designed to help users improve by systematically increasing problem difficulty.

## Project Overview
This tool automates the process of finding Codeforces problems for practice. It fetches the user's current rating via the Codeforces API and selects a problem rated 200 points higher to ensure progressive overload.

## Features
- **Dynamic Difficulty:** Calculates target rating based on real-time user data.
- **Smart Filtering:** Rounds target ratings to the nearest 100 to match valid Codeforces problem difficulties.
- **Latency Optimization:** Pre-fetches the problem set in the background to minimize wait times.

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6+)
- Codeforces API

## How to Use
1. Open the application.
2. Enter your Codeforces handle.
3. The tool will display your current rating, calculate the target difficulty, and provide a direct link to a random problem.