

## Getting Started

### Prerequisites

- Docker installed on your system

### Building the Docker Image

```bash
docker build -t landing-page .
```

### Running the Container

```bash
docker run -d -p 80:80 landing-page
```

The landing page will be available at `http://localhost`

### Stopping the Container

To stop the running container:

```bash
docker ps
docker stop <container_id>
```

## Project Structure

```
├── index.html          # Main HTML file
├── style.css           # CSS styles with responsive design
├── Dockerfile          # Docker configuration
├── assets/             # Image assets
│   ├── blackpink.jpg
│   ├── bypass.jpg
│   ├── deadline.png
│   ├── whatsapp.jpg
│   ├── line.png
│   ├── instagram.png
│   └── ticket.jpg
└── README.md           # This file
```



## Technologies Used

- HTML5
- CSS3 (Flexbox, Media Queries)
- Docker
- Nginx (Alpine)
