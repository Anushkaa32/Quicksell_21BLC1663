**Kanban Board Application**<br/>
A dynamic Kanban board application built with React.js. It allows users to view and manage tasks grouped by status, priority, or user, while also displaying the of users assigned to tasks. The data is fetched from an external API and allows for real-time sorting and filtering of tasks.

**Tech Stack:**<br/>
React.js: Frontend library for building the UI.
CSS: Custom styles for responsive design and layout.
API: The app fetches tasks and user data from an external API endpoint.

**Project Structure:**<br/>
The project has the following structure:

kanban-board/<br/>
│<br/>
├── public/<br/>
├── src/<br/>
│   ├── components/<br/>
│   │   ├── KanbanBoard.js       # The main Kanban board component<br/>
│   │   ├── TicketCard.js        # Component that renders individual task cards<br/>
│   ├── App.js                   # Main app component<br/>
│   ├── App.css                  # Global CSS for the project<br/>
│   ├── index.js                 # React entry point<br/>
│<br/>
├── package.json                 # Project dependencies and scripts<br/>
└── README.md                    # Project documentation<br/>

**Key Components:**<br/>
App.js: The main entry point of the application. It fetches data from the API, manages the state for grouping and sorting, and renders the KanbanBoard component.<br/>
KanbanBoard.js: This component organizes and displays the task tickets based on the current grouping (status, priority, or user). It also handles sorting.<br/>
TicketCard.js: A presentational component responsible for rendering individual task cards.<br/>

**Getting Started:**<br/>
<br/>
*Prerequisites*<br/>
Make sure you have the following installed:<br/>
Node.js: Ensure you have Node.js (>=12.x) installed.<br/>
npm: The Node.js package manager comes bundled with Node.js.<br/>
<br/>
*Installation*<br/>
Clone the repository:<br/>
git clone https://github.com/Anushkaa32/kanban-board.git<br/>
Navigate into the project directory:<br/>
cd kanban-board<br/>
Install the dependencies:<br/>
npm install<br/>
<br/>
*Running the App*<br/>
npm start<br/>
<br/>

**Screenshot of Output:**



