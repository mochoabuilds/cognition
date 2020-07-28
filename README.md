*** WORKING PAPER ***

*** ATTACHED CODE FOR PROOF-OF-CONCEPT (PEOPLE/FOOTFALL COUNTER) ***  

*** YOUTUBE LINK TO PEOPLE/FOOTFALL COUNTER ***

# INTRODUCTION
+ Corner stores serve many roles beyond providing essential goods. They are inherently valuable spaces amid the pandemic. Yet coronavirus has given us new ideas on how to occupy corner stores in a modern society. New ideas carry new notions of law, time and social rhythms.  It means loss as well as gain.
+ My research pulls together something like a work bench to build new tools for corner stores. The focus is on making the tools feel like a natural extension of the existing corner store experience. To do this I start with ethnographic data and develop optimization approaches that emphasize formal logic, categories and brute computational force to bake "street smarts" into computer vision applications.
    
# RESEARCH QUESTIONS
+ How can we bake human-like "street smarts" into computer vision applications?
+ How could we underpin a computer vision system with a public log of all queries run on its video stream data? ("thus the watchers themselves are watched")

# "DATA PREP"
+ The data I start with to develop theory comes from ethnography.  What is ethnography? It's a sociological method of firsthand participant observation in once unfamiliar social circles to pull a sense of what's relevant in that world.  Methods include: personal responses, sensory impressions, neighborhood identities, human behaviors, jottings, etc. 
+ I undertook approximately 10 months of ethnography in two Chicago corner stores. Next I developed a method for getting ethnographic field notes into a coherent, usable data for computer vision applications.

# PRODUCT DESIGN
+ The device combines the functions of LIDAR and RADAR to measure the different speeds of items in one's hands as they move about a corner store.  This approach better avoids interference with other optical sensors, reflective objects, clothing, lighting, etc. 
+ I design this product around a "Chicago global" look inspired by music.

# COMPUTER VISION 
+ Through a combination of data prep, off-the-shelf hardware, reinforcement learning algorithms, reward functions and human feedback our system learns. The device syncs specific locations and items in a room with classifiers across parent-child groupings.  Feedback from humans fine-tune the reward function to bake human-like "street smarts" into the applications. Ideally our modern tools will multiply the efficiency of the corner store while preserving the fabric of the space.

# TIMELINE
+ Winter 2018 — Spring 2020 
    + Literature Review & Ethnography
+ Summer 2020 
    + People/Footfall Counter for Corner Stores & Product Design
+ Fall 2020
    + Inventory Mgmt for Corner Stores (Hand Motion & Item Classifier)
+ Winter 2021
    + "Who has what object?" (Autonomous Checkout Pt. 1)

# PROOF-OF-CONCEPT
01 Installing Required Packages and Libraries 
+ Python
+ OpenCV https://opencv.org/
+ dlib http://dlib.net/a

02 Configuring Edge Computing Device
+ Prep
+ Notes
+ Code

03 Footfall/People Counter | Counts the # of people entering and exiting a room 
+ Prep
+ Notes
+ Videos
    + .avi
    + .mp4
    + .mp4
+ Output
    + .avi
+ cognition
    + init__.py
    + centroidtracker.py
    + directioncounter.py
    + trackableobject.py
+ people_counter.py

# FALL 2020 & WINTER 2021
04 Installing Required Packages and Libraries 
+ scikit-image https://scikit-image.org/
+ scikit-learn https://scikit-learn.org/stable/index.html
+ Numpy https://numpy.org/install/
+ Keras https://keras.io/
+ Tensorflow https://www.tensorflow.org
+ Caffe http://caffe.berkeleyvision.org/

**05 Translating Ethnographic Field Notes**
+ At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

06A 2D Human Pose Estimation with Tensorflow and Caffe 
+ Who’s here? 
![1-DsOBzKpVMUULGABMVFdVIg](https://user-images.githubusercontent.com/40745550/82762582-6febd280-9dc7-11ea-90ea-0671e1bf3744.jpeg)

06B Feature Extraction 
+ Who's here?

06D 3D Human Pose Estimation 
+ Who's here?

07 Training and Deploying a Hand Motion and Object Classifier
+ Whatcha up to?

08 Training and Deploying a Custom Objects Classifier
+ Whatcha holding?

09 Temporal Association 
+ Who has what object?

10 Action Analysis Based on Location 
+ Guest Receiving bill via SMS for Mobile Payment Upon Store Exit

# V. EXPERIMENTS AND RESULTS
+ Summary Statistics
    + Accuracy 
    + Computation Speed
    + System Requirements
    + Model Size
    + Other
+ Datasets and Protocols
+ Results

# DISCUSSION

# POLICY MEMORANDUM 
+ How will the profits that accrue from increasing automation be reinvested back into communities for collective gain? 
+ Working Answer1: In a society that respects labor rights, each person would receive a cash payment equal to their share of the value of an automation-tax, taken on industry in pursuit of economic gain.  Fee proceeds called the “universal basic dividend” would go to all in that community, dispersal tbd.  An automation-tax on such systems also provides industry with an incentive to ensure sufficient re-training, especially of low skilled workers or they bear the full brunt of the automation-tax. An automation-tax could also fund an independent accountability group as we write and refine computer vision policies. It would help shoppers, corner store mgmt and local authority investigate public complaints that are available and easily searchable. We must analyze complaint cause and question methods to design effective computer vision policies.  An automation-tax would fund this.  This is an idea in progress. I'm still reading up on regulation, rules, accounting standards, disclosure standards, stewardship codes, community opinion and new interpretations of laws.

## SANDBOX
+ Show it’s possible to get interesting services without egregious and invasive privacy practices (NO FACE RECOGNITION)
+ Better handling the 10% of "edge cases" (unusual cases that are not common in training data)
+ Branching object persistence models across multiple cameras
+ Better understanding the front-back orientation of human limbs due to clothing, lighting, background
+ Lower processing power bills and bridge the Edge-Cloud barrier
+ Determine the metrics that improve downstream performance
  
## BIBLIOGRAPHY
+ The Great Good Place by Roy Oldenburg (1989)
+ Writing Ethnographic Field Notes, 2nd Edition by Emerson, Fretz and Shaw (2011)

+ "Fast Online Object Tracking and Segmentation: A Unifying Approach" (2019)
+ "Monocular Real-time Hand Shape and Motion Capture using Multi-modal Data" (2020)
+ "Exploiting Temporal Context for 3D Human Pose Estimation in the Wild" (2019)
+ "Deep Reinforcement Learning from Human Preferences" (2017)
