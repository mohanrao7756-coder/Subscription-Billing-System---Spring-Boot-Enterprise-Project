# Subscription-Billing-System---Spring-Boot-Enterprise-Project

## Project Overview

Subscription Billing System is an enterprise-level backend application developed using Java Spring Boot. The system manages users, subscription plans, subscriptions, payments, audit logs, dashboard APIs, and billing workflows using RESTful APIs and layered architecture.

This project follows enterprise coding standards with Controller, Service, Repository, DTO, and Entity layers.



# Technologies Used
JAVA 17
SPRING BOOT
SPRNG DATA JPA
MYSQL
LOMBOK
MAVEN
POSTMAN
SWAGGER
HIBERNATE
ECLIPSE IDE



# Features Implemented

## User Management

* Create User
* Update User
* Delete User
* Get All Users
* Search Users
* Pagination Support
* Role-Based Status Tracking

## Subscription Plan Management

* Create Subscription Plans
* Get All Subscription Plans
* Plan Status Tracking

## Subscription Management

* Create Subscription
* Manage User Subscriptions
* Subscription Status Tracking

## Payment Management

* Create Payments
* Get All Payments
* Payment Status Tracking

## Audit Logging

* Tracks system activities
* Stores performed actions and timestamps

## Dashboard APIs

* Total Users
* Total Subscriptions
* Total Payments
* Active Subscription Reports

## Exception Handling

* Global Exception Handling
* Resource Not Found Handling

## Documentation

* Swagger/OpenAPI Documentation



# Project Architecture

The project follows layered enterprise architecture.


Client/Postman
       ↓
Controller Layer
       ↓
Service Layer
       ↓
Repository Layer
       ↓
MySQL Database




# Package Structure


com.subscription.billing
│
├── controller
├── service
├── service.impl
├── repository
├── entity
├── dto
├── exception
└── BillingApplication

Author

Mohan Rao

Java Spring Boot Developer
