# **DBMS Quiz Management System**

## **Project Overview**
This project is a database-driven quiz management system implemented using MySQL and Java Swing. It allows users to:
- Register or log in with credentials.
- Participate in quizzes with questions categorized by difficulty levels.
- View profiles with stats (e.g., total scores, correct answers, wrong answers, etc.).
- Check the leaderboard for rankings.

---

## **Features**
### Database Schema
- **`Player`**: Stores user details like name and date of birth.
- **`Questions`**: Contains quiz questions, options, and answers.
- **`Score`**: Tracks scores, correct/wrong answers, and stats.
- **`Leaderboard`**: Dynamically ranks players based on scores.

### Procedures and Triggers
- Procedures for managing answers, viewing profiles, and updating scores.
- Triggers for automatic leaderboard updates.

### Interactive Quiz
- Randomized question selection.
- Real-time score updates.

### User Interface
- Built with Java Swing for login, quizzes, and leaderboard access.

---

## **Technologies Used**
- **Database:** MySQL (Procedures, Triggers, Views)
- **Frontend:** Java Swing
- **Backend Connectivity:** JDBC

---

## **Setup Instructions**
1. **Database Setup:**
   - Install MySQL.
   - Create and populate the `miniproject` database using the provided SQL scripts.
2. **Java Environment:**
   - Install JDK 8 or newer.
   - Add MySQL Connector/J to your classpath.
3. **Run:**
   - Compile and run the `dbmsproject.java` file.

---

## **Future Enhancements**
- Add multi-quiz functionality.
- Transition to a web-based platform.
- Implement OAuth for better authentication.

