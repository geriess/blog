# Blog
This is a repository for my personal blog [https://geries.com](https://geries.com).

## To create a new post:

```
hugo new posts/<directory name>/index.md --editor=vim
```

The above creates a new folder and index.md file to start drafting post. For images, place these inside each post's folder for maintaining related images with corresponding post.

## To insert images:

To insert an image into a post, use the following. This will use the bundle-image shortcode which creates various image sizes for various screens. Hugo handles everything else when the post is published. 

```
{{< bundle-image name="picture.jpg" alt="Description for screen readers." caption="Some caption"  >}}
```
