# Flashy Flashcard

**Flashy Flashcard** is a feature-rich web application that allows users to create, organize, and study flashcards. Users can enhance their flashcards by uploading images and audio, making studying more interactive and personalized.

---

## Features

- **Create Flashcards**: Users can create flashcards with text, images, and audio.
- **Organize Flashcards**: Group flashcards into different folders and study sets.
- **Study Mode**: Provides an intuitive interface for users to study flashcards with shuffle and repeat options.
- **Media Support**: Upload images and audio for flashcards, making studying interactive.
- **User Authentication**: Secure login and signup functionality using JWT and Firebase.
- **Real-Time Performance**: Optimized for scalability, ensuring fast loading and interaction.
  
---

## Tech Stack

This project was built using the following technologies:

- **Frontend**: React, Redux
- **Backend**: Express.js, MongoDB
- **Caching**: Redis
- **Messaging Queue**: Kafka
- **Reverse Proxy**: Nginx
- **Containerization**: Docker
- **Cloud Platform**: Azure

---

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/flashy-flashcard.git
   cd flashy-flashcard
   ```

2. **Install dependencies**
   - Navigate to the `frontend` and `backend` directories and install the required packages:
   
   ```bash
   # In frontend/
   npm install
   
   # In backend/
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add the following variables:

    ##### Backend Environment Variable
   ```bash
    MONGO_URI=""
    PORT=""
    JWT_SECRET=""
    CLOUDINARY_URL=""
    CLOUDINARY_CLOUD_NAME=""
    CLOUDINARY_API_KEY=""
    CLOUDINARY_API_SECRET=""
    EMAIL_SERVICE=""
    EMAIL_PORT=""
    EMAIL_USER=""
    EMAIL_PASS=""
    DEVELOPER_EMAIL=""
    EVENT_HUBS_CONNECTION_STRING=""
    EVENT_HUBS_NAMESPACE=""
    EVENT_HUB_NAME=""
    CONSUMER_GROUP_NAME=""
    REDIS_HOST_NAME=""
    REDIS_PORT=""
    REDIS_PASSWORD=""
   ```

   ##### Frontend Environment Variables
   ```
    VITE_FIREBASE_API_KEY=""
    VITE_FIREBASE_AUTH_DOMAIN=""
    VITE_FIREBASE_PROJECT_ID=""
    VITE_FIREBASE_STORAGE_BUCKET=""
    VITE_FIREBASE_MESSAGING_SENDER_ID=""
    VITE_FIREBASE_APP_ID=""
    VITE_FIREBASE_MEASUREMENT_ID=""
    VITE_BASE_URL=""
   ```
---

## Usage

### Creating a Flashcard
- Log in or sign up to start creating flashcards.
- You can add text, upload images, and record or upload audio to your flashcards.

### Organizing Flashcards
- Group flashcards into folders and sets.
- Review flashcards in study mode with the ability to shuffle and repeat cards.

---

## System Architecture

The Flashy Flashcard system is designed with a focus on scalability, performance, and high availability.


### Architecture Diagram
(Add your architecture diagram here)

---

## Video
   
Going to upload a youtube video about working of project soon.

---

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

---

## License

This project is licensed under the MIT License.

---