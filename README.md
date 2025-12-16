# Web Application – Session Logout Issue

## Overview
This repository contains a security assessment report describing an issue related to improper session handling after user logout in a web application.

## Scope
- Authenticated user sessions
- Logout functionality
- Access to user data after session termination

## Summary
The application does not properly terminate user sessions after logout. As a result, sensitive user data may remain accessible even after the user has logged out, for example by using browser navigation.

## Disclaimer
This report was created for educational purposes in a controlled environment.
