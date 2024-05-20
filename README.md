# rahti2-fastapi 

### For deployment to Rahti2

Note: OpenShift wants the main branch to be named **master** by default.

See also: https://fastapi.tiangolo.com/deployment/docker/



### For local real-time development

Rename `.env-example` to `.env` to override the `MODE=production`set in the `Dockerfile`. Note that this needs a valueless declaration of `MODE` in `docker-compose.yml`

To run the container locally:
`docker-compose up --build`
