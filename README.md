# ECE-750-Project
<h1 align="center">Exploring Humanoid Robot Integration for Elder Care: A Study on Non-verbal Interaction and Health Monitoring with NAO</h1>

<p align="center">
  <strong>S M Taslim Uddin Raju</strong><br>
  Department of Electrical and Computer Engineering<br>
  University of Waterloo, Waterloo, ON, Canada<br>
  <a href="mailto:smturaju@uwaterloo.ca">smturaju@uwaterloo.ca</a>
</p>

<div style="text-align: justify;">
  <h3>1. Motivation</h3>
  <p>Robots offer new possibilities. This proposal aims to explore the integration of humanoid robots, such as NAO [1], for elderly caregiving. Robots have gotten better and can help people in many ways. Human-robot interaction is about how people and robots work together. In Canada, there are a lot of older adults who need someone to help them. While traditional practices involve hiring human caregivers to serve meals and attend to basic needs, the elderly often require continuous companionship and health monitoring. However, hiring human caregivers for this job costs a lot of money. But using a robot like NAO could be cheaper and still helpful. NAO isn’t just any robot; it blends technology with empathy. With expressive eyes and graceful movements, NAO connects with the elderly. It can keep the elderly company and check their health using special sensors. The cost-effectiveness is a bonus—NAO doesn’t demand a paycheck. This idea inspired me to work on this project.</p>
</div>

<h3>2.	Background of  Project:</h3>
Human-robot interaction (HRI) is a rapidly expanding discipline exploring how humans and robots work together. It's not just about language-based interaction but also includes all aspects relevant to communication among physical beings [2]. On the other hand, non-verbal communication plays a vital role in HRI. Non-verbal behaviors of robots are the most effective way to influence human perception and engagement. It includes kinesics (body movement), proxemics (spatial distances), haptics (touch), and chronemics (time), as well as combinations of these modes[3].

Numerous studies have been done where humanoid robots are used for various disciplinary fields through non-verbal cues. Akalin et al. [4] demonstrated the effectiveness of a robot designed for elder care in terms of security and safety. A Pepper robot with nonverbal gestures like arm gestures and head nodding was used. In another study, NAO [5] robots used iconic gestures to support children's language learning. In [6], the authors used the Pepper robot to assist people with dementia in assessing the perceptions of care partners and healthcare workers. Mišeikis et al. [7] presented how Lio can be used for personal assistance and care applications. These studies motivated me to use humanoid robots like NAO for older caregivers for companion and healthcare monitoring.

<h3>3. Research Question(s)</h3>
<ol>
  <li><strong>RQ 1:</strong> How do participants perceive when robot NAO touches to monitor the participant’s health?</li>
  <li><strong>RQ 2:</strong> How well can NAO monitor and report the health status of older people by touching them?</li>
  <li><strong>RQ 3:</strong> What factors influence older people’s trust and acceptance of NAO as their companion and caregiver?</li>
</ol>

<h3>4. Non-verbal Behavior: </h3>	
In my project, I will plan to implement two non-verbal behaviors. 

<h4>4.1 Non Verbal Behavior: </h4>	 
<ol>
  <li><strong>Gesture:</strong> It involves hand and arm movements, body language, facial expressions, and eye movements.</li>
  <li> <strong>Touch:</strong> It involved in physical contact or tactile interactions to convey messages or emotions.</li>
</ol>
   <h4> 4.2 How Implement: </h4>	  
<ol>
  <li><strong>Gesture:</strong> For gesture, I will NAO’s built-in gestures library, which includes a variety of hand and arm movements, eye movements for entertaining the older people. </li>
  <li> <strong>Touch:</strong> For touch, I will use NAO’s tactile sensors, which are located on its head. It can measure abnormal signs or symptoms. </li>
</ol>

<h3>5. Pretend User Study (Study Design)  </h3>

 <h4>Experimental Setup </h4>	
- The Webots simulation environment will be used to create a virtual caregiving scenario.
- The simulated robot, NAO, will be programmed with gesture and touch interactions.

 <h4>Procedure</h4>
- Each participant will interact with the virtual NAO robot in the virtual caregiving scenario.
- The robot will communicate with the virtual elderly through gestures and touch, and it will pretend to check their health.
- During the robot's entertainment gesture routine:
  - If an elderly individual gives a "thumbs up," it signifies happiness.
  - A "thumbs down" indicates dissatisfaction.
  - A "halt" gesture signifies a request to stop.
  
 <h4> Data Collection</h4>
- Data will be collected on the frequency and types of gestures and touch interactions performed by the virtual NAO, along with participants' reactions.
- Quantitative data will be gathered through online forms, where participants rate the robot's gestures, touch interactions, and satisfaction.
- Qualitative data will capture participants' feelings and perceptions of NAO's behavior.

 <h4>Research Questions</h4>
### Research Question 1: Perception of Gesture
- **Question:** How satisfied are you with the gestures made by NAO during interactions?
  - **Scale:** 1 (Strongly Dissatisfied) - 5 (Strongly Satisfied)

### Research Question 2: Effectiveness of touch interaction for health monitoring
- **Question:** How confident are you in NAO's ability to accurately measure your health through touch interactions?
  - **Scale:** 1 (Not Confident at all) - 5 (Very Confident)

### Research Question 3: Trust in NAO and concerns about safety
- **Question:** How much do you trust NAO to prioritize your safety during interactions?
  - **Scale:** 1 (Not at all) - 5 (Completely)

### Ethical Considerations
- As this is a virtual simulation, ethical considerations will be different but still significant. Participants should still provide informed consent and maintain privacy.

<h3>6.	Data Analysis </h3>
I'll create a Google survey form and distribute it via email or social media to gather user feedback. The data will be analyzed by combining both qualitative and quantitative methodologies. Statistical methods will be utilized for quantitative analysis. A one-way ANOVA test will be applied to identify significant differences, like comparing means across multiple groups, allowing for an evaluation of how various situations impact respondents' experiences and perspectives. An independent sample t-test could assess any group differences in the second set of study questions, specifically focusing on respondents' opinions regarding touch interactions for health monitoring. Qualitative analysis will involve thematic analysis of open-ended survey questions to explore users' perspectives and experiences with humanoid-robot interaction


## References
[1] A. Robaczewski, J. Bouchard, K. Bouchard, and S. Gaboury, “Socially assistive robots: The specific case of the nao,” International Journal of Social Robotics, vol. 13, pp. 795–831, 2021.

[2] A. Bonarini, “Communication in human-robot interaction,” Current Robotics Reports, vol. 1, pp. 279–285, 2020.

[3] S. Saunderson and G. Nejat, “How robots influence humans: A survey of nonverbal communication in social human–robot interaction,” International Journal of Social Robotics, vol. 11, pp. 575–608, 2019.

[4] N. Akalin, A. Kiselev, A. Kristoffersson, and A. Loutfi, “An evaluation tool of the effect of robots in eldercare on the sense of safety and security,” in Social Robotics: 9th International Conference, ICSR 2017, Tsukuba, Japan, November 22-24, 2017, Proceedings 9. Springer, 2017, pp. 628–637.

[5] J. de Wit, A. Brandse, E. Krahmer, and P. Vogt, “Varied human-like gestures for social robots: Investigating the effects on children’s engagement and language learning,” in Proceedings of the 2020 ACM/IEEE international conference on human-robot interaction, 2020, pp. 359–367.

[6] Y.-J. Liao, Y.-L. Jao, M. Boltz, O. T. Adekeye, D. Berish, F. Yuan, and X. Zhao, “Use of a humanoid robot in supporting dementia care: A qualitative analysis,” SAGE Open Nursing, vol. 9, p. 23779608231179528, 2023.

[7] J. Mišeikis, P. Caroni, P. Duchamp, A. Gasser, R. Marko, N. Mišeičienė, F. Zwilling, C. De Castelbajac, L. Eicher, M. Früh et al., “Lio-a personal robot assistant for human-robot interaction and care applications,” IEEE Robotics and Automation Letters, vol. 5, no. 4, pp. 5339–5346, 2020.



[^1]: A. Robaczewski, J. Bouchard, K. Bouchard, and S. Gaboury, “Socially assistive robots: The specific case of the nao,” *International Journal of Social Robotics*, vol. 13, pp. 795–831, 2021.
[^2]: A. Bonarini, “Communication in human-robot interaction,” *Current Robotics Reports*, vol. 1, pp. 279–285, 2020.
[^3]: S. Saunderson and G. Nejat, “How robots influence humans: A survey of nonverbal communication in social human–robot interaction,” *International Journal of Social Robotics*, vol. 11, pp. 575–608, 2019.
[^4]: N. Akalin, A. Kiselev, A. Kristoffersson, and A. Loutfi, “An evaluation tool of the effect of robots in eldercare on the sense of safety and security,” in *Social Robotics: 9th International Conference, ICSR 2017, Tsukuba, Japan, November 22-24, 2017, Proceedings 9*. Springer, 2017, pp. 628–637.
[^5]: J. de Wit, A. Brandse, E. Krahmer, and P. Vogt, “Varied human-like gestures for social robots: Investigating the effects on children’s engagement and language learning,” in *Proceedings of the 2020 ACM/IEEE international conference on human-robot interaction*, 2020, pp. 359– 367.
[^6]: Y.-J. Liao, Y.-L. Jao, M. Boltz, O. T. Adekeye, D. Berish, F. Yuan, and X. Zhao, “Use of a humanoid robot in supporting dementia care: A qualitative analysis,” *SAGE Open Nursing*, vol. 9, p. 23779608231179528, 2023.
[^7]: J. Mišeikis, P. Caroni, P. Duchamp, A. Gasser, R. Marko, N. Mišeičienė, F. Zwilling, C. De Castelbajac, L. Eicher, M. Früh et al., “Lio-a personal robot assistant for human-robot interaction and care applications,” *IEEE Robotics and Automation Letters*, vol. 5, no. 4, pp. 5339–5346, 2020.


