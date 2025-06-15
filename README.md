# salesforce-youtube-feedback-survey
Project to collect YouTube video feedback using Salesforce Survey

# Salesforce YouTube Feedback Survey 📊

🎯 **[Click here to try the live Salesforce Survey]( https://orgfarm-ea9d9ed8cb-dev-ed.develop.lightning.force.com/survey/runtimeApp.app?surveyVersionId=0KsgK0000001NiXSAU&previewMode=true)**

---

## 💡 Project Summary

This project demonstrates how to create a simple feedback form for YouTube videos using Salesforce Surveys. The form collects:

- Star ratings
- Viewer opinions
- Score and feedback logic

---

## 🔧 Tools Used

- Salesforce Feedback Management
- Survey Builder
- Display Logic
- Page Branching Logic

---

## ✅ Steps Followed (Based on YouTube Video)

### 1. Enable Surveys
- Go to **Setup → Survey Settings**
- Enable Surveys
- Assign **Survey Creator** permissions

---

### 2. Create a New Survey

- Go to **Surveys tab** → Click **New Survey**
- Enter:
  - Name: `YouTube Feedback Survey`
  - Description
  - Apply theme or branding
- Save and launch the **Survey Builder**

---

### 3. Add Pages & Questions

#### **Page 1: Video Feedback**
- Question 1: *Rating* – “Rate the video”
- Question 2: *Text* – “Tell us what you didn’t like”

#### **Page 2: Overall Video Score**
- Question 1: *Score* – “Score our video based on Quality, Content, and Knowledge”

#### **Page 3: Score Details**
- Question 1: *Text* – “Tell us why you gave us this score”

#### **Page 4: Thank You**
- Display message: “Thank you for taking our survey.”

---

### 4. Add Logic

#### Display Logic:
- Show “Tell us what you didn’t like” **only if Rating ≤ 3**

#### Page Branching:
- If Score > 6 → Show **Score Details Page**
- Else → Skip to **Thank You Page**

---

### 5. Activate & Share

- Click **Activate** on the survey
- Generate **Public Link**
- Share it on YouTube, LinkedIn, or social media

---

## 📌 Demo

👉 [Try the Live Survey](https://your-survey-link.com)

---

## 📷 Screenshots (Optional)

You can upload screenshots and reference them like this:

```markdown
![Survey Screenshot](./survey1.png)

