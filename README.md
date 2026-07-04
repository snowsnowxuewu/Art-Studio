Art Studio Sheduler
# Studio Scheduler 📅

**A lightweight web app for art studios to manage student schedules, attendance, and payments.**

🔗 **Live Demo:** [snowsnowxuewu.github.io/studio-scheduler](https://snowsnowxuewu.github.io/studio-scheduler/)

---

## Features

- **Student database** — store contact info, lesson packages, and payment details
- **Weekly calendar** — see all students and time slots at a glance
- **Attendance tracking** — mark each session as Attended, No Show, or Skipped
- **Auto-reschedule** — skipped lessons automatically extend to the end of the term
- **Capacity warnings** — alerts when a time slot exceeds the maximum student limit
- **Summary dashboard** — total students, month-to-date and year-to-date sessions, top 3 students
- **Backup & restore** — download your data as a JSON file and restore it anytime

---

## How to Use

1. Go to the **Students** tab → Add a student with their schedule and lesson package
2. Open the **Calendar** tab → Navigate to the right week to see their sessions
3. After each lesson, select the attendance status from the dropdown
4. Check the **Summary** tab for an overview of studio activity
5. Go to **Summary → Download backup** regularly to save your data

---

## Updating to a Newer Version

1. **Before updating:** Summary tab → Download backup → save the `.json` file
2. Replace `index.html` in the GitHub repository with the new file
3. Open the updated site — if data is still there, done ✅
4. If data is gone: Summary → Restore from backup → select your saved file ✅

---

## Tech Stack

Pure HTML, CSS, and JavaScript — no frameworks, no dependencies, no server required.
Data is stored in the browser's `localStorage`.

---

## 中文简介

**Studio Scheduler** 是一个为艺术工作室设计的轻量级网页应用，帮助老师管理学生课程、出勤记录和付款信息。

**主要功能：** 学生信息管理 · 每周课程日历 · 出勤记录 · 自动顺延课程 · 容量预警 · 数据汇总看板 · 备份与恢复

**技术栈：** 纯 HTML / CSS / JavaScript，无需服务器，数据保存在浏览器本地存储中。

---

*Built with the assistance of [Claude](https://claude.ai) by Anthropic — my first deployed web project. 🚀*
