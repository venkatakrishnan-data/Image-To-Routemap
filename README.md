#Image-To-Route map
The Shiny application to create a route map using image inputs https://image-to-maps.blogspot.ie/.
## Background
The application is built in Shiny and uses the concept of image to text using tesseract package available in R.
## Input
The application takes the destination address in an image format. "N" number of image can be uploaded which holds the destination address the user needs to travel.
## Output
The route map is generated from the imaged destination address. It calculated the distance of each location the user needs to travel from his origin and generates a sequence of maps from his origin to destination. The first map is generated from the starting point of the user to the nearest destination and the next map takes the first destination as the starting point and generates the next map and so on. The distance of each location from the origin is also made available to the user.


