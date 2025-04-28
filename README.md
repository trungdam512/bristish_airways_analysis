# British Airways Reviews Dashboard

A Streamlit dashboard that displays customer reviews for British Airways flights using data stored in Snowflake.

## Features

- Displays review data from Snowflake database in an interactive table format
- Built with Streamlit for easy web-based visualization
- Secure database connection handling using environment variables

## Prerequisites

- Python 3.7+
- Snowflake account and credentials
- Required Python packages (see requirements.txt)

## Setup

1. Clone this repository
2. Create a configuration.env file in the project root with the following variables:
   ```
   snowflake_user=your_username
   snowflake_password=your_password
   snowflake_account=your_account
   snowflake_database=your_database
   snowflake_schema=your_schema
   snowflake_warehouse=your_warehouse
   snowflake_role=your_role
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```python
   print("Hello, World!")
   ```

## Usage

The dashboard will open in your default web browser, displaying:
- A table of British Airways customer reviews
- Interactive sorting and filtering capabilities
- [Add more features as they are implemented]

## Project Structure

