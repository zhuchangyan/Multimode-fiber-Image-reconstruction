**Q**: How to load and use the dataset?

**A**: I recommend using 'pickle' module. Eg. with open("xx/xx/main_24hours_v2_80000_run2.dat", 'rb') as f: speckle_images = pickle.load(f)

**Q**: What does "main_24hours_v2_80000_run2_Records.dat" do?

**A**: It records the wall time when the speckle images started and ended, as well as how long does it took to collect a certain number of images in our MMF experiment.
 
**Q**: Why there are 12000 SLM images but only 80000 speckle images? (Thanks Jawaria Maqbool for the question)

**A**: The first 80000 SLM images are related to first 80000 labels and speckle images. 
 We have 120,000 SLM images simply because we took all the images from MNIST and fashion MNIST dataset, but in experiment we didn't use all of them.

