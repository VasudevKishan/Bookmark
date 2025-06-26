# Bookmark Landing Page

This project is a static web page for a "Bookmark" landing page, built with [Tailwind CSS](https://tailwindcss.com/) and served using a simple Node.js Express server. The page features a responsive design, interactive tabs, and a mobile-friendly navigation menu.

## Features

- Responsive layout with Tailwind CSS
- Interactive tabbed features section
- Mobile navigation with hamburger menu

- FAQ accordion section
- Newsletter subscription form

## Usage

You can run this project locally using Node.js:

```sh
npm install
npm start
```

Or build and run it in a Docker container:

```sh
docker build -t bookmark-app .
docker run -p 3000:3000 bookmark-app
```

## Related Projects

This application is used as a demo/static site in the following repositories:

- [Nginx Reverse Proxy Demo](https://github.com/VasudevKishan/Nginx-reverse-proxy):  
  Shows how to use Nginx as a reverse proxy for multiple instances of this app.
- [Kubernetes Minikube Demo](https://github.com/VasudevKishan/k8-demo):  
  Demonstrates deploying this app on Kubernetes using Minikube.

Visit those repositories for instructions on running this app behind Nginx or in a Kubernetes cluster.
