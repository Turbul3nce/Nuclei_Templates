# Nuclei Templates 
<p align="center">

<img src="https://github.com/RosePwns/HTB_Challenges/blob/main/assets/rosehacks.PNG"> 
  
</p>

## Overview

This respository is dedicated to nuclei templates I've created for CVEs and other vulnerabilities discovered. Credit is given to creators of the HackTheBox challenges and the rest of the application security community.

## Table of Contents

| Folder        | Description                               |
| ------------- | ----------------------------------------- |
| [cves](./http/cves)   | Templates focusing on known CVEs.             |
| [printers](./http/printers) | Templates designed for printers(Easy Pwns). |
| [vulnerabilities](./http/vulnerabilities) | Templates focusing on vulnerabilities.       |
|  |  |

## Usage
1. Clone this repository: ```git
git clone https://github.com/RosePwns/Nuclei_Templates.git```
3. Install Nuclei: Follow the [official installation guide](https://github.com/projectdiscovery/nuclei#installing-nuclei).
4. Run Nuclei with the desired templates: ```
nuclei -t nuclei-templates/http/cves -u example.com```

Feel free to explore and customize these templates based on your specific testing requirements.

## Acknowledgements
We appreciate the Nuclei project by Project Discovery for providing an excellent foundation for effective and scalable vulnerability scanning. Special thanks to the community for sharing valuable insights and contributing to the continuous improvement of security testing tools.

Happy scanning and happy hunting!
