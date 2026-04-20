# Evaluation-task
Game System Assessment
How to run:

Make sure you have Docker installed.

Run the following command in the root folder:
docker-compose up --build

The system will automatically:

Set up a PostgreSQL database.

Run Prisma migrations.

Execute the main.js script to demonstrate the logic.

הוראות הרצה
דרישות קדם: ודאו שתוכנת Docker Desktop מותקנת ופעילה.

הרצה: הריצו את הפקודה הבאה בטרמינל מתוך תיקיית הפרויקט:

Bash
docker-compose up --build
מה המערכת מבצעת:
מסד נתונים: הקמת קונטיינר PostgreSQL.

סנכרון: הרצה אוטומטית של Prisma כדי לעדכן את מבנה הטבלאות.

אפליקציה: הרצת הקובץ main.js למימוש הלוגיקה העסקית.

תוצאה: הודעת Success: User joined game תופיע ביומן הריצה (Logs).
