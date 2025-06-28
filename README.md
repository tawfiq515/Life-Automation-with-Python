# Life Automation with Python

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Automate your daily tasks with these Python scripts featuring email reminders and web monitoring.

## Features

- **Automated Email Reminders** - Get daily notifications sent to your inbox
- **Task Status Monitoring** - Automatic checks for overdue tasks
- **Flexible Scheduling** - Customize run times for each task
- **Error Resilient** - Handles network issues gracefully

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/life-automation.git
cd life-automation 

## Configure with your credentials:

Replace email/password in the script

Update ChromeDriver path

Customize task tracker URL and element IDs

Run the notebook or copy scripts to Python files

## Included Automations

Daily Email Reminder

Sends a fixed message at 9:00 AM daily

Uses SMTP with Gmail (requires app password)

Task Status Checker

Checks a task tracker website hourly

Sends alert if tasks are overdue

Requires ChromeDriver and Selenium

## Dependencies

Python 3.x

Selenium (for web automation)

Schedule (for task scheduling)

smtplib (built-in for email)

## Security Notes

Never commit actual credentials to code
Use app passwords instead of real email passwords
Consider environment variables for sensitive data

## Future Enhancements

Add more automation examples (calendar, expenses etc.)

Implement GUI for configuration

Add logging for debugging
