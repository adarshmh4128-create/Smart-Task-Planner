LifeOS — AI Productivity Assistant

LifeOS is a personal AI productivity assistant designed to help students organize their daily lives, manage study schedules, prioritize tasks, and stay consistent with their goals.

It aims to make daily planning easier by creating realistic timetables based on available time, task priorities, fixed commitments, breaks, and energy levels.

🎯 Project Objective

The main goal of LifeOS is to help students become more organized and productive without feeling overwhelmed.

LifeOS can assist with:

- Daily timetable planning
- Task prioritization
- Study and revision planning
- DSA practice scheduling
- College assignments and deadlines
- Break and energy management
- Identifying tasks that should be postponed

✨ Current Features

1. Daily Plan Generation

The "generate_daily_plan" function is designed to accept:

- Available time in minutes
- A list of tasks
- Task durations
- Task priorities: low, medium, or high
- Fixed commitments
- Break duration
- Energy level: low, medium, or high

2. Smart Task Prioritization

LifeOS is intended to prioritize important tasks and help users decide what to complete first.

3. Time Management

The assistant checks whether tasks fit within the available time and can suggest postponing lower-priority tasks when necessary.

4. Student-Focused Assistance

LifeOS is designed for students managing college studies, DSA practice, programming projects, assignments, and personal goals.

🛠️ Technology Used

- Google AI Studio: AI prototyping and model interaction
- Gemini: AI reasoning and natural-language responses
- Function Calling: Structured inputs and outputs for task-planning operations
- JSON: Data format for function declarations and responses

⚙️ How It Works

1. The user provides available study time and a list of tasks.
2. Gemini interprets the user's requirements.
3. Gemini may request the "generate_daily_plan" function.
4. The function receives structured information about tasks and time constraints.
5. A function response supplies the proposed schedule.
6. Gemini presents the plan and explains which tasks should be postponed.

Important: A function declaration describes the expected inputs and outputs. A real implementation or manually supplied test response is needed to produce the function result.

🧪 Example

User input:

- Available time: 120 minutes
- DSA practice: 60 minutes, high priority
- Chemistry assignment: 45 minutes, medium priority
- C++ revision: 30 minutes, high priority
- Break: 15 minutes
- Energy level: medium

Expected planning behavior:

LifeOS should recognize that completing every task plus the break requires 150 minutes, exceeding the available time by 30 minutes. It should propose a realistic schedule and identify what needs to be rescheduled.

🚧 Current Development Status

This project is currently at the AI prototyping and function-calling stage.

Component| Status
LifeOS system instructions| Prepared
"generate_daily_plan" declaration| Prepared
Function-calling test| Initiated
Sample function response| Available for testing
Actual function implementation| Not yet confirmed
Persistent task storage| Not yet implemented
User interface/dashboard| Not yet implemented

🔮 Future Improvements

- Task creation, editing, and completion
- Persistent task storage using a database
- Daily and weekly progress reports
- DSA problem-solving tracker
- Habit and gym tracking
- Deadline reminders
- Calendar integration
- A personalized productivity dashboard
- Automatic timetable generation using a working backend

🔒 Data and Privacy

The current prototype should not be assumed to save tasks or timetables permanently. Persistent storage and appropriate privacy protections will need to be implemented before using it as a full personal productivity application.

🚀 Vision

LifeOS aims to become a personal productivity companion that helps students balance academics, technical skill development, projects, health, and personal commitments through realistic planning and consistent progress.

Build better habits. Plan realistically. Make every day count.
