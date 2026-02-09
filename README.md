# Upstar Music

A music artist management application built with React, Redux, and MongoDB.

## Features

- **Artist Management**: Create, edit, delete, and view details of music artists.
- **Filtering**: Filter artists by age, years active, and retirement status.
- **Search**: Search for artists by name.
- **Data Persistence**: Uses MongoDB for storing artist and album data.
- **Desktop App**: Packaged with Electron for desktop usage.

## Tech Stack

- **Frontend**: React, Redux, Redux Form, React Router
- **Backend/Database**: MongoDB, Mongoose
- **Desktop Wrapper**: Electron
- **Build Tool**: Webpack

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB installed and running locally on port 27017

### Installation

1.  Clone the repository:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  Install dependencies:

    ```bash
    npm install --legacy-peer-deps
    ```

3.  Start the application:
    ```bash
    npm run start
    ```
    This command starts both the Electron app and the Webpack development server.
