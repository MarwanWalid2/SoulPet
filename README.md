# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Instructions
1. **Setup environment variables**:
    - Rename `.env.example` to `.env`.
    - Fill in the necessary values in `.env`.

2. **Build the Docker image**:
    ```bash
    docker build -t app .
    ```

3. **Run the Docker container**:
    - Make sure Docker is running.
    - Start your application:
    ```bash
    docker run -ti --rm -p 5000:5000 --env-file .env app
    ```

4. **Access the application**:
    - Open your browser and navigate to `http://127.0.0.1:5000`.

## Product vision statement

SoulPet aims to be a leading platform that intuitively links individuals seeking emotional companionship with the perfect emotional support animal, seamlessly bridging the space between solitude and unwavering affection.

## User stories

- **Finding the Right Match:** As a lonely individual, I want to find an emotional support animal that matches my personality so that I can have a companion who understands and complements me.

- **Profile Creation:** As a new user, I want to easily create a profile detailing my interests and personality so that the app can find the best animal match for me.

- **Choice of Animal Type:** As a user with specific preferences, I want to select the type of animal I'm interested in so that I'm only matched with animals I'm comfortable with.

- **Learning About the Animal:** As a prospective pet owner, I want to see detailed profiles of the animals, including their history, temperament, and needs, so that I can make an informed decision.

- **Easy Communication:** As a user, I want to communicate easily with shelters or current owners so that I can ask questions and arrange meetings with potential emotional support animals.

- **Safety Measures:** As a concerned individual, I want to know that all animals on the platform are verified and safe so that I can trust my future companion.

- **Feedback and Reviews:** As a user, I want to read reviews and feedback from other users who have adopted animals so that I can make a more informed decision.

- **Updating Preferences:** As a user whose preferences change, I want to easily update my profile and animal preferences so that I continue to get matches that suit my current situation.

- **Post-Adoption Guidance:** As a new pet owner, I want access to resources and tips on taking care of my emotional support animal so that we can have a harmonious relationship.

- **Community Engagement:** As a user, I want to interact with a community of like-minded individuals who have also adopted emotional support animals so that I can share experiences and gain insights.

## Task boards

https://github.com/orgs/software-students-fall2023/projects/7/views/2
