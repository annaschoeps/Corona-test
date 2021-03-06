# Corona Explorer

This Shiny app uses data from the European Centre for Disease Prevention and Control to visualize the number of confirmed cases of COVID-19 worldwide.

![image](https://user-images.githubusercontent.com/43906806/80989865-ceabd500-8e35-11ea-9eb1-ecb9c1c750b5.png)


![image](https://user-images.githubusercontent.com/43906806/80998499-5b10c480-8e43-11ea-9edf-3f9231e814ff.png)




### Run the app

The Corona app is implemented in R using the Shiny Server web application framework. All dependencies are packaged in the docker container.

Follow the steps below to run the app using the Docker file:

- Run the docker using the command:
```
sudo docker run -p 80:3838 annaschoeps/corona
```



To build an image from the Dockerfile first (if necessary), use the following commands:

- Clone the GitHub repository into a newly created directory using the command:
```
git clone git@github.com:annaschoeps/Corona-explorer.git
```

- Build an image from a Dockerfile:
```
sudo docker build -t annaschoeps/corona .
```
Note: Building the image can take a few minutes.
