# URL Shortener App

## Overview

The URL Shortener App is a Ruby on Rails application that allows users to shorten long URLs, making them more convenient to share. It provides a simple and efficient way to manage and track links while maintaining a user-friendly interface.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features

- Shorten long URLs into a user-friendly format.
- Track the number of times each shortened link is clicked.
- View the top 100 most clicked links.
- URL validation to ensure valid input.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Ruby (version 2.6.6)
- Ruby on Rails
- PostgreSQL

### Installation

1. Clone the repository:

   ```bash
    git clone https://github.com/salmanali23/url-shortener-app.git
    cd url-shortener-app
   ```
2. Install dependencies:

  ```bash
    bundle install
  ```
3. Create and migrate the database:
  ```bash
  rails db:create
  rails db:migrate
  ```
4. Start the Rails server:
  ```bash
    rails server
  ```

