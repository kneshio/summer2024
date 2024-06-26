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

# June 19th

Goals:
- Run BIRD in Google Colab
- Try to get Docker working

Update 1:
- I should've read the BIRD research paper with a little more effort, since the results did not seem as promising as Real-ESRGAN.

Update 2:
- After searching super resolution on YouTube for roughly one hour, I found two models that have promising results which were featured by the YouTube channel "Two Minute Papers".
- Models are called GigaGAN and SUPIR
- Going to do some research and test out both models

Final Update:
- Was not expecting how big of an improvement the SUPIR model ended up being
  - Will show the visual results in the presentation on June 20th, but it is a much bigger improvement compared to Real-ESRGAN
  - Difference between Real-ESRGAN lies in the prompt you can feed the model beforehand to guide it to the right path
  - Unfortunately computationally expensive, so can only test on small images
- GigaGAN did not have an open-sourced implementation, and seemed to not be viable with its ridiculous computation power

# June 20th

Goals:
- Finish up testing SUPIR before the presentation today
  - Try to generate smaller output images to test efficiency
  - Test inputs that have text
 
Update 1:
- After some testing, I also discovered that SUPIR is not very good at generating text, even if you try to help it by adding text.
  - Moving forward, I want to try to work around this by incorporating a model with SUPIR that generates text well.
  - When I have access, I want to test the model on the small blurry images Seongha sent.
  - Start learning Docker to setup the model locally in Argonne systems

# June 21st

Goals:
- Test the small blurry images
- Study Docker
- Study Source Code and have it successfully run in local systems

Update:
- SUPIR works well on the small blurry images when testing on the online demo
- Docker is quite complicated
  - Getting GPU to work on PyTorch is quite tedious
- Searching for additional source code for the SUPIR model so I can figure out what to use for the final product

# June 24th

Goals:
- Continue studying source code on SUPIR
- Study more Docker

Update: 
- Found the old Waggle-sensor Dockerfile that I could possibily use for my code
- Searched online for additional code implementations of SUPIR
  - The UI version I showed on Thursday is a paid implementation, so I cannot directly access the source code
  - There is another free implementation, but uses a ComfyUI system so it is much more tedious for the user to use

# June 25th

Update:
- I was working at home due to the bad weather
- Decided to study alternative ways to access GPU nodes, so I was looking into Polaris Jupyter Notebook and how to run GPU, since it is running CPU by default
- Watched the old resources under https://docs.alcf.anl.gov/services/jupyter-hub/ in hopes of setting it up
- Still having trouble setting up GPU
