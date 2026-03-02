# DeviantArt RSS

Most DeviantArt features are available through RSS feed. For how to create RSS in DeviantArt, you can read the official instructions for example in ["How do I use RSS Feeds?"](https://www.deviantartsupport.com/en/article/how-do-i-use-rss-feeds) or ["Access deviations with RSS feeds"](https://www.deviantart.com/developers/rss). But even so, I managed to run into problem of creating RSS Feeds. I found two solutions for how to form a tape:

#### 1. We use an example from DeviantArt with changes.

```https://backend.deviantart.com/rss.xml?type=deviation&q=[name]+sort%3Atime+meta%3Aall```

For example https://backend.deviantart.com/rss.xml?type=deviation&q=zeon-in-a-tree+sort%3Atime+meta%3Aall

This method does not work with all profiles and for some profiles this method does not work.

#### 2. This is a universal way to create RSS Feeds.

```https://backend.deviantart.com/rss.xml?q=gallery:[name]```

For example https://backend.deviantart.com/rss.xml?q=gallery:zeon-in-a-tree

Also in this [repository](https://github.com/jamesl1001/deviantART-API) I found how to access a specific gallery.

For example ```https://backend.deviantart.com/rss.xml?q=gallery:[deviant name]/[gallery]```

## Accessing AI Art and Communities via RSS

DeviantArt has a growing community of AI art creators and enthusiasts. You can use RSS feeds to stay updated with AI-generated artwork and related communities.

### Search for AI-Generated Art

To get an RSS feed of AI-generated artwork across DeviantArt:

```https://backend.deviantart.com/rss.xml?q=by:*+in:artisan/animation+sort:time+AI```

Or search for specific AI art tags:

```https://backend.deviantart.com/rss.xml?q=tag:aiart+sort:time```
```https://backend.deviantart.com/rss.xml?q=tag:stablediffusion+sort:time```
```https://backend.deviantart.com/rss.xml?q=tag:midjourney+sort:time```
```https://backend.deviantart.com/rss.xml?q=tag:dalle+sort:time```

### Follow AI Art Communities and Groups

Many AI art communities have formed on DeviantArt. You can follow their activity through RSS:

```https://backend.deviantart.com/rss.xml?q=gallery:AI-Art-Community```
```https://backend.deviantart.com/rss.xml?q=gallery:AIGeneratedArt```
```https://backend.deviantart.com/rss.xml?q=gallery:Neural-Artists```

### Search Multiple AI-Related Terms

You can combine search terms to get more specific results:

```https://backend.deviantart.com/rss.xml?q=aiart+OR+generative+OR+neural+sort:time+meta:all```

### Filter by AI Art Categories

To focus on specific types of AI artwork:

```https://backend.deviantart.com/rss.xml?q=tag:aiart+in:digitalart/paintings+sort:time```
```https://backend.deviantart.com/rss.xml?q=tag:aiart+in:digitalart/3d+sort:time```

This allows you to connect with various AI art federations and communities across DeviantArt through RSS feeds, keeping you updated with the latest AI-generated creative content.


