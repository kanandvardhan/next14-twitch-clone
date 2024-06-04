# Gamehub

Hi, I'm Sai Anand. I will be covering one of my exciting projects that I worked on to gain developer experience. The web application is named "Gamehub".

Gamehub is an online live video streaming SaaS application, which can also be referred to as a Twitch Clone. This project is made using the Server Side Rendering capabilities of Next.js 14, Tailwind CSS, Shadcn UI library, Prisma ORM, PostgreSQL database, Livekit streaming API, and authentication services using Clerk.js.

## Features

- *Live Streaming:* Anyone can use this web application to live stream their content on the internet and others can watch it live.
- *Live Chat:* Includes live chat feature both solo and community-wise.
- *Streamer Information:* Viewers can know which streamer is currently live, view a particular streamer's about section, their number of followers, and follow or unfollow a streamer.
- *Search Functionality:* Users can search for any streamer in the search box.
- *Streamer Dashboard:* Every streamer has their own dashboard which includes:
  - Control over community chat.
  - Enable/disable chat.
  - Delay chat by 3 seconds.
  - Enable chat only for followers.
- *Streaming Configuration:* Streamers must configure their server URL and stream key to connect to their local streaming application (e.g., OBS Virtual Studio).
- *User Management:* Streamers can block/unblock any of their viewers or followers.

## Technologies Used

- *Next.js 14:* Server Side Rendering.
- *Tailwind CSS:* Styling.
- *Shadcn UI Library:* UI components.
- *Prisma ORM:* Database management.
- *PostgreSQL:* Database.
- *Livekit Streaming API:* Streaming capabilities.
- *Clerk.js:* Authentication services.

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

Ensure you have the following installed:
- Node.js
- PostgreSQL
- OBS Virtual Studio (for streaming)

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your-username/gamehub.git
2. Install NPM packages
   ```sh
   npm install
3. Set up your environment variables for PostgreSQL, Livekit, and Clerk.js.
4. Run the application
   ```sh
   npm run dev
   
### Usage

1.  **For Streamers:**
    - Configure your server URL and stream key in the dashboard.  
    - Use OBS Virtual Studio or any other local streaming application to start streaming.
        
2.  **For Viewers:**
    - Browse and search for live streamers.
    - Follow or unfollow streamers to customize your sidebar.
        
### Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
    
2.  Create your Feature Branch (git checkout -b feature/AmazingFeature)
    
3.  Commit your Changes (git commit -m 'Add some AmazingFeature')
    
4.  Push to the Branch (git push origin feature/AmazingFeature)
    
5.  Open a Pull Request
    

### License

Distributed under the MIT License. See LICENSE for more information.

### Contact

Sai Anand - \[kanandvardhan@yahoo.com] - \[https://www.linkedin.com/in/kanandvardhan/]

Project Link: [Next 14 - Twitch Clone](https://next14-twitch-clone-beta.vercel.app/)



