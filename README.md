# Facebook Video Download Microservice

A simple and efficient microservice to download Facebook videos by providing the video URL. This microservice provides a REST API to fetch video URLs and download the video content.

## Features

- **Fetch video information**: Extracts metadata (e.g., title, resolution, etc.) from a Facebook video URL.
- **Download video**: Allows downloading Facebook videos directly to the server or client.
- **Supports multiple resolutions**: Choose video resolution before downloading.

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/facebook.video.download.microservice.git
    cd facebook.video.download.microservice
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the microservice:

    ```bash
    python app.py
    ```

   By default, the server will run on `http://localhost:5000`.

## API Usage

### 1. Fetch Video Info

#### Endpoint
`GET /api/video/info`

#### Parameters
- `url` (required): The Facebook video URL.

#### Example Request
```bash
GET http://localhost:5000/api/video/info?url=https://www.facebook.com/video_url
