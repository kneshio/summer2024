# June 3rd

Attended Orientation and Performed Training Tasks for the Week

# June 4th

Continued finishing Training Tasks

# June 5th

Started looking into papers to perform Super Resolution. Attended a DOE weekly meeting event.

# June 6th

Looked through 4 different papers covering the history of Super Resolution and detailed methods on  how to perform super resolution using Neural Networks and Transformer Based Methods

# June 7th 

Wrapped up findings into a Presentation, but the results of each of these methods did not seem very promising

# June 10th

Discovered GAN-based methods, specifically Real-ESRGAN, which also includes open sourced code and has very promising results

# June 11th

Looked through different Real-ESRGAN implementations and compared each of the results. 

# June 12th

Briefly went through guides for connecting ssh into a gpu computer. Also attended the DOE weekly event.

# June 13th

Summarized results for Real-ESRGAN for some of the node images that were provided. Learned that some of the results with low quality image inputs looked cartoonish. Need to test more results on text based images as well.

# June 14th

Found two new models for Super Resolution called BIRD and OSEDiff. Read over research papers. Also now have access to Chicago street view images, so I can test over potential images where there are cars with license plate numbers.

# June 17th

The goal for this day was to try to implement the two implementations. Unfortunately, today was a rough day: BIRD required a GPU node, and there were connectivity issues with the GPU nodes. I also tried reimplementing on Google Colab but had issues with unzipping my files. I then moved to Jupyter Notebook by connecting through Polaris and my School Account using Anvil, but both sessions failed to start. Spent some time testing the new images I acquired in the Real-ESRGAN model. Also started looking into Docker for future setup with the GPU node.

# June 18th

Goals:
- Try to run other Real-ESRGAN implementations and BIRD in Google Colab and compare results
- See if it works on Jupyter Notebook through Polaris and the GPU Node as well
- Figure out how to improve results or work with results and create a GUI user friendly interface with it

Update 1:
- Was able to run N00MKRAD's implementations of Real-ESRGAN that are specifically trained on real world images. Will continue updating on results but it seems to not be much of a difference
- Polaris and the GPU node is unable to connect to the internet, so I am unable to import any packages using pip commands. Will continue to use Colab for now until it is fixed.

Final Update:
- There did not seem to be much of a difference between other implementations of Real-ESRGAN trained on real world images with the results I showed last week. Maybe an improved GPU could have an improvement but highly doubt it
- Started looking into Polaris, since Dario taught me how to import files into Polaris using Containers. Seems like I need to study Docker for tomorrow.
