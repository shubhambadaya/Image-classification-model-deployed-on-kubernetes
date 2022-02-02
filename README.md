# Image classification model deployed on GCP
The detail steps are

    1.Create a streamlit app -python file.

    2.Create a docker file.
  
    3.Create the requirements file.
  
    4.Create the Kubernetes deployment YAML file.
  
    5.Create the Kubernetes service YAML file.
  
    6.Create the cloudbuild YAML file.
  
    7.Create a GitHub repository on the GitHub desktop.
  
    8.Upload and organize the files on the Github desktop.
  
    9.Push the files from desktop to Github.
  
    10.Link the cloudbuild to the Github and the GCP project.
  
    11.Create a trigger in the GCP -trigger based on the changes in the Github code.
  
    12.Now the build is triggered and the app is deployed on the Kubernetes engine.
 
 
## Key points to focus on:

    1.While creating kubernetes cluster, make sure to create a standard cluster.Cluster with 1 machine will not work this code.

    2.Check if the file names and cluster location are consistent across the codes.
<img width="1439" alt="Screenshot 2021-08-07 at 12 15 40 PM" src="https://user-images.githubusercontent.com/86912972/128591370-83ee487e-9d03-425b-a1fb-a69730a0b8bf.png">


