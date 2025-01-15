# Time Tracker in Rust

## Overview
The Time Tracker CLI application is a Rust-powered tool designed to help users track and report time spent on various tasks. 

## Key Features

### Start Tracking
Begin tracking time for a task:
```bash
timetracker start "Writing Code"
```

### Stop Tracking
Stop the current task:
```bash
timetracker stop
```

### View Logs
Display time spent on tasks for the day, week, or month:
```bash
timetracker log
```

### Report Generation
Generate a detailed report of time spent on each task:
```bash
timetracker report --weekly
```

### Tagging Tasks
Add tags to tasks for better categorization:
```bash
timetracker start "Meeting" --tags "work, team"
```

### Export Data
Export logs for external analysis in CSV format:
```bash
timetracker export --format csv
```



