# required by disqus to display comments
url: https://your-site-url

# jekyll-paginate
paginate: 5
paginate_path: "/blog/page:num/"

# jekyll-tagging (optional)
tag_permalink_style: pretty
tag_page_layout: tag_page
tag_page_dir: tag

# for github pages custom domains:
# include: [CNAME]

dash:
  # the way how dates should be displayed
  date_format: "%b %-d, %Y"

  # (optional) discqus comment configuration
  disqus:
    shortname: <your-disqus-shortname>  

  # the animation speed of the post scroll-in effect
  animation_speed: 50

  # wether to enable Right-to-Left support or not
  rtl: false

  # Replaces the default avatar provider (gravatar)
  #avatar_source: github
  #github_username: bitbrain
  #avatar_source: local
  #avatar_path: /assets/avatar.png

  # generate social links in footer
  # supported colors: green, red, orange, blue, cyan, pink, teal, yellow, indigo, purple
  social_links:
    - url: https://twitter.com/bitbrain_
      icon: twitter-square
      color: cyan
    - url: https://bitbrain.itch.io
      icon: itch-io
      color: red
    - url: https://github.com/bitbrain
      icon: github-square
      color: purple
  
  # wether the author box should be displayed or not
  show_author: true
