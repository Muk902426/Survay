Feedback Survay Module For Magento2

The Survey Form serves as a specialized tool within the Magento2 platform, facilitating customer feedback and data collection. Its purpose is to offer website visitors a streamlined method for expressing their experiences and providing suggestions. Operating in a straightforward manner, this tool is ideal for customers seeking to gather personal information from website visitors and empower them to share their thoughts and ideas

Step 1: Unzip the file in a temporary directory
Step 2: Upload it to your Magento installation root directory
Step 3: Disable the cache under System >> Cache Management
Step 4: Enter the following command at the command line:
php f bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
php bin/magento cache:flush
