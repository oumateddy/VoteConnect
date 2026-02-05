# VoteConnect
VoteConnect platform, a full-stack civic engagement solution for Kenyan youths (18+) to connect with politicians and civic leaders in a controlled, admin-mediated environment. This plan adheres to the specified requirements, including user roles, features, authentication, payments, legal compliance, and design guidelines. 
/backend (Node.js/Express)

/src
/controllers (auth.js, users.js, events.js, etc.)
/models (User.js, Event.js, etc. – using Sequelize ORM)
/routes (api.js)
/middleware (auth.js, ageCheck.js)
/services (africasTalking.js, mpesa.js)
package.json (dependencies: express, sequelize, africas-talking, jsonwebtoken, etc.)
server.js (entry point)
.env.example (API keys, DB config)
/frontend-web (React/Next.js)

/pages (admin/dashboard.js, public/home.js, user/profile.js)
/components (EventCard.js, LoginForm.js)
/styles (global.css with Kenyan colors)
package.json (dependencies: next, axios, etc.)
next.config.js
/mobile-android (Flutter)

/lib
/screens (RegistrationScreen.dart, Dashboard.dart)
/widgets (OtpInput.dart, EventList.dart)
/services (api_service.dart)
pubspec.yaml (dependencies: flutter, http, firebase_messaging)
android/app/build.gradle (for Material Design)
/database (PostgreSQL)

migrations/ (SQL files for schema)
seeds/ (sample data for testing)
/docs

README.md (full setup guide)
wireframes/ (PNG files – described in text, but you can generate with Figma)
deployment.md (AWS instructions)
/tests (Jest for backend, Flutter test for mobile)

Dockerfile (for containerization)

docker-compose.yml (for local dev: backend, DB, web)
