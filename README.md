# IT23665002_ITPM-ASSIGNMEN01
# Test Automation UI

This project contains a Playwright automation test for checking image preview functionality in Pixelssuite.

## Install dependencies

python -m pip install -U pip
python -m pip install playwright openpyxl
python -m playwright install

## Run test

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
