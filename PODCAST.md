- [DevOps'ish Podcast](#devopsish-podcast)
  - [Purpose](#purpose)
  - [Sources](#sources)
  - [Twitter Space](#twitter-space)
    - [Title](#title)
  - [Share on Social Media](#share-on-social-media)
    - [Record](#record)
    - [Go Live](#go-live)
    - [Downloading](#downloading)
      - [Alternate Method](#alternate-method)
    - [Editing](#editing)
    - [Distribution (aka Anchor.fm)](#distribution-aka-anchorfm)
  - [Newsletter](#newsletter)
  - [Future Considerations](#future-considerations)

# DevOps'ish Podcast

This document seeks to give a HOWTO and Why for the DevOps'ish Podcast creation process.

## Purpose

- Go over the inputs into the newsletter (not neccesarily the newsletter itself) to give users a different look at the news
- Not a reguritation of the newsletter itself (unless asked)
- Have a live audience ([Twitter Spaces](https://help.twitter.com/en/using-twitter/spaces))
- Another advertising outlet for [Sponsors](https://devopsish.com/sponsor)
- Twitter Spaces isn't fully functional on desktop yet but, be sure to have it open on your laptop so you can paste links easily

## Sources

These all probably require my login to get the most accurate data, but they are definitely worth documenting for consistency:

- [Twitter Analytics](https://analytics.twitter.com/user/chrisshort/tweets)
  - Top Tweets
  - Last 7 days + 1-2
- [/r/devopsish](https://www.reddit.com/r/devopsish/top/?t=week)
  - 2-3+ upvotes depending on time
- [LinkedIn Recent Activity](https://www.linkedin.com/in/thechrisshort/recent-activity/)
  - 100+ impressions is worth mentioning
  - This is an awful way to get analytics but, I don't think there's another way.

## Twitter Space

- Create a Twitter Space for Monday AM ET
- Set it to be **recorded** or you're screwed

### Title

Title the Twitter Space:  
*The DevOps'ish Podcast: 2022-09-26*

## Share on Social Media

Share the new link ASAP, as a sticky post on [/r/devopsish](https://www.reddit.com/r/devopsish/): 

- Sticky Post
- Mark it as Moderator
- Mark as OC
- Mark as Spoiler
- Add Podcast flair
- Example: <https://www.reddit.com/r/devopsish/comments/yapjup/the_spooky_post_kubecon_special_edition_of_the/>

- Create additional Social Media
  - Day before
  - One hour before
  - 15 minutes before
  - Go live
  - Post once available via Podcast networks

### Record

- **Make sure you configure the Twitter Space to be recorded BEFORE you start it**
- Capture five seconds of dead air somewhere for the noise floor

### Go Live

To utilize my fancy mic hardware I'm using the following setup:

[Shure SM7B](https://amzn.to/3Rv9EZ3) -> [Cloudlifter](https://amzn.to/3SGsr5r) -> [Scarlett 2i2](https://amzn.to/3E68Wib) -> [Lightning Dongle (w/ power)](https://amzn.to/3LW2qMT) -> [iPhone](https://amzn.to/3E5LXUc)

### Downloading

Make use of [sw-yx/mech fork](https://github.com/chris-short/mech) to download the Twitter Space. This won't work if you forgot to record it). Dysfunctional example (note, it's not the URL, just the Space ID):

``` bash
twitter -c 1lDxLndplWvGm
```

Remember you'll have to make the `twitter` download executable and place it in your `$PATH` and it will only work if you recorded it.

#### Alternate Method

The alternate method is to pull it from your [Twitter data archive](https://twitter.com/settings/download_your_data) (which takes hours/days to be generated; and a week to expire).

### Editing

- Remove noise floor
- Keep it light and simple
- Trim beginning and ends
- Edit out anything before "Good Morning" (that's an incentive to join the Twitter Space early)
- Sponsor Pitch?
- Upload to [Anchor](https://anchor.fm/devopsish)

### Distribution (aka Anchor.fm)

All distribution is done via Anchor. The web site has a [Podcast page](https://devopsish.com/podcast) that makes use of the [`podcast` Hugo shortcode](https://github.com/chris-short/devopsish.com/blob/main/layouts/shortcodes/podcast.html) in the code base.

## Newsletter

Under the intro there is a subsection for the Twitter Space and Podcast. Be sure to update this weekly.

## Future Considerations

- Clean up other services pages (old URLs in Anchor) (DevOps'ish Deep Cuts to plain DevOps'ish Podcast)
  - It's not clear to me how this is done
  - Should open ticket with Anchor
- Add to Sponsor Prospectus and Sponsor page after 5 episodes
- Feature the podcast Hugo shortcode in more places?
- Bring Anchor page under devopsish.com (somehow: podcast.devopsish.com could have its own RSS feed?)
