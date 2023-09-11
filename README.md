# Drupal-10-basic-setup
Basic setup for Drupal 10

1. Run ```git clone https://github.com/QZtweede/Drupal-10-basic-setup.git YOUR_WEBSITE_NAME```, change ```YOUR_WEBSITE_NAME``` to the name of your project
2. Make a git environment, in your new directory run ```git remote set-url origin YOUR_GIT_URL```, change ```YOUR_GIT_URL``` to the URL of your git environment
3. Run ```git branch -M main; git push -uf origin main```
4. In your browser, go to the YOUR_WEBSITE_NAME/web in your web environment (f.e. localhost/YOUR_WEBSITE_NAME/web), run the setup
5. After running the setup, navigate to Appearance, then to Uninstalled themes, install 'Custom bootstrap SASS' and set as default

Now you've succesfully made a Drupal web environment. 

Recommended further steps:

6. Navigate to Extend, install 'Media' and 'Media Library'
7. In your terminal, navigate to your base Drupal directory, and run ```composer require 'drupal/twig_tweak'```. Also install this in Extend.
