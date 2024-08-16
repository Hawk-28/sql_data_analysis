# Data Analysis Project

## Data source: https://data.world/atlas-query/paintings

## Overview

This project involves analyzing a dataset related to famous artworks, focusing on canvas sizes, pricing, and data cleaning operations. It includes a Python script to load data into a PostgreSQL database and SQL queries to perform analysis and data cleaning.

## Dataset

The dataset consists of several tables represented as CSV files:

- `artist.csv`: Contains information about artists.
- `canvas_size.csv`: Lists various canvas sizes available for artworks.
- `image_link.csv`: Contains URLs or paths to images of the artworks.
- `museum_hours.csv`: Details museum operating hours.
- `museum.csv`: Contains information about museums.
- `product_size.csv`: Contains data about different product sizes and their associated costs.
- `subject.csv`: Details the subjects of artworks.
- `work.csv`: Contains information about artworks, such as work ID, name, museum ID, style, and artist ID.

## Setup

### Prerequisites

- Python 3.x
- PostgreSQL database
- Required Python libraries: `pandas`, `sqlalchemy`
