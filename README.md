# webcloud
We have created a script that deploys an offline version of Wikipedia to a distant server

We are going to to explain you how to deploy our project to your own computer.
There are two files :
  <ul>
  
  <li>README.md ; Text file with information for deployement </li>
  <li>deploy.sh : bash script for deployement </li>
  </ul>

  <h2> Prerequisites </h2>
   To deploy your website, you need :
    <ul>
    <li> A server with Linux (with Digital Ocean, as an example) </li>
    <li>A terminal (GitBash for example) </li>
       <li> An internet connexion </li>
       <li> Private and public keys from your computer </li>
       <li> With Digital Ocean, you will need to create a clean droplet to create your Ubuntu server </li>
       <li> The IP adress of your server </li>
     </ul>
        

  <h2> Deployement : </h2>
    <ul>
       <li> Open your terminal </li>
       <li> Go to the cloud webcloud's folder on your computer  : $cd~...\FOLDER\ </li>
       <li> Connect to the distant server and deploy the file "deploy.sh" : $~ssh root @XXX.XXX.XXX.XXX &lt; ./deploy.sh </li>
       <li> The process may take a while </li>
       <li> Enter yes if they ask you to</li>
       <li>Go to your browser and enter your server's ip adress when the process has ended</li>
     <ul>

        If you have correctly followed the different steps, the deployment should have succesfully worked. 



        
        
