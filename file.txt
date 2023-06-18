import os

directory_name = "merge"

try:
    os.mkdir(directory_name)
    print(f"Directory '{directory_name}' created successfully.")
except OSError as error:
    print(f"Failed to create directory '{directory_name}': {error}")
