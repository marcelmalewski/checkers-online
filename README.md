# Checkers online

## Table of contents
* [Idea](#idea)
* [Features](#features)
* [Technologies](#technologies)

## Idea
Checkers online app where you can play with somone in real-time.

## Features
### Current features
* You can register and login.
* Your data is encrypted (with argon2) and stored in database.
* With jsonwebtoken it is checkd every time if someone who wants to do some action in your account is really you. Eventually he is logged out.
* You can create and delete your own room.
* You can join other's rooms.
* You can play checkers inside room.
* You can use chat inside room.

## Technologies
* React
* Redux
* Formik
* Express
* Mongoose
* Socket.IO
* Axios
* jsonwebtoken
