# Users & Partners Management App

A simple React-based web application to manage users and partners. Users can be added, viewed, edited, and filtered by username, set code, and countries. Built using React, Ant Design, Axios, and a JSON server backend.


## Features

**Add New User:** Add a user with username, optional set code, and countries (multi-select).  
**View & Edit User:** View user details and edit them with a full-page modal.  
**Filter & Sort:** Sort users by Username, Set Code, or Countries.  
**Responsive UI:** Modern, clean interface using Ant Design and Tailwind CSS.  
**Backend Integration:** Stores and fetches data from a local JSON server  



## Technologies Used

**Frontend:** React.js, Ant Design, Tailwind CSS  
**Backend:** JSON Server / Express (mock REST API)  
**HTTP Requests:** Axios  
**State Management:** React Hooks (`useState`, `useEffect`)  

---

##Folder Structure


users-partners-app/
├── public/
├── src/
│   ├── components/
│   │   ├── UsersTable.jsx
│   │   ├── NewUserModal.jsx
│   │   └── ViewUserModal.jsx
│   ├── App.jsx
│   └── index.js
├── package.json
└── README.md


##Usage



**Add User:** Click "+ Add New User" button → fill username, optional set code, and select countries → click Save.

**View User:** Click "View" button next to a user → full-page modal opens → edit fields if needed → click Save.

**Sort Users:** Click on table headers (Username, Set Code, Countries) to sort ascending/descending.



