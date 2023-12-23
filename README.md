# [Kanban Board Application](https://frolicking-sopapillas-dcb91d.netlify.app/)

This is a Kanban board application built using React + vite that interacts with the provided API from [https://tfyincvdrafxe7ut2ziwuhe5cm0xvsdu.lambda-url.ap-south-1.on.aws/ticketAndUsers](https://tfyincvdrafxe7ut2ziwuhe5cm0xvsdu.lambda-url.ap-south-1.on.aws/ticketAndUsers). The application allows users to dynamically adjust the Kanban board based on their grouping and sorting preferences. Users can group tickets by status, user, or priority, and sort the displayed tickets by priority or title. The application also retains the user's view state even after page reload.

## Features

- Group tickets by status, user, or priority.
- Sort tickets by priority or title.
- Visually appealing and responsive design.
- Ability to save the user's view state in local storage.
- Priority levels are defined as Urgent (4), High (3), Medium (2), Low (1), and No priority (0).

## Demo

You can see a live demo of the Kanban board application [here](https://frolicking-sopapillas-dcb91d.netlify.app/).

## Installation

To run the Kanban board application locally, follow these steps:



1. Navigate to the project directory:
    ```bash
    cd kanbanBoard
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm run dev
    ```
5. Open your web browser by following the link given in terminal visit  to use the application (http://127.0.0.1:5173/).


## Usage

1. Click the "display" button to fetch and display the tickets from the provided API.

2. Select one of the three grouping options: "By Status," "By User," or "By Priority."

3. Choose the sorting option: "Priority" or "Title."

4. The Kanban board will dynamically adjust to reflect your choices.

5. The application will save your view state, so you can return to your preferred settings even after a page reload.



