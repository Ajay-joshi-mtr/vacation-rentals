# VRCore [Work in progress!] 

[![Greenkeeper badge](https://badges.greenkeeper.io/ahmadawais/vacation-rentals.svg)](https://greenkeeper.io/)
Add vacation rentals to your WordPress site with membership, agents, partners, search, and frontend booking features. [Documentation →](http://documentation.wpvacationrentals.com/)

![](https://i.imgur.com/hV31YF3.png)
![image](https://i.imgur.com/KLCnYOM.png)![image](https://i.imgur.com/0RP1qxJ.png)
![image](https://i.imgur.com/GIgNQKU.png)
![image](https://i.imgur.com/LKDEPDE.png)
![image](https://i.imgur.com/edLpOMe.png)
![image](https://i.imgur.com/Yk2OGF6.png)

## Architecture
- `vr-core.php`: Main plugin file that includes `vrc.php`
- `vrc.php`: Main initializer for everything

### Design Pattern
Let's assume we are building a functionality called `feature`
- Folder: `feature` 
- File: `feature-init.php` includes everything classes and actions/filters
- File: `class-feature.php` main class that interacts with other small classes
- File: `cpt-feature.php` class for the Custom Post Type
- File: `ct-feature-taxonomy.php` class for the custom taxonomy
- File: `feature-custom` a custom class for a sub-feature
- File: `class-feature-meta-boxes` class for related meta boxes

Copyright Ahmad Awais | WPTie | WGA.
