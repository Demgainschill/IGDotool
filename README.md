## For the community. Always for the Community.
# IGDotool #
The perfect tool created for extracting posts from instagram using automation using tools such as (xargs for parallel downloading capabilites ,yt-dlp for downloading posts,xclip for clipboard copy/pasting ,xdotool for automating mouse-click actions, )

![image](https://github.com/user-attachments/assets/e914a006-df30-4a36-b57d-4aca54fc1886)

# (MUST READ CAREFULLY inorder for it to work flawlessly...):
1. The user must have the browser session to be at "67% zoom" on a screen resolution of 1920x1080p screen and the page must be on the all-posts instagram page.
2. Regardless of whether the tool will perform a dependency check and install the tools required the tool expects the user to download the tools himself manually if errors caused since script checks and downloads only using apt package manager as of now (tools mentioned at the end section).
3. Note: the tool always assumes the first post to extract is the post from the top left of the instagram all-posts page.
## Assuming the user has all the requirements met before this.
## Running the tool (A 2 step procedure)
1. Running the command ./igdotool -n [int] ( int being the number of posts to extract from )

https://github.com/user-attachments/assets/8843401a-e481-475f-9162-94e74b93bebf

3. A defaulting filename "iglinks" will be populated with links ( can be modified within the script as seen in the above vid) 
4. Then running the command ./igdotool -x [int] ( int being the number of threads/tasks for yt-dlp to download posts parallely in the CWD. ( usually a number between 6-64 based on number of cores { can run "noproc" to view existing cores and adjusting threads } )

https://github.com/user-attachments/assets/af9f9d74-b5ac-4a47-aab2-02a5659e1f5a

## For the community. Always for the community.


