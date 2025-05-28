# 75 Hard Challenge Tracker 💪

A simple, client-side web application to help you track your progress through the 75 Hard mental toughness program. This tracker allows you to monitor your daily tasks, view your progress on a 75-day grid, take daily notes, and manage your challenge attempt.

## ✨ Features

* **Daily Task Checklist:** Track all 6 critical tasks for the 75 Hard challenge:
    * Two 45-minute workouts.
    * Follow a diet (with a field to specify your diet plan).
    * No alcohol.
    * Drink 1 gallon of water.
    * Read 10 pages of a non-fiction book (with a field for the book title).
    * Take a progress picture.
* **Progress Grid:** Visual 75-day grid showing completed, failed, or pending days. Click on a day to navigate to it.
* **Current Day Display:** Clearly shows which day of the challenge you are currently on.
* **Mark Day Complete/Failed:** Buttons to mark the current day's status. Tasks must be checked to mark a day complete.
* **Daily Notes & Reflections:** A dedicated section to jot down thoughts, challenges, or wins for each day.
* **Persistent Data:** Your progress, notes, diet plan, and book titles are saved in your browser's LocalStorage. This means your data persists even if you close the browser tab or refresh the page.
* **Carry-Over Diet & Book:** Diet plan and book title automatically carry over to the next day for convenience.
* **Navigate Between Days:** Easily switch between days to review past entries or plan ahead (though the challenge requires sequential completion).
* **Reset Options:**
    * **Reset Today's Tasks:** Clears the checkboxes for the current day.
    * **Reset Entire Challenge:** A confirmation-protected option to wipe all progress and start over from Day 1.
* **Challenge Rules Displayed:** The core rules of the 75 Hard challenge are listed for easy reference.
* **Responsive Design:** Basic styling for usability on different screen sizes.

## 📜 75 Hard Challenge Rules

As a reminder, the app helps you track the following rules:

1.  Follow a diet (any diet, no cheat meals).
2.  No alcohol.
3.  Two 45-minute workouts per day. One MUST be outdoors.
4.  Drink 1 gallon (3.78 liters) of water daily.
5.  Read 10 pages of a non-fiction, entrepreneurial, or self-help book daily.
6.  Take a progress picture daily.

**If you miss ANY task, you must start over from Day 1.**

## 🚀 How to Use

1.  **Download:**
    * Clone this repository or download the `index.html` file.
2.  **Open:**
    * Open the `index.html` file directly in your web browser (e.g., Chrome, Firefox, Safari, Edge). No web server is needed as it's a client-side application.
3.  **Start Tracking:**
    * The app will load to Day 1 by default, or your last saved day.
    * Fill in your chosen **Diet Plan** and current **Book Title** if desired.
    * Check off tasks as you complete them throughout the day.
    * Use the **Daily Notes** section to record your experiences.
    * Click **"Save Notes for Day X"** to save your task status, notes, diet, and book title for the current day. This also happens automatically when marking a day complete or failed.
    * Once all tasks are completed, click **"Mark Day X Complete ✅"**. This will advance you to the next day.
    * If you fail a day, click **"Mark Day X Failed ❌"**. Note that officially, this means restarting the challenge, but the tracker allows you to mark a day as failed for your own records.
    * Use the **Progress Grid** to visualize your journey and navigate to previous days.
    * If you need to restart the entire challenge, use the **"⚠️ Reset Entire Challenge ⚠️"** button (use with caution!).

## 💻 Technologies Used

* **HTML:** Structure of the web page.
* **CSS:** Styling for the user interface.
* **JavaScript:** Application logic, interactivity, and data persistence using LocalStorage.

## 💾 Data Persistence

* All your challenge data (daily task completion, notes, diet plan, book title, current day, and grid status) is stored locally in your browser's **LocalStorage**.
* This means your data is specific to the browser and device you use. It will not sync across different browsers or devices automatically.
* Clearing your browser's cache or site data for this page may erase your progress.

## 🙏 Good Luck!

This tracker is a tool to aid you in the 75 Hard Challenge. The real work is in the discipline and execution. Stay strong and crush it!
