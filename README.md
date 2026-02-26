# Personal Minecraft Server

## `.env` File

Add a `.env` file to the root folder before running the containers.

Valid variables:

- `MC_DATA_DIR`: Path to the Minecraft `data/` directory that will be mounted to the container as a volume.
- `MEMORY`: Maximum memory allocation, e.g. "`8G`".
- `RCON_PASSWORD`: Password for RCON SSH access on port 2222.