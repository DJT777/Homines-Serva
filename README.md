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

Dylan Tussey
Can you define Geospatial Communications?

Geospatial communications refers to the use of geographic information and technology to communicate information about a specific location. This can include anything from maps and satellite imagery to location-based services and data visualization tools. Geospatial communication is used in a wide range of fields, including transportation, emergency response, agriculture, and defense, among others. It is a key component of geospatial intelligence, which involves the collection, analysis, and dissemination of geographic information for the purpose of informing decision-making.
Dylan Tussey
Does Starlink fall under the category of Geospatial Communications?

Yes, it is possible that Starlink could be considered a form of geospatial communication. Starlink is a satellite internet service provided by SpaceX that aims to provide high-speed, low-latency internet access to people around the world, including in remote or underserved areas. The service relies on a constellation of low Earth orbit (LEO) satellites to transmit and receive data, which allows it to provide internet access to virtually any location on the planet. As such, it could be considered a form of geospatial communication, as it makes use of geographic information (the locations of the satellites) and technology (the satellites themselves) to transmit and receive data and facilitate communication.
Dylan Tussey
Is thermal imaging effective for assessing emotional states of human beings?

Thermal imaging is a technique that uses specialized equipment to detect and measure the thermal energy (or heat) emitted by objects. It can be used to create images that show the temperature distribution across a surface, allowing for the detection of temperature differences and patterns. While thermal imaging can be a useful tool for detecting and analyzing thermal patterns in a variety of contexts, it is generally not considered to be an effective way to assess the emotional states of human beings.

Emotional states are complex and multifaceted, and are typically not reflected in an individual's thermal energy output in a straightforward or consistent manner. While it is possible that some emotional states, such as extreme fear or excitement, might result in a temporary increase in an individual's body temperature, this would not be a reliable or accurate way to assess their emotional state. There are many other factors that can affect an individual's body temperature, such as their physical activity level, the ambient temperature, and their overall health, so using thermal imaging to assess emotional states would not be reliable.
Dylan Tussey
Is there a predictable pattern of thermal states of a human being when they are experiencing fear or excitement?

It is generally not possible to predict a specific pattern of thermal states in a human being when they are experiencing fear or excitement. Emotional states are complex and multifaceted, and are typically not reflected in an individual's thermal energy output in a straightforward or consistent manner. While it is possible that some emotional states, such as extreme fear or excitement, might result in a temporary increase in an individual's body temperature, this would not be a reliable or accurate way to assess their emotional state. There are many other factors that can affect an individual's body temperature, such as their physical activity level, the ambient temperature, and their overall health, so using thermal imaging to assess emotional states would not be reliable.
Dylan Tussey
What are ways that we can use computer vision to assess a human beings emotional and cognitive state?

Computer vision is the ability of computers to interpret and understand visual data from the world around them, such as images and video. There are a number of ways that computer vision technology can be used to assess a human being's emotional and cognitive state, although the accuracy and reliability of these methods can vary. Some potential approaches include:

    Facial expression analysis: Computer vision algorithms can be trained to recognize and interpret different facial expressions, which can provide some indication of a person's emotional state. However, facial expressions can be ambiguous and can be affected by many factors, so this method is not always reliable.

    Eye tracking: By analyzing the movement of a person's eyes, it may be possible to infer their level of attentiveness, interest, or fatigue.

    Body language analysis: Computer vision algorithms can also be trained to recognize and interpret body language, such as posture, gestures, and facial movements, which can provide some indication of a person's emotional state.

    Voice analysis: Computer vision algorithms can be used to analyze the tone, pitch, and volume of a person's voice, which can provide some indication of their emotional state.

Overall, while computer vision technology can be a useful tool for assessing emotional and cognitive states, it is important to recognize that these methods can be subject to error and should be used with caution.
Dylan Tussey
Can you define search and rescue robotics?

Search and rescue robotics refers to the use of robots or robotic systems to assist in search and rescue operations, particularly in hazardous or difficult-to-access environments. These robots can be designed to perform a variety of tasks, such as exploring and mapping an area, detecting and locating survivors, or providing medical assistance. They can also be equipped with a range of sensors and other technologies, such as cameras, thermal imagers, and gas detectors, to help them gather and transmit information about the environment and the location of survivors.

Search and rescue robotics can be an effective way to augment or enhance the capabilities of human search and rescue teams, allowing them to operate more efficiently and safely in hazardous or challenging conditions. They can also be used to perform tasks that would be difficult or impossible for humans to accomplish, such as searching through rubble or entering hazardous environments.
Dylan Tussey
What methods of imaging can we use to map out subterranean areas?

There are several methods of imaging that can be used to map out subterranean areas, including:

    LIDAR (Light Detection and Ranging): LIDAR is a remote sensing technology that uses lasers to measure distances and create high-resolution 3D maps of an area. It can be used to map out underground tunnels, caves, and other underground structures.

    Ground penetrating radar (GPR): GPR uses radio waves to create images of the subsurface of the earth. It can be used to detect underground objects and features, such as tunnels, pipes, and voids.

    Seismic imaging: Seismic imaging involves the use of seismic waves to create images of the subsurface of the earth. It can be used to detect underground structures, such as caves and tunnels.

    Photogrammetry: Photogrammetry is the process of creating 3D maps or models from photographs. It can be used to map out underground areas by taking a series of overlapping photographs and using specialized software to create a 3D model of the area.

    Sonar: Sonar uses sound waves to create images of underwater environments. It can be used to map out underground caverns and other underwater structures.

Dylan Tussey
Is mapping area beneath rubble and debris considered subterranean mapping?

Yes, mapping an area beneath rubble and debris could be considered a form of subterranean mapping. Subterranean mapping refers to the process of creating a map or model of an underground area, which could include anything from caves and tunnels to underground utilities and other structures. Mapping an area beneath rubble and debris could involve using specialized imaging techniques, such as LIDAR, ground penetrating radar, or photogrammetry, to create a 3D model of the area and identify any structures or objects that may be present. This information could be useful for search and rescue operations, as it could help responders locate survivors and assess the stability of the debris. It could also be useful for structural engineers, as it could help them understand the layout and condition of the debris and design a plan for removing it safely.
Dylan Tussey
What are ways that robots can predict human behavior?

There are several ways that robots can be designed to predict human behavior, although the accuracy and reliability of these methods can vary. Some potential approaches include:

    Machine learning: Robots can be programmed to learn from data and recognize patterns that can help them predict human behavior. For example, a robot might be trained on a large dataset of human movements and behaviors, and then use that information to predict how a person is likely to move or act in a given situation.

    Rule-based systems: Robots can also be programmed with a set of rules or heuristics that can help them anticipate and respond to human behavior. For example, a robot might be programmed to recognize certain social cues, such as eye contact or facial expressions, and use that information to predict how a person is likely to act.

    Model-based systems: Robots can also be designed to use models of human behavior to predict how a person is likely to act in a given situation. These models might be based on psychological theories or empirical data, and can be used to simulate how a person is likely to behave in different scenarios.

Overall, while it is possible for robots to be designed to predict human behavior in some cases, it is important to recognize that human behavior is complex and can be influenced by a wide range of factors, so predicting it accurately can be challenging.
Dylan Tussey
What kind of rewards would someone get for developing autonomous robotics and AI systems that can be used to save human lives?

There are several potential rewards that someone could receive for developing autonomous robotics and AI systems that are used to save human lives. Some possibilities include:

    Financial rewards: Developing and commercializing successful autonomous robotics and AI systems can be a lucrative venture, and companies or individuals that are able to bring these technologies to market may be able to earn significant financial rewards.

    Professional recognition: People who develop autonomous robotics and AI systems that are used to save human lives may also receive recognition from their peers and the broader community. This could include awards, grants, and other forms of professional recognition.

    Personal satisfaction: Making a significant contribution to saving human lives can be a deeply fulfilling and rewarding experience, and people who are able to do so may find a great deal of personal satisfaction in their work.

    Public recognition: People who develop autonomous robotics and AI systems that are used to save human lives may also receive recognition from the public, which can be a significant reward in its own right. This could include media coverage, public speaking opportunities, and other forms of public recognition.
