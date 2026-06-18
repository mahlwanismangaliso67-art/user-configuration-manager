# User Configuration Manager

A Python project that allows users to manage application settings such as themes, languages, and notifications.

## Features

- Add new settings
- Update existing settings
- Delete settings
- View current settings
- Automatic lowercase formatting for keys and values

## Technologies Used

- Python

## Project Objective

This project was completed as part of the freeCodeCamp Python curriculum.

## Example

```python
settings = {
    "theme": "light"
}

add_setting(settings, ("language", "english"))
update_setting(settings, ("theme", "dark"))

print(settings)