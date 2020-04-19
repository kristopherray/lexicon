# Lexicon
## A Personal Dictionary Theme Website
[Setup Tutorial](https://docs.google.com/document/d/1wd_NZh5QIBBUOIrcPCL0HG_RsEcF9e9A_sl1IXvw7I8/edit?usp=sharing)

I built Lexicon to be an easy to deploy, uber-simple, some-what quirky, solution for anyone's own "personal" website. Use it to catalog the ever-evolving definition of your life, and share all your other various profiles and accomplishments, in one place, your own website.

### Examples:
- [KristopherBolleter.com](https://kristopherbolleter.com)
- [OliverRay.com](https://oliverray.com)

Author: [KristopherRay.com](https://kristopherray.com)

*built with [Hugo](https://gohugo.io)* and :heart:

**Required for Deployment** 
- Netlify
- Github Repository
- NetlifyCMS (packaged in this Repository)

**Local Dependancies: (optional)**
- [ >= Hugo v0.69.0 - Extended](https://github.com/gohugoio/hugo/releases/tag/v0.69.0)  
For more information on using Hugo [View the Documentation](https://gohugo.io/documentation/)

### [How to Launch a Website with Lexicon :link:](https://docs.google.com/document/d/1wd_NZh5QIBBUOIrcPCL0HG_RsEcF9e9A_sl1IXvw7I8/edit?usp=sharing)
Follow the steps in this tutorial I wrote (less than 10), and you'll have your very own website up in 30 minutes or less! And there are even 'lite' customization options available, make it your own. 

### Configuration Options
If you follow the tutorial, all the settings and configurations can be configured via the NetlifyCMS easy to use GUI.
 
 However, if you want to skip the NetlifyCMS stepa entirely, all your settings and content will be configured in the `content/_index.md` file. The top of this file is YAML, contained inside opening and closing `---`, these are used for setting and inserting content into the theme. Under the YAML, is the Body content, written in Markdown.
 
| YAML Variable | Content |  Description  |
| ----------- | ----------- | ----------- |
| animation | Animation | Select from Flip In, Fade In, Slide In Left, Slide In Right, Bounce |
| title | Your Name |  Used as the h1 and meta-title |
| decription | Meta Description | Used for all open-graph and meta-data descriptions |
| partOfSpeech | Part of Speech | Select from Noun, Verb, Adjective, Pronoun, Adverb, Preposition, Conjunction, Interjection |
| pronunciation | Pronunciation | How does it sound? |
| synonyms | Synonyms | What else are you known by? |
| social (optional) | Social Network | Link to your favorite social networks, currently supported (but hidden if not used) Email, Facebook, Twitter, Instagram LinkedIn, Dribbble, Github, Last.fm

### Definitions
Definitions are the long-form body of your description. Currently supports up to 100 entries, and they can be ordered with the "Order" Variable. The title of each entry will be ignored and is only used for reference in NetlifyCMS.