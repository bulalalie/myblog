# myblog
This site was configured by HUGO which is a framework for building websites.

## How to generate my blog page
1. Download hugo framwork and install it on your OS. 
brew install hugo

2. Create a site 
hugo new site

3. Download themes，suggest go to Hugo base-site to find the themes "https://themes.gohugo.io/" 
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

4. Define the themes in the config file. 
echo "theme = "ananke" >> config.toml

5. Generate a new artical 
hugo new posts/.md

6. Compile and generate static pages 
hugo

7. Deploy it on the local web server and go to check the site items. 
hugo server