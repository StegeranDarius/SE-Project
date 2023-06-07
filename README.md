# PROJECT for SOFTWARE ENGINEERING LABORATORY

## Stegeran Darius Cosmin

### TO-DO Lister

---

## ******Application Description******

To-Do List application that allows users to efficiently manage their tasks and organize them into groups. The application will incorporate user authentication, database connectivity, and a user-friendly interface to enhance productivity and task management.

---

## **Use Case Diagram**

![uc.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc.svg)

---

## USE CASE DETAILS

---

**UC1: User Login**

- **Actor(s):** User
- **Description:** This use case allows the user to log into the application using their credentials.
- **Preconditions:** The user must have a registered account in the system.
- **Postconditions:** The user is successfully logged in and can access their to-do list.
    
    ![uc1.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc1.svg)
    

---

**UC2: Add Task**

- **Actor(s):** User
- **Description:** This use case enables the user to add a new task to their to-do list.
- **Preconditions:** The user must be logged into the application.
- **Postconditions:** The task is successfully added to the user's to-do list and saved in the database.
    
    ![uc2.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc2.svg)
    

---

**UC3: Remove Task**

- **Actor(s):** User
- **Description:** This use case allows the user to remove a task from their to-do list.
- **Preconditions:** The user must be logged into the application and have existing tasks in their to-do list.
- **Postconditions:** The selected task is successfully removed from the user's to-do list and deleted from the database.

![uc3.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc3.svg)

---

**UC4: Edit Task**

- **Actor(s):** User
- **Description:** This use case allows the user to modify the details of an existing task.
- **Preconditions:** The user must be logged into the application and have existing tasks in their to-do list.
- **Postconditions:** The selected task is successfully updated with the new details in the user's to-do list and the database.

![uc4.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc4.svg)

---

**UC5: Change State of Task**

- **Actor(s):** User
- **Description:** This use case enables the user to change the state of a task (e.g., mark it as completed, set a priority level).
- **Preconditions:** The user must be logged into the application and have existing tasks in their to-do list.
- **Postconditions:** The selected task's state is successfully updated in the user's to-do list and the database.

![uc5.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc5.svg)

---

**UC6: Add Task to Group**

- **Actor(s):** User
- **Description:** This use case allows the user to add a task to a specific group or category.
- **Preconditions:** The user must be logged into the application and have existing tasks and groups/categories available.
- **Postconditions:** The selected task is successfully assigned to the chosen group and saved in the database.

![uc6.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/uc6.svg)

---

## Activity Diagrams

UC name: **Add Task**

![acd1.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/acd1.svg)

---

UC name: **Edit Task**

![acd2.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/acd2.svg)

---

## GUI

![gui3.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/gui3.svg)

This diagram represents the following flow:

1. LoginScreen is the initial screen for the User Login use case. Upon successful login, the user is navigated to the MainScreen.
    
    ![login.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/login.png)
    
2. ReisterScreen allows a new user to register for the task management system
    
    ![register.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/register.png)
    
3. MainScreen represents the home screen, from which the user can navigate to different use cases.
    
    ![Screenshot from 2023-06-07 15-27-06.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/Screenshot_from_2023-06-07_15-27-06.png)
    
4. For the Add Task use case, the user navigates to the AddTaskScreen and then returns to the MainScreen upon saving the task.
    
    ![Screenshot from 2023-06-07 15-28-11.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/Screenshot_from_2023-06-07_15-28-11.png)
    
5. For the Edit Task use case, the user navigates to the EditTaskScreen and then returns to the MainScreen upon saving the changes.
    
    ![Screenshot from 2023-06-07 15-38-50.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/Screenshot_from_2023-06-07_15-38-50.png)
    
6. For the Add Task to Group use case, the user navigates to the AddTaskToGroupScreen and then returns to the MainScreen upon saving the group assignment
    
    ![Screenshot from 2023-06-07 15-41-18.png](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/Screenshot_from_2023-06-07_15-41-18.png)
    

---

## DOMAIN MODEL

![domain-model.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/domain-model.svg)

---

## ROBUSTNESS DIAGRAMS

UC name: **Add Task**

![robust1.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/robust1.svg)

---

UC name: **Change State of Task**

![robust_2.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/robust_2.svg)

---

## SEQUENCE DIAGRAMS

UC name: **Add Task**

![seq1.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/seq1.svg)

UC name: **Change State** 

![seq2.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/seq2.svg)

---

## THE EXTENDED CLASS DIAGRAM

![extened_class_diag.svg](PROJECT%20for%20SOFTWARE%20ENGINEERING%20LABORATORY%202c4b7be625e746cb878f1a87185b388b/extened_class_diag.svg)
