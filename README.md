*** WORKING PAPER ***

*** ATTACHED CODE FOR PROOF-OF-CONCEPT ***

*** YOUTUBE DEMO ***

# INTRODUCTION

* Neighborhood shops do more than provide us with essential goods. They're our "homes away from home" where unrelated people relate. They're the place you can go daily at a given time for the simple pleasure of good company and conversation.  However, informal public life is not totally engrained in our young American cities.  Modern tools must perserve these kinds of informal human associations as they're essential to healthy democratic cities.  My research pulls together something like a work bench to preserve the social fabric of the neighborhood shop. I'm focused on making modern tools feel like a natural extension of the existing experience. 
* With the help of many others, I develop a sensing system capable of intergrating ethnographic field notes into more abstract and analytical efforts to address the evolving nature of human-computer interactions.  My goal is to make neighhborhood shops feel more "neutral", so staff and guests can better get to know each other, like one another and take interest in each others well-being.  

# DATA PREP: ETHNOGRAPHY & AUTOENCODER

* First, I get rich ethnographic data into a coherent usable format for the sensing system. The rich data comes from neighborhood shop ethnography. My belief is that new data helps us ask new questions, new questions develop new theories and new theories can create new sensing system tools.
+ So what is ethnography? It's a sociological method of firsthand participant observation in once unfamiliar social circles to pull a sense of what's relevant in that world. Field notes include: personal responses, sensory impressions, neighborhood identities, human behaviors, jottings, etc. I embarked on 10 months of ethnography in two Chicago neighborhood shops for data collection. Next I built a working autoencoder to convert the qualitatively rich data into a usable coherent format, so it has nicer properties for sensing system algorithms to learn good judgement, especially during unusual "edge cases".  

# SENSING SYSTEM ALGORITHMS

* Through a combination of data prep, off-the-shelf hardware, reinforcement learning, reward functions and human feedback I develop a sensor system to address unusual "edge cases" more effectively. I do this by digitizing the location of all items in a shop to create real-time planograms.
* Hardware:
* Reinforcement Learning:
* Reward Functions:
* Fine-Tuning:

# TIMELINE 

* Winter 2018 — Spring 2020
   	* Literature Review & Ethnography
* Summer 2020
	* People/Footfall Counter (Proof-of-Concept)
* Fall 2020
	* Inventory Asst for Neighborhood Shops (Hand Motion & Item Classifier)
* Winter 2021
	* Who has what object? (Temporal Association)
* Spring 2021
	* Autonomous Checkout Pt. 1 
	
# LEADING QUESTIONS

* Teach machines to NOT use guest biometrics as a condition of accepting payment under the Song Beverley Act of 1971?
* How could we underpin modern tools for neighborhood shops with a public log of all queries run on video stream data?  ("thus the watchers themselves are watched")
* Branching object persistence models across multiple cameras
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background
* Lowering processing power bills by bridging the edge-cloud barrier
* Determining the metrics that improve downstream performance
* How could I better understand how social, economic and legal systems work together to achieve my research goals? 
		
# SUMMER 2020

01 Installing Required Packages and Libraries
* Python
* OpenCV https://opencv.org/
* dlib http://dlib.net/a

02 Configuring the Edge Computing Device (Raspberry Pi)

03 Footfall/People Counter (Plz see Attached Codebase)
* Counts the # of people entering and exiting a room
* Videos/
    * .avi
    * .mp4
    * .mp4
* Output/
	* .avi
* cognition (module)
	* init__.py
	* centroidtracker.py
	* directioncounter.py
	* trackableobject.py
* people_counter.py (driver script)

# FALL 2020 & WINTER 2021

01 Installing Required Packages and Libraries
* scikit-image https://scikit-image.org/
* scikit-learn https://scikit-learn.org/stable/index.html
* Numpy https://numpy.org/install/
* Keras https://keras.io/
* Tensorflow https://www.tensorflow.org
* Caffe http://caffe.berkeleyvision.org/

02 Ethnography & Autoencoder Setup

03 2D Human Pose Estimation with Tensorflow and Caffe 
* Who’s here? 

04 Feature Extraction
* Who's here?

05 3D Human Pose Estimation 
* Who's here?

06 Training and Deploying a Hand Motion and Item Classifier
* Whatcha up to?

07 Training and Deploying a Custom Item Classifier
* Whatcha holding?

08 Temporal Association
* Who has what item?

09 Autonomous Checkout Pt. 1
		
# EXPERIMENTS AND RESULTS

* Accuracy
* Computation Speed
* System Requirements
* Model Size
* Other
* Datasets and Protocols
* Results

# DISCUSSION

# POLICY MEMO

* How will the profits that accrue from increasing automation be reinvested back into communities for collective gain?
* An automation tax taken on by industry and citizen could fund an independent accountability group to help communities revisit their computer vision policies. It could help neighborhood shops and local authorities investigate public complaints regarding computer vision/privacy. These recommendations are an idea in progress. I'm reading up on regulation, rules, accounting standards, community opinion and new interpretations of laws.

# BIBLIOGRAPHY

* The Great Good Place by Roy Oldenburg (1989)

* Capitalism, Socialism and Democracy by Joseph A. Schumpeter (1950)

* Writing Ethnographic Field Notes, 2nd Edition by Emerson, Fretz and Shaw (2011)

* Deep Learning, An MIT Press Book by Ian Goodfellow and Yoshua Bengio and Aaron Courville (2016)

* "Fast Online Object Tracking and Segmentation: A Unifying Approach" (2019)

* "Monocular Real-time Hand Shape and Motion Capture using Multi-modal Data" (2020)

* "Deep Reinforcement Learning from Human Preferences" (2017)
