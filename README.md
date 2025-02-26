# AI Trip Advisor

AI Travel Planner is a smart travel assistant that helps users discover destinations, plan trips, and get personalized recommendations using AI. It integrates Google Places API, Gemini API, and Auth-Client API for real-time data and authentication. Secure login is managed with Firebase Authentication, ensuring a seamless user experience.

## Features

- **Personalized Trips**: Generate trips tailored to your budget and travel choices.
- **Hotel Recommendations**: Get hotel suggestions that fit your itinerary.
- **Dynamic Itineraries**: Itineraries are created based on user preferences and budgets.

## Screenshots


![Screenshot 1](https://github.com/user-attachments/assets/8be09761-a8d1-4a0f-a365-425ddb4e688e)
![Screenshot 2](https://github.com/user-attachments/assets/b7dd2f12-291d-4645-9533-7cc5298ef6fe)
![Screenshot 3](https://github.com/user-attachments/assets/bd0cfefd-8aad-4b66-a516-58a899f86d3a)
![Screenshot 4](https://github.com/user-attachments/assets/c859c344-80fb-4222-8b06-f9225275189b)

## Getting Started

To run this project on your machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kartik-chaudhari-1911/AI-Travel-Planner.git
    cd AI-Travel Planner
    ```

2. **Create a `.env.local` file in the root folder**:
    ```plaintext
    VITE_GOOGLE_PLACE_API_KEY=your_google_place_api_key
    VITE_GOOGLE_GEMINI_AI_API_KEY=your_google_gemini_ai_api_key
    VITE_GOOGLE_AUTH_CLIENT_ID=your_google_auth_client_id
    FIREBASE_API_KEY=your_firebase_api_key
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Run the application**:
    ```bash
    npm run dev
    ```
