# API-Testing-Python

## Overview
This repository demonstrates practical **API testing using Python**, covering all CRUD operations (GET, POST, PUT, DELETE).  
The scripts are designed to showcase sending, receiving, and validating API requests using the `requests` library and formatted JSON outputs.  


## Technologies Used
- Python 3
- `requests` library
- `json` module

## Scripts
| Script | Description |
|--------|-------------|
| `get_users.py` | Sends a GET request to fetch all users and prints the response in readable JSON format |
| `post_user.py` | Sends a POST request to create a new post and prints the response |
| `put_user.py` | Sends a PUT request to update an existing post and prints the response |
| `delete_user.py` | Sends a DELETE request to remove an existing post and prints the response |

## How to Run
1. Clone the repository:  
    ```bash
    git clone https://github.com/K-Canzater/API-Testing-Python.git
    ```
2. Navigate to the folder:  
    ```bash
    cd API-Testing-Python
    ```
3. Install dependencies:  
    ```bash
    pip install requests
    ```
4. Run any script:  
    ```bash
    python get_users.py
    ```

## Notes
- The scripts use [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com/) as a practice API.  
- Responses are **pretty-printed** using `json.dumps(..., indent=4)` for readability.  
- This repo demonstrates **core API testing concepts** suitable for QA portfolios or interview demonstrations.
