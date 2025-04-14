## For the community. Always for the Community.
# IGDotool #
The perfect tool created for extracting saved posts from instagram using automation using tools such as (xargs for parallel downloading capabilites ,yt-dlp for downloading posts,xclip for clipboard copy/pasting ,xdotool for automating mouse-click actions, )

![image](https://github.com/user-attachments/assets/e914a006-df30-4a36-b57d-4aca54fc1886)

# (MUST READ CAREFULLY inorder for it to work flawlessly...):
1. In order to install the tool copy and paste in your terminal "git clone https://github.com/Demgainschill/IGDotool.git"
2. The user must have the browser session to be at "67% zoom" on a screen resolution of 1920x1080p screen and the page must be on the all-posts instagram page.
3. Regardless of whether the tool will perform a dependency check and install the tools required the tool expects the user to download the tools himself manually if errors caused since script checks and downloads only using apt package manager as of now (tools mentioned at the end section).
4. Note: the tool always assumes the first post to extract is the post from the top left of the instagram all-posts page.
## Assuming the user has all the requirements met before this.
## Running the tool (A 2 step procedure)
1. Running the command ./igdotool -n [int] ( int being the number of posts to extract from )

https://github.com/user-attachments/assets/6b14c4d0-7a30-48bb-950a-d522e128c69a

3. A defaulting filename "iglinks" will be populated with links ( can be modified within the script as seen in the above vid) 
4. Then running the command ./igdotool -x [int] ( int being the number of threads/tasks for yt-dlp to download posts parallely in the CWD. ( usually a number between 6-64 based on number of cores { can run "noproc" to view existing cores and adjusting threads } )

https://github.com/user-attachments/assets/37316862-8257-413c-991f-1bd5be94fe5c

## Known Problems
1. In this release problems related to saved "photo posts" will cause problems as a whole (Only video posts as of now...)

## For the community. Always for the community.


Buy me a coffee ☕ 
Btc address
bc1q44xnlwyeajzsj28ln2ju5u8c7ugvnqzmf8awsw
