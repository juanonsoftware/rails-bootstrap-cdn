Run the docker image
docker run -p 3000:3000 huanhvhd/rails-apps:demo-bootstrap-cdn-latest
-> With environment variables:
docker run -it -e RAILS_ENV=production -e RAILS_MASTER_KEY=e358f0309116e57ec5de32bf7af917cf -p 3000:3000 huanhvhd/rails-apps:demo-bootstrap-cdn-latest