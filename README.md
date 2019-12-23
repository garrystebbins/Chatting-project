### How to add yourself as an author

This repository is quite large. You can either clone it locally, or submit your request through the GitHub interface.

1. Go to [`/src/_data/authors/`](/src/_data/authors/)
2. Create a new file named `firstname-lastname.json` in this format:

```
{
  "name": "full-name",
  "photo": "photo.jpg",
  "bio": "I am a full-stack developer.",
  "twitter": "https://twitter.com/",
  "facebook": "https://facebook.com/",
  "linkedin": "https://www.linkedin.com/",
  "instagram": "https://instagram.com/"
}
```

3. Add your photo to [`/images/authors`](/images/authors), named using the filename listed in the `photo` field of your JSON
4. Open a pull request titled `Add author <firstname lastname>`

A maintainer of this repository will review and merge your pull request.

Thank you!
