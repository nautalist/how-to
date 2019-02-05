# How to be a Nautalist
A friendly, opinionated method for creating lo-fi, shareable, and reusable (and remixable?) lists of links in yaml

## What's a Nautalist?
> A Nautalist (as opposed to the cephlapod nautilus) is a wanna-be/made-up standard protocol for sharing lists of URLs with people across the web. Whether you're an educator trying to share an open list of educational resources with students or a parent passing a list of urls for recipes to your favorite dishes to your kids, formatting your list as a 'nautalist' can make it easy for both humans and computers to use.

Here's a simple example of a list of urls formatted in a friendly "nautalist" way:

Nicely formatted in `YAML`...

```yaml
name: "Hello Lovely People!"
description: "Making shareable and usable lists of links make my heart warm"
features:
- url: "https://itp.nyu.edu"
  name: "ITP/IMA @ NYU"
  description: "Based at NYU"
- url: "https://thecodingtrain.com/"
  name: "@Shiffman's Coding Train"
  description: "All aboard the Coding Train with Daniel Shiffman, a YouTube channel dedicated to beginner-friendly creative coding tutorials and challenges."
- url: "https://p5js.org/"
  name: "p5js website"
  description: "p5js is a javascript library to make coding more accessible to everyone"
```

...yields nicely formatted `JSON`:

```json
{
  "description": "Making shareable and usable lists of links make my heart warm", 
  "features": [
    {
      "url": "https://itp.nyu.edu", 
      "name": "ITP/IMA @ NYU", 
      "description": "Based at NYU"
    }, 
    {
      "url": "https://thecodingtrain.com/", 
      "name": "@Shiffman's Coding Train", 
      "description": "All aboard the Coding Train with Daniel Shiffman, a YouTube channel dedicated to beginner-friendly creative coding tutorials and challenges."
    }, 
    {
      "url": "https://p5js.org/", 
      "name": "p5js website", 
      "description": "p5js is a javascript library to make coding more accessible to everyone"
    }
  ], 
  "name": "Hello Lovely People!"
}
```




## Structure



## Learning YAML

https://learnxinyminutes.com/docs/yaml/

