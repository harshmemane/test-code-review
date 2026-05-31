# Test file for AI code review

import os
import sys

password = "admin123"
api_key = "sk-1234567890abcdef"

def get_user(user_id):
    query = "SELECT * FROM users WHERE id = " + user_id
    return query

def calculate(x, y):
    result = eval(x + y)
    return result
                                                         
secret_password = "supersecret123"
user_input = input()
eval(user_input)
secret_password = "supersecret123"
user_input = input()
eval(user_input)
# New vulnerable code
admin_password = "password123"
db_query = "DELETE FROM users WHERE id = " + user_id
exec(user_input)
