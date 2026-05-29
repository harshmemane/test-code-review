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
                                                         
