# Crowd-Nation

Crowd-Nation is a dynamic community-driven platform that empowers users to explore, create, and share events across a wide range of categories. With a focus on personalization and community engagement, Crowd-Nation allows individuals to discover events based on their unique preferences while also enabling them to contribute by suggesting new events or making recommendations. Whether you're an organizer, an attendee, or someone with a passion for discovering new experiences, Crowd-Nation is designed to be your go-to platform.

## Table of Contents
- [Vision](#vision)
- [Motivation](#motivation)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Modules](#modules)
- [Contributing](#contributing)
- [License](#license)

## Vision

The vision behind **Crowd-Nation** is to create a central hub for live events, tailored to user preferences and enhanced through community involvement. Whether you love attending festivals, concerts, or club events, Crowd-Nation makes it simple to find events that match your personal tastes. 

We aim to provide a **seamless and inclusive experience** for users to connect with the events they care about, while also offering event organizers a platform to reach an audience more effectively.

## Motivation

The need for a centralized platform that not only aggregates events but also offers personalized event recommendations was apparent. As technology evolves, so do user expectations for discovering and attending live events. Crowd-Nation bridges that gap by delivering a community-focused platform that enables user-generated content, personalized recommendations, and real-time event notifications.

## Key Features

- **Event Cards with Hardware-Tracking**: Crowd-Nation offers unique event tracking through hardware-based solutions such as WiFi access points, allowing users to get live data about event crowd levels and more.
- **Personalized Notifications**: Receive notifications tailored to your interests—whether it's your favorite artist releasing new music or an upcoming performance.
- **User-Contributed Events**: Users can suggest new events or modify existing ones to ensure event information is up-to-date.
- **Artist and Event Tracking**: Get personalized updates on your favorite artists, from new music releases to their upcoming performances.
- **SurrealDB Database**: Crowd-Nation uses [SurrealDB](https://surrealdb.com/), a high-performance, scalable, and flexible database, ideal for dynamic event data.
- **C# REST API Backend**: The platform uses a powerful and scalable backend built in C# to handle user authentication, event suggestions, and real-time data.

## Tech Stack

Crowd-Nation uses a modern tech stack to ensure scalability, performance, and a rich user experience:

- **Frontend**: 
  - [Vue.js 3](https://vuejs.org/)
  - [PrimeVue](https://www.primefaces.org/primevue/) (for UI components)
  - [Pinia](https://pinia.vuejs.org/) (for state management)
  - [SCSS](https://sass-lang.com/) (for styling)

- **Backend**:
  - [C#](https://learn.microsoft.com/en-us/dotnet/csharp/) (for REST API)
  - [SurrealDB](https://surrealdb.com/) (Database)

- **Tools and Integrations**:
  - [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) (for automated deployments)
  - [Docker](https://www.docker.com/) & [Portainer](https://www.portainer.io/) (for container management)
  - [Let's Encrypt](https://letsencrypt.org/) (for SSL certificates)
  - [Swagger](https://swagger.io/) (for API documentation)
  - [SurrealDB](https://surrealdb.com/) for user and event data.

## Usage

Crowd-Nation’s platform allows users to:

- Browse personalized event recommendations based on filters like location, genre, and artist preferences.
- Submit new events for community review or edit event details.
- Receive notifications about event changes or updates to favorite artists and genres.
  
### Event Discovery:

1. **Browse Events**: The main feature of the app allows users to search and browse a comprehensive list of events.
2. **Apply Filters**: Filters such as genre, location, and event type help users tailor the events they see.
3. **Personalized Suggestions**: Based on user interactions, the platform will provide customized event suggestions.

### Event Suggestion:

1. **Submit an Event**: Users have the ability to suggest new events that can be reviewed by admins or the community.
2. **Modify Events**: Existing events can be updated or modified by users with specific permissions.

## Modules

The platform contains several core modules:

- **User Authentication**: Handle login, registration, and user roles (admin, moderator, user).
- **Event Management**: Handle event creation, modification, and deletion.
- **Notifications**: Personalized event and artist updates.
- **Analytics**: Backend analytics for event attendance and popularity metrics.

## Contributing

We welcome contributions from the community to enhance the functionality of Crowd-Nation. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch with the following format: `issue-[Issue ID]-feature-description` (e.g., `issue-1-event-suggestion`).
3. Make your changes.
4. Create a pull request referencing the issue (e.g., #1).
5. Wait for approval and merge.

## License

Crowd-Nation is open source and licensed under the MIT License.
