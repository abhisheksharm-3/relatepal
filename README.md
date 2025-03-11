# Relatepal

An intelligent relationship management app that helps users maintain important personal connections through AI-driven suggestions.

## Overview

Meaningful Connections is a native Android application designed to help users strengthen and maintain relationships with important people in their lives. Unlike standard reminder apps that create mechanical interactions at predetermined intervals, this app introduces natural unpredictability and contextual awareness to make staying in touch feel more spontaneous and meaningful.

## Features

### Relationship Dashboard
- Organize contacts into customizable relationship categories
- Visual indicators showing the "health" of each relationship
- Set priority levels for different relationships
- Notes section for important details about each person

### Smart Connection Recommendations
- AI suggests connections at contextually appropriate but unpredictable times
- Recommendations based on time since last contact, special occasions, life events, and conversation history
- Varied suggestion types (call, message, video chat, in-person) based on relationship type

### Conversation Assistant
- AI-generated conversation starters based on previous discussions and shared interests
- Conversation history log to enable meaningful follow-ups
- Reminders for important events mentioned in previous conversations

### Interaction Tracking
- Log of when and how you last connected with each person
- Analysis of who initiates contact to help maintain balanced relationships
- Optional sentiment tracking for future reference

### Privacy & Security
- End-to-end encryption for all relationship data
- Local storage options for sensitive information
- No required contact access (manual entry option available)

## Technical Implementation

### Architecture
- MVVM architecture pattern
- Room Database for local storage
- Kotlin Coroutines for asynchronous operations
- Jetpack Compose for modern UI implementation
- WorkManager for scheduling suggestions

### Key Components
- AI Recommendation Engine for personalized connection timing
- Contextual conversation topic generation
- Natural, non-mechanical notification system

## Development Status

This application is currently in development. The initial version focuses on core relationship management features with plans to expand AI capabilities in future releases.

## Getting Started

### Prerequisites
- Android Studio Arctic Fox or newer
- Min SDK: 29 (Android 10.0)
- Target SDK: 35 (Android 15)

### Building the Project
1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle files
4. Run on an emulator or physical device