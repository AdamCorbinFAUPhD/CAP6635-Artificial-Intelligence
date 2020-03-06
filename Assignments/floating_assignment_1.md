# Notes on week 1 - Whats AI
1. Differences between ANI and AGI
  - Artificatil narrow intelligence - smart speakers, self-driving cars
  - Artificatil general intelligence - basically to be as smart as a human
1. Machine learning
  - Supervised learning - Finding mappings between inputs to outputs. 
  - Data 
    - Usually a table of information
    - Labeling data - Identifying an attribute value to an item of the data. It can be manual or can it be derived based on the data it self
    - How to use data the wrong way 
      - The discussion between I will collect data and then analize it many years down the road. 
    Its best to start analysing the data right away because you can learn sooner about the data and make piviots if needed
      - More data doesnt mean its the best. Its possible that this data doesnt provide any value or lacks perspective.
    - Data is messy or incorrect. There can be cleaning of data or incorrect data that can throw off the AI.
      - Structured data in tables or unstructured data like text 
  - Terms
    - Machine Learning - basically there are inputs and it splits out outputs. Usually an algorithm
    - Data Science - coming up with hypothisis , run test to support the hypotisis or dispove. Usually lots of documents to support the algorithm in a way to drive information or ideas like business insights
    - Deep learning - Artifical neual network. Takes many inputs to come up with an output. Add screenshot of neural network. Neral netowek is not like the human brain in nerons
  - whats an ai company
    - Talking about how internet companys can piviot fast unlike traditional companieis such as a shopping mall. That means they can tests lots of things quickly to undersand consumer behavior.
    - They are good figure out which data to collect, possible providing free services which they could then leverage that data to sell insights to someone else. Also its important to have the data all organized simulary so that it can be processed smoothly
  - AI Transformation
    1. Pilot Projects - Investigation about AI with small projects to get a feel for what it should look like and behave like.
    2. Set up infastruction - Companys can then take the lessessons learned from the pilot projects and set up standaization around data warehousing. This is improtant to streamline and AI projects
    3. Training - Ensure that the teams are adiquatly training to peform the tasks of these new roles and even managers so they have an awareness to the projects
    4. Strategy - As many good projects and vetures go, setting up a good strategy to allow the whole team to undersand what the roadmap will look like.
    5. Communication - Ensure that everyone within the project is on the same page as well as how teams are comuncationg to the outside teams so they dont have any contradictions. 
   - What AI can & Cannot do
     - Rule of tumb - If a human can do the task quicky that AI most likely could do the task. For example taking an audio file and converting it to text. A poor example would be take some market research and output a 50 page analysis report 
     - In general there it can be challenging to say if AI can do a task so it might mean taking some time doing investigation to prove out some theorys 
    - fiesability basically if the task can be done in a short time frame such as seconds and if that task has the oppertinity for lots of data then it could mean a good canidate for ML
  - Overview of Nurl network. 
    
# Notes on week 2 - building projects
- Steps for Machine learning project
  - Collect data
  - Train model
  - deply model
- Steps for Data Science project
  - Collect data
  - Analyze data
  - Suggest hypotheses or actions. loop back to the top
- Usages for Data Science vs Machine learning
  - Recruting
    - Data science can be used to analzie the recruting funnel to view each step. Based on that analysis you can make recmendations to how to improve the recruting funnel. Over time that data can help make educated decisiosne
    - For Machine Leanring there could be a model build where you feed in resumes and it will classify if the person should be a canidate to be interviewed. This can be challenging in the case that the model potenticall could be biased depending on the model development.
 - How to pick an AI project
    - Consider having an AI expert and a Domain expert to be apart of the project
    - Intersting point discussion AI replacing jobs, Andrew discusses that we should consider breaking down a job into many tasks. These tasks could be more efficent for an AI to to but posssibly an AI to do all of the tasks might not make sense.
    - Another key aspect is to thinkg about what business value is this project going provide
    - Last point would be look for pain points in the current system and see if AI can help solve those problems
    - Andrew says that we dont really need huge dataset to use AI for good. Its possible to try to leverage small data sets to prove out ideas
    - Two aspects to think about before kicking off an AI project. One that the project is feisable to undersand that tecnically it can be done. Second that the project is valueable to the business
    - Buid vs buy condrum - Machine learning ususally buy could be faster up front but maybe not as flexible. Data Science usually all done inhouse
  - How to work with an AI team
    - Specify the acceptance criteria
    - Splitting the data between the training set and the test set. The training set will take all the inputs to build a model and then will be tested on the test set. Sometimes an AI team will want to use 2 different test sets.
    - Some pitfals would be miss classification of data sets, not enough data to analize, or missing classification. 
  - Tools
    - ML Frameworks - TensorFlow, PyTorch, Keras, Scikit-learn
    - research - Arxiv
    - Open Source software - GitHub
    - CPU vs GPU. GPU has been found to be useful for nurel networks. 
    - Cloud vs on-prem(ises)
      - Edge deployment. Example would be a car that doesnt have enough time to upload to cloud to crunch numbers so some computations happen right on site. Putting a processor right next to where the data is collected.
# Notes on week 3 - AI in your company
- Dive deep on a smart speaker
  - create a wakeword
  - speach recoginition to listen. converts audo to text and if that wakeword is found then it will activate
  - Intent recognition - spcicify commands when talking to the smart spearker. Such as whats the time, whats the weather. There can be many different kind of combinations of words that link of to the same Intent. For example: "whats the weather", " can you tell me the weather", "whats the forcast today"
  - Back end running of a program. This is predefined code that build to handled the intents
- note: in general these steps comprise of an AI Pipeline. No all AI Pipelines have the same steps but that what we call an AI Pipeline.
- There is a video on self driving cars. Consider diving deeper but its simular to the Smart speaker.
- Roles in AI
  - Software enigneer, responsible to creating that back end of executing a job
  - Machine learning engineer - Someone who takes pre existing ideas of ML and applying them to current problems
  - Machine Learning Resaecher - Mainly looking for new ways to apply ML
  - Applied ML Scientist - mixtur of the 2
  - Data Scientist - Looking at data, developing ideas or insights to present to decision makers.
  - Data Engineer - someone who orgnaizese the data.
  - AI Product Manager - someone to help come up with ideas to apply AI to problems
- AI Playbook
  - Pilot projects. Consider trying to make simple projects that would be succcessful. Trying to gain momentum. 
  - AI team - Using an AI team and matrix them into different organizations. This will alow the AI members to work with the domain experts. Consider the compaty to provide funding first vs having the business units to providie funding. Add screenshot time 6:40 @ AI Transformation palyboo(part1)
  - Training - Execs need to training so they are aware of some of hte terms and usages. Leaders of divisions - how to manage a prodct and give direction to where the project should go. AI devs - using online reseouces, other team members in house that might know the information
  - Strategy - Andrew talks about how its sometimes important to not come up with a stratefy up front becuase it might be accidemic in nature and might not lean well towards the consumer or project. this is espically good if you or your team is new to this concept.
    - Virtuous cycle of AI - basically where the product is good, which means it gets more users which then it gets more data to improve. Making it difficult for entry level products to enter the market.
    - come up with some product that might be free but to collect data. this data collection would be used to improve your product making it more valueable 
  - communication between AI and all parities
    - Undersanding the external customers like investors or the goverment and effecticly communicate what the prodcut is trying to accomplish
    - Having a clear vision about your proct that can be communcated well can also help with recurting top talent. 
    - lastly ensureing that internal stakeholders or customers are undersanding of the product 
- AI Pitfalls
 - Not have high expecations that AI is going to solve all of your problems but undersand that AI can be a great leveraging tool if you use it well
 - Hiring a set of ML Engineers need to be paired up with domain experts 
 - AI is an itteravie process so make sure you dont set high expecations up front.
## Tecnical applications
- Computer vision which can be used to identify objects or classify objects based on shapes and colors. An applcation would be face recgonition. There is also an application called Image segmentation which wil define a clear outline around an object.
- Natural language processing 
  - An applciation would be to take emails and clasify them as spam or a good email.
  - Web search is another applcaiton where a text input gets convert to a relevent website.
- Speech
  - Taking an audio file and converting it to text based. 
  - Speaker ID where an person can be identified by their speach
- Robotics
  - Perception to underdand what objects are around its surrounding
  - Motion planning to try to schedule where the robot plans to move to
## Unsuperived learning
- clustering <insert picture> algo can group data into small chunks. Used often for market segmentation problems. The concept here is that the algos try to find meaningful representation without an input guiding it.
- It can take a lot of data to train something that would be able to identify something with supervised learning. There is nope that Un-supervised learning could be a key contributor to undsersanding how to itendify something with smaller datasets
- Transfer leanring. An example would be to build a model for detecting cars with 100k images, and take that model and update it to try to identify golf carts with only 100 images
- Reinforcement learning - Kinda how you would training a dog. Prais it when it did something good, and let them know when they did something bad. Using a "reward signal" to train the system. It takes a lot of data to build these models. 
- General Adversarial network(GANs) used to create images from scratch and help improve image qualirt
 
# Notes on Week 4 - AI Biases 
## AI and Socciety
- Goldilocs rule to just set your expecations level. Bing to optimisitc to super AI and that it will take over the world can be considered a waste of energy since there is not a clear path anything like that in the near future. Bing too pessimistic such as AI cant do anything so why bother with it about how another AI winter is coming. At that time in past for AI winter it was hyped up too much and didnt bring much value at the time. Today AI is bring ecnomic value so its not over hyped. 
- Sometimes AI is look down upon becuase it cant explain it self on how it made its decisions.
### AI Bias
- There have been studies that have been found that AIs have parsed some data from online to build some relationships and found that it can be bias. For example if you told AI man to woman as Father it would come up Mother. A bias example was Man to Computer programmer as Woman would come up with homemaker which is not a good representation. Insert picture from video bias ~ 4:10. 
- Hiring company created an AI tool and found that it was picking a select demographic. This tool was later decommision due to the bias.
- Solutions would be to use inclusive data or less biased data. Also having some audition processes such as having different types of training sets to ensure that the system is staying unbysaed. 
### Adversarial attacks
- Its possible to add some data that doesnt look obvious to a human but it throws off the AI by a lot. Insert picture at 1:31. We have an example here were some pixels were changed and AI is not classifying this as a hammer where it hsould be a humming bird
- There are some physical attacks such as adding a sticker to make it think that an object or an object has a toaster in the image.
### Adversaruak defenses
- Can have some changes to the Neural netowrks but the systems might run a little slower.
- Some systems wouldnt make sense to do this such as trying to fool a good email into that its a spam email.
### Adverse use of AI
- DeepFakes - AI used to make people look like they said something when they really didnt. Buzzfeed posted a video of obama of the first one that became popular but also said he was fake. <insert link>
- Some goverments can use this to monitor their citicents and evade human privacy
## AI and Developing economies
- The concept would be to have AI automate some of the lower end jobs but to use that econmic savings to help leapfrog people upward on the economic ladder. Example would be Mobile payments, in some countries such as indian, they didnt bother building all the landlines, insead they focused on building the wireless infrastructior to support wireless communication. 
## AI and Jobs
- McKensey Global Institute did a study that estimated that between 400-800 milion jobs would be displaced but on the flip side they found that AI would generate between 555-890 million jobs 
- Usually jobs that have routines have high likely that AI could impact 
- some suggested solustions would be to have lifelong learning socicety or a conditional basic income to help provide a safty net but incentivize learning. 
