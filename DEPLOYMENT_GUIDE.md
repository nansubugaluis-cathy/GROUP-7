# Deployment Guide for Employee Cyberthreat Vigilance System

## Live Deployment Instructions
1. **Clone the Repository**  
   First, clone the repository to your local machine:
   ```bash
   git clone https://github.com/nansubugaluis-cathy/GROUP-7.git
   ```

2. **Install Dependencies**  
   Navigate to the project directory and install the necessary dependencies:
   ```bash
   cd GROUP-7
   npm install  
   ```

3. **Configure Environment Variables**  
   Create a `.env` file based on the `.env.example` file provided in the root of the project. Update the variables with your configuration:
   ```bash
   cp .env.example .env
   ```

4. **Build the Project**  
   Compile the project before deployment:
   ```bash
   npm run build
   ```

5. **Start the Server**  
   Finally, you can start the server using:
   ```bash
   npm start
   ```

## Hosting Options
- **Heroku**  
   Deploy your application to Heroku by following these steps:
   1. Create a Heroku account and log in.
   2. Install the Heroku CLI.
   3. Run `heroku create` to create a new application.
   4. Push your code to Heroku:
      ```bash
      git push heroku main
      ```

- **AWS (Amazon Web Services)**  
   For deploying on AWS, consider using Elastic Beanstalk:
   1. Install the AWS CLI and configure it with your credentials.
   2. Create a new Elastic Beanstalk application and environment.
   3. Use the command:
      ```bash
      eb deploy
      ```

- **DigitalOcean**  
   You can also deploy on DigitalOcean by following these steps:
   1. Create a DigitalOcean account.
   2. Set up a Droplet (virtual machine).
   3. SSH into your Droplet and clone the repository as shown above.

- **Vercel**  
   For quick deploys, Vercel is a great option:
   1. Sign up for a Vercel account.
   2. Connect your GitHub repository and select your project.
   3. Deploy directly from the Vercel dashboard.

By choosing one of these hosting options, you can easily manage and run the Employee Cyberthreat Vigilance System in a live environment.