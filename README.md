# Amazon Price Scraper

A web-based application that allows users to scrape Amazon product information across multiple regions and keep track of their search history. 

## Demo

For a live demonstration of the application, click [here](https://github-production-user-asset-6210df.s3.amazonaws.com/68614457/257233963-129e4f08-1647-48fe-9e6c-a06d8e68cbc7.mp4).

## Features

1. **User Authentication**: Secure Google login using OAuth2.
2. **Search Limit**: Set daily search limits for users to ensure fair use.
3. **Search History**: Users can review their search history, complete with product information.
4. **Price Comparison**: Allows users to compare prices across different Amazon regions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-price-scraper.git
   ```

2. Navigate to the project directory:
   ```bash
   cd amazon-price-scraper
   ```

3. Install necessary dependencies

## Usage

1. Set up the SQLite database:
   ```bash
   python database.py
   ```

2. Run the application:
   ```bash
   flask run
   ```

3. Access the web app via `http://localhost:5000/`.

## Tech Stack

- **Backend**: Python, Flask
- **Database**: SQLite
- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Google OAuth2

## Contributing

1. Fork the repository.
2. Create a new branch for your changes.
3. Make the desired changes or improvements.
4. Submit a pull request detailing the changes made.

## License

MIT License.

---
