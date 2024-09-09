# kobuki_system

Provides docker compose based implementation of kobuki system.

Container included at the moment are follows

| Service       | Container                                  | Repository                                        |
| ---           | ---                                        | ---                                               |
|kobuki         | ghcr.io/airesearchlab/kobuki:humble        | https://github.com/AIResearchLab/kobuki           |
|astra_legacy   | ghcr.io/airesearchlab/astra_legacy:humble| | https://github.com/AIResearchLab/astra_legacy_ros | 


## Usage

Clone this reposiotory

```bash
git clone https://github.com/AIResearchLab/kobuki_system.git
```

Pull the Docker image and start compose

```bash
cd kobuki_system/docker
docker compose pull
docker compose up
```