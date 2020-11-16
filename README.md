## Introduction

I am currently attending the Deep Dive Coding Java + Android Bootcamp. My plan after graduation is to look for employment or contract work in Android app development.
    
## Projects

* [albuquirky: Android app](https://https://github.com/albuquirky/albuquirky-service)

* [ABQ Murals Online: Web Site](https://github.com/Art-Mural-Devs/Art-Mural)

* [Codebreaker: Android app](https://github.com/John-Jaramillo/codebreaker-android-v2)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/john-jaramillo-5172521b3/)