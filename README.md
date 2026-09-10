# Z3C 班级主页 · Class Homepage

> 湖州市上海世外教育南浔实验学校 · 三年级 Z3C 班 · 2026–2027 学年
>
> Huzhou World Foreign Language School (Nanxun) · Grade 3, Class Z3C · Academic Year 2026–2027

---

## 简介 · Overview

这是 Z3C 班的班级信息网站，集合了课程表、执勤排班与班级日志，方便同学和家长随时查阅。

A lightweight class information website for Z3C, bringing together the weekly schedule, morning duty roster, and class journal — accessible to students and parents at any time.

---

## 页面 · Pages

| 页面 | 说明 | Page | Description |
|------|------|------|-------------|
| `index.html` | 班级主页 · 导航入口 | Home | Landing page with navigation cards |
| `schedule.html` | 完整课程表（周一至周五，含课后服务） | Schedule | Full weekly timetable with all subjects & teachers |
| `duty.html` | 早上值勤排班（学生礼仪岗 + 家长护学岗） | Duty Roster | Morning duty schedule for students & parent volunteers |
| `journal.html` | 班级日志（通知、活动、总结） | Class Journal | Announcements, events, and weekly summaries |

---

## 功能 · Features

- **课程表** — 按科目色块展示每日 9 节课，含任课教师姓名及双语科目标注
- **执勤排班** — 区分历史记录与当前学期，清晰呈现男女生轮值及职责说明
- **班级日志** — 用于发布班级通知、活动记录与学期总结
- **响应式设计** — 适配手机与桌面，表格支持左右滑动查看

---

- **Schedule** — Subject color-coded timetable with teacher names and bilingual labels for all 9 daily periods
- **Duty Roster** — Separated by term, shows student ceremony posts and parent school-gate volunteer shifts with clear responsibilities
- **Class Journal** — A place for announcements, activity records, and term summaries
- **Responsive** — Works on mobile and desktop; wide tables scroll horizontally

---

## 项目结构 · Structure

```
wflnx/
├── index.html          # 主页
├── schedule.html       # 课程表
├── duty.html           # 执勤排班
├── journal.html        # 班级日志
├── 课程表.html          # 备用课程表页
├── 值勤排班表.html       # 备用排班表页
└── css/
    └── style.css       # 全站样式
```

---

## 技术栈 · Tech

纯静态 HTML + CSS，无框架依赖，可直接在浏览器中打开或部署至任意静态托管服务（GitHub Pages、Vercel 等）。

Plain static HTML + CSS, zero dependencies. Open directly in a browser or deploy to any static host (GitHub Pages, Vercel, etc.).

---

## 版权 · License

© 2026 Z3C 班 · 湖州市上海世外教育南浔实验学校
