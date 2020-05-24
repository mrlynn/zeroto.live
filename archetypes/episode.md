---
title: "{{ replace .Name "-" " " | title }}"
Description: ""
PublishDate: {{ .Date }}
podcast_file: "###.mp3"
podcast_duration: ""
podcast_bytes: ""
episode_image: ""
episode_banner: ""
guests: []
sponsors: []
images: []
hosts: []
aliases: ["/##"]
youtube: ""
spotify: ""
apple: ""
explicit: "no"
date: {{ .Date }}
# media_override: "" if you want to use a specific URL for the audio file
# truncate: 
draft: true
---