# Travel Buddy - Your Ultimate Trip Planner

![Travel Buddy Logo]()

## Introduction

Welcome to Travel Buddy - Your Ultimate Trip Planner! Travel Buddy is a web application designed to simplify the process of planning and organizing trips with your friends or family. It allows you to create, manage, and collaborate on trips, keeping everyone on the same page and ensuring a memorable travel experience.

## Features

- User Registration and Login: Create an account or log in to access your trips and collaborate with others.
- Creating a Trip: Plan a new trip by providing essential details such as destination, dates, and description.
- Inviting Friends: Invite friends or colleagues to join the trip by sending email invitations directly from the application.
- Trip Dashboard: View trip details, itinerary, expenses, chat, and other relevant information in one place.
- Managing the Itinerary: Collaboratively create and manage the trip itinerary, add activities, attractions, and more.
- Expense Tracking: Add and track trip-related expenses, calculate individual contributions, and view expense summaries.
- Real-time Chat: Communicate with trip members via real-time chat for discussions and coordination.
- Document Sharing: Upload and share important trip-related documents for easy access by all members.
- Notifications: Receive notifications for important updates, reminders, and new messages in the chat.
- Trip Completion: Mark the trip as finished when it's completed, and access trip history for future reference.

## Problem Statement

The current trip management process faces several challenges that affect the overall experience of travelers. The following are the key problems that the Travel Buddy app aims to solve:

1. **Inefficient Trip Management:** The traditional methods of managing trips, such as spreadsheets or manual planning, are time-consuming and prone to errors. There is a need for a centralized platform that streamlines trip management tasks and provides a seamless experience.

2. **Lack of Information on Popular Visiting Sights:** Travelers often struggle to find reliable and up-to-date information about popular tourist attractions at their destination. This results in missed opportunities and difficulties in planning the itinerary. The Travel Buddy app will provide a comprehensive database of popular visiting sights, ensuring users have access to accurate and relevant information.

3. **Limited Knowledge of Nearby Hotels:** Finding suitable accommodation options that fit within the traveler's budget can be a daunting task. The app will leverage hotel data to provide users with a list of nearby hotels, along with essential details such as pricing, reviews, and availability. This will help users make informed decisions and find the best accommodation options.

4. **Lack of Budget Regulation:** Many travelers struggle to keep track of their expenses during a trip, leading to overspending or unexpected financial challenges. The Travel Buddy app will include a budget management feature that allows users to set a budget for their trip and track their expenses in real-time. This feature will provide insights into spending patterns and help users stay within their budget.

5. **No Dedicated Panel for Trip Discussion:** Coordinating and communicating with fellow trip members can be chaotic, especially when using multiple platforms like email, messaging apps, or social media. The Travel Buddy app will include a dedicated discussion panel where trip members can collaborate, share ideas, discuss plans, and make decisions collectively. This will enhance the overall coordination and ensure everyone is on the same page throughout the trip.

The Travel Buddy app aims to address these challenges and provide a comprehensive solution for seamless trip management, efficient itinerary planning, budget regulation, and effective communication among trip members. By solving these problems, the app will enhance the travel experience and make trips more enjoyable and memorable for users.

## Tech Stack

Travel Buddy is built using the MERN (MongoDB, Express.js, React, Node.js) stack with Redux for state management. It also utilizes the Rapid API for fetching location and hotel data.

## API Usage

Travel Buddy uses the Rapid API for fetching location and hotel data. To use the API, sign up on [Rapid API](https://rapidapi.com/) and obtain your API key. Replace `YOUR_RAPID_API_KEY` in the client-side code (wherever API calls are made) with your actual API key.

```javascript
// Example API call using Rapid API
const apiKey = 'YOUR_RAPID_API_KEY';
const apiUrl = `https://api.example.com/endpoint?apiKey=${apiKey}`;
```
