---
layout: post
title: "Project: AgriSmart – Secure PHP 8 MVC Agriculture Marketplace"
date: 2026-01-11 12:00:00 +0100
categories: projects web
tags: [PHP, MVC, MySQL, web security, CSRF, XSS, e-commerce, ESPRIT]
image: /images/projects/AgriSmart-Secure-PHP-MVC-Marketplace.png
---
## Overview
**AgriSmart** is a production-ready agriculture marketplace built with **pure PHP 8 and MySQL**, letting farmers and agricultural sellers buy, sell and manage products online through a secure, intuitive platform. *(Associated with ESPRIT.)*

📁 Repository: [AgriSmart](https://github.com/Razi-Ammari/AgriSmart)

## Architecture
A **custom MVC architecture — no frameworks** — giving complete control over routing, controllers, models and views.

## Features
- **Role-based access**: Admin, Seller and Customer.
- Product browsing, search and advanced filtering (category, price, sorting).
- Shopping cart, checkout, **order management** and order history.
- Seller dashboard with sales statistics, revenue and inventory management.
- Reviews & ratings, profile management and **category-based recommendations**.

## Security by design 🔐
- **bcrypt** password hashing.
- **CSRF** tokens on every state-changing form.
- **XSS** prevention through systematic output escaping.
- **SQL injection** protection with **PDO prepared statements**.
- Secure file upload handling and session management.

## Tech Stack
`PHP 8` · `MySQL 8` · `PDO` · `JavaScript` · `HTML5 / CSS3`
