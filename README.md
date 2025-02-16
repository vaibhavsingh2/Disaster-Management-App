# Disaster-Management-App

For our hackathon on February 16th at IIIT NR, we developed an innovative Disaster Management App designed to address critical challenges in disaster relief.

The problem statement we tackled was:

# Disaster Relief Coordination Platform

During natural disasters, relief efforts often face communication gaps, inefficient resource allocation, and delays in reaching affected communities. Your task is to develop a real-time disaster relief coordination platform that uses crowdsourced data, geolocation tracking, and AI-driven demand prediction to streamline aid distribution. The platform should enable volunteers, NGOs, and government agencies to coordinate relief efforts effectively and respond faster to emergencies.

Through this project, we aimed to bridge the gaps in disaster relief efforts, enhancing coordination and impact when it matters most.

# Functionality of the project

1) On our homepage, we have integrated an intelligent chatbot designed to assist users in navigating natural disasters effectively. Built using Botpress, this chatbot provides real-time guidance, offering crucial tips on how to respond to various emergencies. By interacting with the bot, users can receive instant, situation-specific advice, empowering them with the knowledge to stay safe and make informed decisions during a crisis.

2) To ensure the authenticity and reliability of information, we have restricted the ability to add announcements solely to the government authorities, while the general public can only view the updates published by them. This guarantees that all announcements remain credible and authoritative.

However, in cases where duplicate entries, accidental additions, or unauthorized modifications occur—whether due to human error or malicious activity—we have implemented a dedicated admin page. This page, accessible only to us, allows for the swift removal of any incorrect or misleading disaster reports, ensuring that the platform maintains accuracy and integrity at all times.

3) We have designed a Contribute Page where users can support disaster-affected individuals through donations. When a picture of a disaster is posted, it signifies that all funds collected during that time will be directed toward aiding those injured in the calamity.

To honor and appreciate the generosity of contributors, we also maintain a donor recognition system, displaying the names of those who have extended their support. This not only fosters transparency and trust but also encourages a sense of community and shared responsibility in times of crisis.

4) We have developed a Live Location Tracking Page that utilizes the Geolocation API to determine a user’s precise longitude and latitude in real time. This system continuously monitors disaster occurrences within a ±5-degree radius of the user's location.

If the platform detects 100 or more disasters within this range, the default "Safe Zone" status will automatically switch to "Unsafe Zone" for all individuals in that area. This feature enables proactive awareness, helping communities stay informed and take necessary precautions when disaster risks escalate.








