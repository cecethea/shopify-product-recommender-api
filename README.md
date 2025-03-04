# Shopify Product Recommender API

A Django REST API that analyzes Shopify store data and recommends high-potential products using AI.

## Features

- Connect to Shopify stores using OAuth authentication
- Retrieve sales information, product details, and categories
- Analyze best-selling products
- Generate AI-powered recommendations for 5-10 high-potential products
- Integrate selected products directly into the shop

## Tech Stack

- Django
- Django REST Framework
- Pydantic for validation
- Shopify API
- Machine learning for product recommendations

## Installation

```bash
# Clone the repository
git clone https://github.com/cecethea/shopify-product-recommender-api.git
cd shopify-product-recommender-api

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env  # Edit the .env file with your configuration

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

## API Documentation

API documentation is available at `/api/docs/` when the server is running.

## License

MIT