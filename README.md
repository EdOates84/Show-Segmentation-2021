# Show-Segmentation
GSoC 2021 project with Red Hen Lab. I want to improve the clustering algorithm to the in-production code and enhance the previous work. The main problem is to find the correct anchor. Currently, the most time-consuming process in the program is going frame by frame and extracting faces. The face-recognition method used in the production code processes each frame individually. I want to upgrade it to a parallelized algorithm to process multiple frames in a batch and increase the processing speed exponentially, which will also help in faster testing of hyperparameters. Batch processing can be much quicker than processing single images at a time. So I think we use batch processing for multi-threading. More information about the project statement can be found <a href="https://sites.google.com/site/distributedlittleredhen/home/the-cognitive-core-research-topics-in-red-hen/the-barnyard/tv-show-segmentation">here</a>. 

<b>Mentors:</b> <a href="https://www.rees.ox.ac.uk/people/dr-anna-wilson">Anna Wilson</a>, <a href="https://comm.ucla.edu/person/francis-steen/">Francis Steen</a>, <a href="http://frankie.robertson.name/">Frankie Robertson</a> 

### Blog detailing the research and working can be found at <a href="https://edoates84.github.io">edoates84.github.io</a>
