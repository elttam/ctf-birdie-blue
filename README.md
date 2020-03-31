# Overview

**Title:** Birdie Blue  
**Category:** Web  
**Flag:** `libctf{1a320949-b768-4ace-af9f-03eeb3883136}`  
**Difficulty:** Easy

# Usage

The following will pull the latest 'elttam/ctf-birdie-blue' image from DockerHub, run a new container named 'libctfso-birdie-blue', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-blue \
  elttam/ctf-birdie-blue:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-blue' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-blue:latest
```
