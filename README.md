# 2025-02-07-tutorial

How to run the script:

1. Build the container: `docker build -t mycontainer`
2. Run the container: `docker run -p 8787:8787 -e PASSWORD="password" mycontainer`
3. Go into RStudio: Open a browser, go to `localhost:8787`
4. In terminal: run `bash /home/rstudio/list.sh`