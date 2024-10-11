# Weather bot

> This is a WhatsApp bot that provides weather updates and enables weather-related conversations..
> Written using ballerina and uses OpenWeatherMap API for weather data and OpenAI services to power the chatbot.
> This bot will participate in the IEEE [Innovate With Ballerina](https://innovatewithballerina.com/) challenge.

## Features

- Get weather information for a location periodically.
- Answer questions related to weather with,
  - Current weather information.
  - Weather forecast.
  - Historical data.

## Installation

### Prerequisites

- pnpm
- Ballerina 2201.10.0
- WhatsApp Business API setup
- OpenWeatherMap API setup
- OpenAI API setup

### Steps

1. Clone the repository.
2. Install the project management dependencies.
   ```bash
   pnpm install
   ```
3. Start the bot using the following command.
   ```bash
   pnpm start
   ```

## Contributing

### Git Workflow

- The `main` branch is the default branch.
- Commiting directly or merging to the `main` branch locally is not allowed.
- Create a new branch for each issue.
- Push the branch to the remote repository and create a pull request when ready for review.
- Addding `Closes #issue-number` in the pull request description or in any commit message will automatically close the issue when the pull request is merged.
