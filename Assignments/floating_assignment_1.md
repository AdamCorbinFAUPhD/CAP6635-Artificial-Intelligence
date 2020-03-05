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
  - Strategy
  - communication between AI and all parities
# Notes on Week 4 - AI Biases 
