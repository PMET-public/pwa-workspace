# Development

This is a workspace to work with both [StoryStore UI](https://github.com/pmet-public/storystore-ui) and [StoryStore PWA 🔒](https://github.com/pmet-public/storystore-pwa) repositories in a local environment (a.k.a. localhost).

## Get Started

### 👯‍♀️ Clone Repo
`git clone https://github.com/PMET-public/pwa-workspace.git --recursive`

### ☝️ Configure your Environment

Start by setting your environment variables in _storystore-pwa_. You can do so by copying the the .env file from the sample template `cp ./storystore-pwa/.env.sample ./storystore-pwa/.env`

Then, open the file in you editor of choice `code storystore-pwa/.env` and change the your environment accordingly.

### ✌️ Install Dependencies

From the root folder of your project, run `yarn install`

### 🤙 Run Development

From the root folder of your project, run `yarn dev`. This is going to run both Luma UI and Luma PWA on watch mode.
