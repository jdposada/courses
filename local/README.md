# Instruction for local Build

- Start the container that has Hugo and all dependencies installed
    - `docker run -it --net host -v /home/jposada/Documents/github_repos:/home/workdir --entrypoint /bin/sh jdposa/hugo_backend`
- Inside that terminal navigate to the current repo
    - `cd /home/workdir/courses`
- Run Hugo server with `hugo server` inside the folder and go to `localhost:1313` to visualize the webpage 