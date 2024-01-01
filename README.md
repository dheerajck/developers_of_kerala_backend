# OpenSource Kerala Developers Gig/Job Platform - Backend

**Still in the initial stages of the project, looking for 6 initial contributors to join this project!**
**Let me know if you are interested. Contact me at [sangeeth123sj@gmail.com](mailto:sangeeth123sj@gmail.com)**
**Website Link: [https://kerala-devs.vercel.app](https://kerala-devs.vercel.app)**

Welcome to the backend repository of the OpenSource Kerala Developers Gig/Job Platform! This repository houses the backend services for our platform dedicated to fostering the growth of the Python community in Kerala.

## About

This backend repository serves as the core of our open-source job/freelance platform tailored specifically for Kerala's developers. It encompasses the API services, data management, and server-side functionalities to support the frontend interface.

## Key Features

- **API Endpoints**: Handle job listings, freelance gigs, user authentication, and community-related functionalities through robust API endpoints.
- **Data Management**: Efficiently manage and store data related to job listings, user profiles, collaborations, and more.
- **Authentication and Security**: Implement secure authentication mechanisms to protect user data and interactions.
- **Scalability and Performance**: Design for scalability and optimal performance to handle growing user interactions.

## Technologies Used

- **FastAPI**: Leveraging FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.7+.
- **Database (Choose based on preference)**: Planning to utilize MongoDB Atlas for data storage.(Looking for contributor)
- **Authentication**: Implementing authentication mechanisms such as JWT (JSON Web Tokens) in fastapi.(Looking for contributor)
- **Deployment**: Deploying on Digital Ocean using Docker (Looking for contributor)

## Getting Started
 - Create and activate your python venv, [Check this out to learn how to do that](https://realpython.com/python-virtual-environments-a-primer/#create-it)
 - Install required dependencies, `pip install -r requirements.txt`
 - Now you should get a connection string to the mongodb instance you are going to use, [Check this out to learn how to do that](https://www.youtube.com/watch?v=rE_bJl2GAY8)
 - Create two environment variables MONGODB_URI and SECRET_KEY, MONGODB_URI is the connection string you got from previous step, [Check this out to learn one way to generate a secret key using python](https://docs.python.org/3/library/secrets.html)
 - Run your webapp, `uvicorn main:app --reload`

## How to Contribute

1. **Fork** the repository.
2. **Clone** the forked repository to your local machine.
3. Make your **contributions** or enhancements to API endpoints, data models, security measures, or performance optimizations.
4. Create a **Pull Request**.

We encourage contributions of all kinds, whether it's building the backend, bug fixes, new API endpoints, database optimizations, or documentation improvements. Join us in building a robust backend for supporting the Kerala Python community!

## Hall of Fame

Become one of the exclusive initial six builders of this platform and receive special badges for increased job search visibility. Your contributions will be celebrated, recognized, and you'll play a vital role in steering the future of this open-source gig/job platform.


## License

This project is licensed under the [MIT License](link-to-license).
