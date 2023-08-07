#   Procedure
1. Create repo on github
2. Clone to desktop with GH Desktop app
3. Follow instructions from https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll
4. But when bundle install fails in step 2.5, use:
   1. sudo gem install bundler -v '1.16.1'
5. When you get error bundler could not file compatible versions, follow suggestions and run
   1. bundle update
6. sudo gem install jekyll bundler
7. Edit Gemfile.lock to use Bundled With 2.0.1

#  Fonts
In settings.yml, original values were:

font_embed: '<link href="https://fonts.googleapis.com/css?family=Muli:300,400,600,700" rel="stylesheet">'
  title_font: '"Muli", sans-serif'
  body_font: '"Muli", sans-serif'

## New Potential Fonts
###   Manrope
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;600;700&display=swap" rel="stylesheet">

font-family: 'Manrope', sans-serif;

###   Inter Tight
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter+Tight:wght@300;400;600;700&display=swap" rel="stylesheet">

font-family: 'Inter Tight', sans-serif;

###   DM Sans (from Curate Template by jekyllthemes.io)
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,600;9..40,700&display=swap" rel="stylesheet">

font-family: 'DM Sans', sans-serif;

### Colors
####  TODO: Make body text higher contrast
Prior Values
text_dark_color: '#2A2F36'
  text_medium_color: '#6C7A89'
  text_light_color: '#ABB7B7'

Change to: (bluish gray ting)
dark: #000000
med: #1c2833
light: #2e343b

Accent color / overlay background color prior: #F2784B
Mclaren Papaya Orange: #ff931b