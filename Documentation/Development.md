# About this Project

# FRONTEND

This is a frontend application powering the Content Management System of Intertwined Financial, this application is built with the following technologies and libraries:

## Installing Prerequisites

Current versioning:

- npm: version 10.8.1>
- node: version 22.3.0>

Please follow these instructions carefully to setup this project on your machine.

1. Install Node.js and npm from [here](https://nodejs.org/en/)
2. Clone this repository into a folder of your choosing (preferably where you won't have to change permissions) using `git clone` command

*   Open the folder after cloning in the command line.
    *   If you cloned using command line, just cd into directory by:
        *   <pre>cd next-gen-financial-learning-hub </pre>
   

## Running the App

You can run the React app using the following commands while inside the project directory:

### NOTE

Before running the application, ensure you create this file  ```.npmrc``` in the root directory of the project
![alt text](https://github.com/coreybrowndev/next-gen-financial-learning-hub/blob/master/pictures/npmrc.png)  
This is crucial as this file stores a core dependency 

Copy the following into the file   
```
@tiptap-pro:registry=https://registry.tiptap.dev/
//registry.tiptap.dev/:_authToken=${$API_KEY}
```  
Gather the $API_KEY from a Developer listed on the project

```
# Install dependencies
npm install

# Start the development server
npm run dev
```

## Output

```
> next-gen-financial-learning-hub-frontend@0.0.0 dev
> vite

Re-optimizing dependencies because vite config has changed

  VITE v5.4.8  ready in 546 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```

Navigate to `http://localhost:5173/` in your browser to access the app

## Third-Party Software

Below is a list of third-party software used in this project:

| Software           | Description                                                    |
| ------------------ | -------------------------------------------------------------- |
| **React.js**       | A JavaScript library for building user interfaces.             |
| **Vite**           | A fast build tool and development server for modern web apps.  |
| **Tailwind CSS**   | A utility-first CSS framework for styling the application.     |
| **Shadcn UI**      | A UI library that integrates well with React and Tailwind CSS. |
| **Vitest**         | A testing framework built for Vite.                            |
| **TipTap**          | A customizable framework for building rich text editors.       |
| **React Feather**  | A collection of simply beautiful open-source icons for React.  |
| **React Router**   | A standard library for routing in React applications.          |
| **Tanstack Query** | Powerful asynchronous state management for React.              |

# Replicating via Docker

## Install Prerequisites

- Download and install Docker Desktop
  - Mac:  [Mac](https://docs.docker.com/desktop/setup/install/mac-install/) 
  - Windows: [Windows](https://docs.docker.com/desktop/setup/install/windows-install/).
  - Linux: [Linux](https://docs.docker.com/desktop/setup/install/linux/).
- Run the Docker executable and start when installing is done.

## Clone Repos 
## Frontend
- Clone the following Repos
  - `git clone https://github.com/coreybrowndev/next-gen-financial-learning-hub-frontend`
 

## You can do it via command line
  - (Windows) Shift+Right-click to an empty place on that folder to open a command line.
  - Run these commands:
   - `git clone https://github.com/coreybrowndev/next-gen-financial-learning-hub-frontend`

### Run
- Run the Frontend  
  Before running the application, ensure you create this file  ```.npmrc``` in the root directory of the project
![alt text](https://github.com/coreybrowndev/next-gen-financial-learning-hub/blob/master/pictures/npmrc.png)  
This is crucial as this file stores a core dependency 

Copy the following into the file   
```
@tiptap-pro:registry=https://registry.tiptap.dev/
//registry.tiptap.dev/:_authToken=${$API_KEY}
```  
Gather the $API_KEY from a Developer listed on the project

  - Run the following docker-compose command in the root folder
  - `docker compose up`
  -  Navigate to `http://localhost:5173/` in your browser to access the app
  -  ![alt text](https://github.com/coreybrowndev/next-gen-financial-learning-hub/blob/master/pictures/docker-compose-output.png)  





