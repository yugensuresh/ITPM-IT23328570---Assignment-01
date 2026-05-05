IT3040-ITPM: Assignment 1 - Option 1
Transliteration Accuracy Testing (Singlish to Sinhala)

IT23328570: Yugen S
Assignment Option: Option 1 (Transliteration Accuracy Testing)

Project Overview

This project evaluates the accuracy of the Singlish-to-Sinhala chat translator available at [pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator). It contains 50 negative test cases designed to identify failures in chat-style transliteration across 24 specific input types.

Prerequisites

Before running the scripts, ensure you have the following installed:
Python 3.11 or 3.12
Google Chrome (installed via Playwright)

Installation Instructions

1. Navigate to the project terminal:

python IT23328570_test_automation.py --excel "IT23328570/IT23328570.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 10000 --type-delay-ms 120 --timeout-ms 90000 --save-every 1 --keep-open