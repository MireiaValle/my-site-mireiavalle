# my-site-mireiavalle

#Attach `blogdown` (once per session):

library(blogdown)

# Check the verson of hugo:
blogdown::hugo_version()

# Note: you can also check for hugo updates if you're working on this later on:
blogdown::update_hugo()

# Create your new site

new_site(theme = "gcushen/hugo-academic", 
         sample = TRUE, 
         theme_example = TRUE, 
         empty_dirs = TRUE,
         to_yaml = TRUE)

#To visualize your site
blogdown::serve_site()

#Create netlify.toml file
file.create("netlify.toml")


#To be added
#Projects: Sweden/PhD
#Publications: all 
#awards: IPBES
#Courses: list of courses