# GitHub Actions CI Project

## About
This is a simple Free and Open Source (FOS) project that demonstrates how to use *GitHub Actions* for Continuous Integration (CI).  
Whenever code is pushed or a pull request is created, tests run automatically.

## How It Works
1. script.py contains a simple function.
2. tests/test_sample.py checks if the function works correctly.
3. GitHub Actions (ci.yml) runs pytest automatically on every push.

## How to Use
- Clone the repo
- Run locally:
  ```bash
  pip install pytest
  pytest
