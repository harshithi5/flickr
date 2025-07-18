# Flickr — Memory Time Capsule App

## About the Project

### Problem

People often capture their memories in the form of images but lack a meaningful way to preserve them for future reflection. Traditional gallery apps or cloud drives do not offer the emotional experience of unlocking a memory on a future date — like opening a time capsule.

### Solution

This app solves the problem by allowing users to upload images as **memories**, associate each image with a **future unlock date**, and experience the joy of revisiting those moments only when the time comes.
It also enables users to **favourite their unlocked images** and gives them the flexibility to **unlock images manually** if the unlock date has already passed.

Built with the **MERN Stack (MongoDB, Express, HTML, CSS, JavaScript, Node.js)** and **Google OAuth** for authentication, this app brings together secure login, intuitive design, and emotional value.

## Features

* **Secure Authentication**
  Google OAuth login ensures secure access to personal memories.

* **Upload Memories with Unlock Date**
  Users can upload images and set a future unlock date, like creating a digital time capsule.

* **Unlocking Logic**
  Images remain hidden until the unlock date arrives. Users can manually unlock past-due images.

* **Favourites Collection**
  Users can favourite unlocked images for easy access to their most cherished memories.

* **Organized Viewing**
  Images are clearly categorized into:

  * **Upcoming Memories**
  * **Unlocked Memories**
  * **Favourites**

* **Clean, User-Friendly Interface**
  Minimal design focused on emotional connection and ease of use.


## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/harshithi5/flickr.git
cd flickr
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Create a `.env` File

Use the provided `.env.example` as a reference.

### 4. Fill in Required Environment Variables

* **Google OAuth Credentials**
* **MongoDB Atlas Connection String**

Refer to `.env.example` for the exact keys.

### 5. Start the Application

```bash
npm start
```

### 6. Ensure Uploads Directory Exists

Make sure there is an `uploads/` directory at the project root for storing user-uploaded images. Create it manually if it is missing.

```
/uploads
```

