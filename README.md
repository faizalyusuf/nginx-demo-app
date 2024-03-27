This is a demo of a CI/CD build and deploy of an NGINX container to a docker host.
<p>It utilises the following tools:
<p>1. AWS EC2 with Docker
<p>2. Jenkins
<p>The NGINX application is accessible at http://54.179.207.208:99. This will show the index.html page.</p>
<p>Commits to the index.html docker-compose.yml file will be automatically deployed by Jenkins to the EC2 host.</p>
