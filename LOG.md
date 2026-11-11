# CacheLab build log

## Day 1
- Created the GitHub repo and cloned it.
- Set up a monorepo with three packages: core, server and worker.
- Set up TypeScript with one shared base config, and Prettier for formatting.
- Wrote the Docker file for Redis Stack and MongoDB.

**What broke:** Docker could not unpack the downloaded images ("read-only file system"). The cause was a nearly full drive, with only 1 GB free.

**What I learned:**
- A workspace links several packages inside one repo.
- Docker needs roughly 10 GB of free space to unpack Redis Stack and MongoDB.
- The Redis and Mongo URLs are addresses we choose ourselves when we run them locally.