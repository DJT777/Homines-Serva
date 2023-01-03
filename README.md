# Save-Humans


# NOTES

# Work in Progress:
## TO-DO:
### Expand Dataset Beyond 105 images to 1000+
### Develop C++ Deployment of YoloV7 for Fastest Performance
### Push Expanded Dataset to Roboflow and C++ Deployment to GitHub
### Provide Theoretical Implementation of Save-Humans AI
### Deploy C++ Deployment to Nvidia Jetson Nano and beyond
### Integrate C++ Deployment With Autonomous Robotics
## END TODO


## Research After Project Completion:
### Thermal Imaging For Emotional, Cognitive, and Health Assessment of Human
### Voice Analysis of Human Being
### Body Language Analysis By Computer Vision
### Human Facial and Ocular Pattern Classification
### Geospatial Communications And Autonomous Robotics
### Subterranean Imaging and Mapping By LIDAR, Ground Penetrating Radar, Seismic Imaging, Photogammetry, and Sonar
### Renewable Energy Sources For Sustained Long Term Deployment of Autonomous Robotics

## END NOTES




#A Human Detection System Created in Collaboration Between an AI and a Human

#Credit: Dylan James Tussey and OpenAI (https://chat.openai.com/chat)

#ChatGPT Transcript

#Dataset: https://susanqq.github.io/UTKFace/
  
#Dataset Annotated For MK1 Training: https://app.roboflow.com/cyborg-ninja/save-human-females/1


Dylan Tussey
How would I go about composing a computer vision dataset of human females and human males?

To create a computer vision dataset of human females and males, you will need to follow these steps:

    Identify the goal of your dataset and the tasks it will be used for. This will help you determine the size and diversity of the dataset you need to create.

    Gather images of human females and males. You can do this by searching online, purchasing stock photos, or taking your own photos.

    Pre-process the images to ensure they are all in the same format and resolution. You may also want to crop the images to focus on the face or body.

    Annotate the images by labeling the gender of each person in the image. You may want to use a tool like Labelbox or RectLabel to help with this process.

    Split the dataset into training, validation, and test sets. It is important to have a separate test set to evaluate the performance of your model.

    Store the dataset in a format that is easy to access and use for training a computer vision model. Some common formats include HDF5, TFRecord, and COCO.

Keep in mind that creating a high-quality dataset can be a time-consuming process. It is important to carefully curate and label the images to ensure that the dataset is representative and useful for the task you are trying to accomplish.
Dylan Tussey
Can you give me some code that I could use to pull images from Google that are labeled "human female"

There are a few different ways you could go about using code to pull images from Google that are labeled "human female":

    Use a search engine API to search for "human female" images and retrieve the search results programmatically. Google has a Custom Search API that you can use for this purpose. You would need to create a Custom Search Engine and then use the API to search for images and retrieve the search results.

    Use a web scraper to search for "human female" images on Google and download the images. There are many different web scrapers available, including Python libraries like Beautiful Soup and Selenium. You would need to write code to search for "human female" images on Google and then parse the search results to extract the image URLs. You could then download the images using a library like requests.

    Use a pre-built dataset of human female images that has already been collected and labeled. There are many datasets available online that you can use for computer vision tasks, including datasets of human faces. Some examples include the UTKFace dataset and the CelebFaces Attributes Dataset (CelebA).

Keep in mind that when using images from the internet for a computer vision dataset, it is important to respect copyright laws and ensure that you have the necessary permissions to use the images.
Dylan Tussey
If I have a part1.tar.gz part2.tar.gz part3.tar.gz how do I extract all parts together?

To extract multiple .tar.gz files together, you can use the tar command with the -zxvf options, followed by a list of the .tar.gz files you want to extract:

tar -zxvf part1.tar.gz part2.tar.gz part3.tar.gz

This will extract all of the .tar.gz files into the current directory. If you want to extract the files to a specific directory, you can use the -C option followed by the directory path:

tar -zxvf part1.tar.gz part2.tar.gz part3.tar.gz -C /path/to/output/directory

Keep in mind that this command will extract all of the files in the .tar.gz files into the same directory, so you may want to create separate directories for each .tar.gz file to keep the extracted files organized.

You can also extract the .tar.gz files one at a time by using the tar command on each file separately:

tar -zxvf part1.tar.gz
tar -zxvf part2.tar.gz
tar -zxvf part3.tar.gz

This will extract each .tar.gz file into the current directory. You can use the -C option with this method as well to specify an output directory.

