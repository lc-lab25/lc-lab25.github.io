---
---

## Advancing Intelligent Robotics Through Learning and Control

Our lab develops both foundational theory and practical tools in machine learning and control to make robots more intelligent. 

On the one hand, reinforcement learning provides a data-driven way for robots to learn decision-making policies through interaction. On the other hand, control theory offers rigorous, reliable design principles that guarantee stability and performance. By combining them, we enable robots to operate safely, autonomously, and efficiently in complex, real-world environments.

**We are actively recruiting undergraduate and graduate students to join our team. Please see [CONTACT]({% link contact/index.md %}) for more information.**

{% include section.html %}

## News and Updates

- **[August 18, 2026]** — We are excited to announce that the LC Lab has received a new $300,000 NSF award for the project **“Integrating Physical Principles and Learning for Safe and Reliable Locomotion of Legged Robots.”** Led by Dr. Leilei Cui, this project will advance our research at the intersection of learning, control, and legged robotics, with a focus on developing safe and reliable locomotion methods.
- **[July 15, 2026]** — We are excited to announce that the LC Lab has welcomed a new Unitree G1 humanoid robot! The robot will serve as an important experimental platform for our research in machine learning, control, and intelligent robotics.

*Last updated: {{ site.time | date: "%B %d, %Y" }}*

{% include section.html %}

## Highlights

{% capture text %}

Our research can be broadly organized into three parts: learning for control, control for learning, and applications to robotics.

{%
  include button.html
  link="projects"
  text="See our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{%
  include button.html
  link="publication"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.svg"
  link="projects"
  title="Our Research"
  text=text
%}

{% capture text %}

We offer courses in the areas of dynamics & control and robotics. 

{%
  include button.html
  link="teaching"
  text="Browse our teaching"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/ME561.png"
  link="teaching"
  title="Our Teaching"
  flip=true
  text=text
%}

{% capture text %}

Our team includes researchers and graduate/undergraduate students passionate about learning and control and their applications to robotics.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/teams.png"
  link="team"
  title="Our Team"
  text=text
%}