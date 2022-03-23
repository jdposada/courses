# Instruction for local Build

- Start the container that has Hugo and all dependencies installed
    - Windows machine
        - `docker run -it -p 1313:1313 -v C:\Users\jdpos\Documents\github_repos:/home/workdir --entrypoint /bin/sh jdposa/hugo_backend`
    - Linux Machine
        - `docker run -it -p 1313:1313 -v /home/jose/Documents/github_repos/courses:/home/workdir --entrypoint /bin/sh jdposa/hugo_backend`
- Inside that terminal navigate to the current repo
    - `cd /home/workdir/courses`
- Run Hugo server with `hugo server` inside the folder and go to `localhost:1313` to visualize the webpage