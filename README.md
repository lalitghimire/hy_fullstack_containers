# hy_fullstack_containers
## Exercise 12.1:Using a computer (without graphical user interface)  
Step 1: Read the text below the Warning header.  
Step 2: Download this repository and make it your submission repository for this part.  
Step 3: Run curl http://helsinki.fi and save the output into a file. Save that file into your repository as file script-answers/exercise12_1.txt. The directory script-answers was created in the previous step.  

## Exercise 12.2: Running your second container  
Use script to record what you do, save the file as script-answers/exercise12_2.txt  
The hello-world output gave us an ambitious task to do. Do the following  
Step 1. Run an Ubuntu container with the command given by hello-world  
The step 1 will connect you straight into the container with bash. You will have access to all of the files and tools inside of the container. The following steps are run within the container:  
Step 2. Create directory /usr/src/app  
Step 3. Create a file /usr/src/app/index.js  
Step 4. Run exit to quit from the container  

## Exercise 12.3: Ubuntu 101  
Use script to record what you do, save the file as script-answers/exercise12_3.txt  
Edit the /usr/src/app/index.js file inside the container with the now installed nano and add the following line  
```console.log('Hello World')```

## Exercise 12.4: Ubuntu 102  
Install Node while inside the container and run the index file with node /usr/src/app/index.js in the container.  
The instructions for installing Node are sometimes hard to find, so here is something you can copy-paste:  
```curl -sL https://deb.nodesource.com/setup_16.x | bash  
apt install -y nodejs```  
You will need to install the curl into the container. It is installed in the same way as you did with nano.  
After the installation, ensure that you can run your code inside the container with command  
```root@b8548b9faec3:/# node /usr/src/app/index.js  
Hello World  ```
