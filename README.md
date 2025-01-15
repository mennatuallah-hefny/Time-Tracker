# CLI Automation: Time Tracker in Rust

## Overview
The Time Tracker CLI application is a Rust-powered tool designed to help users effectively track and report time spent on various tasks. Whether you’re managing your personal projects or keeping tabs on your work hours, this app provides a seamless way to organize your time.

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

## Installation
1. Ensure you have [Rust](https://www.rust-lang.org/) installed on your system.
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/timetracker.git
   ```
3. Navigate to the project directory:
   ```bash
   cd timetracker
   ```
4. Build the project:
   ```bash
   cargo build --release
   ```

## Usage
1. Navigate to the directory containing the compiled binary:
   ```bash
   cd target/release
   ```
2. Start using the Time Tracker CLI:
   ```bash
   ./timetracker start "Your Task Name"
   ```


